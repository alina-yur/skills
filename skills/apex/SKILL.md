# Oracle APEX Skills

This domain is scaffolded for future Oracle APEX skills.

This domain will cover Oracle APEX application development, workspace administration, security, deployment, data access, and extension patterns.

## How to Use This Domain

1. Start with the routing table below.
2. Read only the specific file or category you need.
3. Add new APEX skills under the planned category structure as content lands.

## Directory Structure

```text
skills/apex/
├── app-dev/        Planned: pages, items, processes, dynamic actions
├── data/           Planned: SQL, REST data sources, forms, reports
├── security/       Planned: authn, authz, session protection
├── ui/             Planned: themes, templates, Redwood, accessibility
├── integration/    Planned: REST, webhooks, external services
├── deployment/     Planned: export, install, CI/CD, environment promotion
└── admin/          Planned: workspaces, instance settings, operations
```

## Category Routing

| Topic | Directory |
|-------|-----------|
| Pages, regions, items, processes, dynamic actions | `skills/apex/app-dev/` |
| SQL queries, forms, reports, REST data sources | `skills/apex/data/` |
| Authentication, authorization, session security | `skills/apex/security/` |
| Themes, templates, Redwood UI, accessibility | `skills/apex/ui/` |
| REST APIs, external services, integration patterns | `skills/apex/integration/` |
| Application export, deployment, promotion, CI/CD | `skills/apex/deployment/` |
| Workspace administration, instance operations, governance | `skills/apex/admin/` |

## Key Starting Points

- Domain scaffold only
- Add the first entry-point skills under `app-dev/`, `data/`, and `deployment/`
- Keep APEX guidance focused on practical build and runtime workflows

## Common Multi-Step Flows

| Task | Recommended Sequence |
|------|----------------------|
| Build a new APEX application feature | `app-dev` → `data` → `ui` |
| Secure an APEX application | `security` → `app-dev` → `admin` |
| Promote an app across environments | `deployment` → `security` → `admin` |
