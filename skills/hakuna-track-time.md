---
name: Track time with hakuna
description: Start and stop the running timer, or create a time entry directly, and read the resulting overview metrics.
api: openapi/hakuna-openapi.yml
operations: [getTimer, startTimer, stopTimer, createTimeEntry, listTimeEntries, getOverview]
---

# Track time with hakuna

Record worked time for the authenticated user, either with the running timer or by posting a completed time entry.

## Auth

Every request needs the `X-Auth-Token` header set to a personal API token (managed under "My Settings"). Base URL: `https://app.hakuna.ch/api/v1`. Stay under 100 requests/minute or you get a 429 with a `Retry-After` header.

## Steps

1. Check whether a timer is already running with `getTimer` (`GET /timer`). If one is running you should stop it before starting a new one.
2. Start tracking with `startTimer` (`POST /timer`), optionally passing `task_id`, `project_id`, and a `note`.
3. When finished, stop with `stopTimer` (`DELETE /timer`) — this converts the timer into a time entry.
4. To log time after the fact instead, use `createTimeEntry` (`POST /time_entries`) with `start_time`, `end_time`, and optional `task_id`/`project_id`.
5. Confirm with `listTimeEntries` (`GET /time_entries`) and read balances with `getOverview` (`GET /overview`).

## Notes

- Errors come back as JSON with a `message` field (401 invalid token, 422 validation, 429 rate limit).
- There is no idempotency-key mechanism; check `getTimer` before starting to avoid duplicate running timers.
