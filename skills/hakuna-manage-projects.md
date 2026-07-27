---
name: Manage hakuna projects and clients
description: Create and maintain clients, projects, and tasks with an admin token, and read organization presence status.
api: openapi/hakuna-openapi.yml
operations: [listManagedClients, createManagedClient, listManagedProjects, createManagedProject, createManagedTask, getOrganizationStatus]
---

# Manage hakuna projects and clients

Set up the client → project → task hierarchy that time is tracked against. These are admin-only operations.

## Auth

Management endpoints require an admin `X-Auth-Token`; the organization status endpoint requires an organization-level token. Base URL: `https://app.hakuna.ch/api/v1`.

## Steps

1. List existing clients with `listManagedClients` (`GET /management/clients`); create one with `createManagedClient` (`POST /management/clients`) passing a `name`.
2. Create a project under that client with `createManagedProject` (`POST /management/projects`), passing `name` and the `client_id`.
3. Add categorization tasks with `createManagedTask` (`POST /management/tasks`).
4. Review who is present or absent across the organization with `getOrganizationStatus` (`GET /organization/status`).

## Notes

- Projects and clients can be archived (`archived: true`) rather than deleted to preserve historical time entries.
- Respect the 100 requests/minute limit when bulk-creating resources; back off on 429 using `Retry-After`.
