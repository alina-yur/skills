# Oracle Fusion Skills

This domain is scaffolded for future Oracle Fusion skills.

This domain will cover Fusion application configuration, extension, integration, reporting, and operational guidance across major Fusion product families.

## How to Use This Domain

1. Start with the routing table below.
2. Read only the specific file or category you need.
3. Add new Fusion skills under the planned category structure as content lands.

## Directory Structure

```text
skills/fusion/
├── common/         Planned: platform concepts, environments, navigation
├── erp/            Planned: financials, procurement, project operations
├── hcm/            Planned: core HR, payroll, talent, recruiting
├── scm/            Planned: supply chain, manufacturing, inventory
├── cx/             Planned: sales, service, marketing workflows
├── platform/       Planned: visual builder, app composer, extensions
├── integration/    Planned: OIC, REST, SOAP, events, data sync
├── reporting/      Planned: OTBI, BI Publisher, analytics
└── security/       Planned: roles, data security, environment controls
```

## Category Routing

| Topic | Directory |
|-------|-----------|
| Shared Fusion concepts, environment setup, navigation | `skills/fusion/common/` |
| ERP configuration and workflows | `skills/fusion/erp/` |
| HCM configuration and workflows | `skills/fusion/hcm/` |
| SCM configuration and workflows | `skills/fusion/scm/` |
| CX configuration and workflows | `skills/fusion/cx/` |
| Visual Builder, App Composer, Redwood extensions | `skills/fusion/platform/` |
| Integration patterns, APIs, events, and data movement | `skills/fusion/integration/` |
| OTBI, BI Publisher, dashboards, analytics | `skills/fusion/reporting/` |
| Roles, privileges, data access, environment governance | `skills/fusion/security/` |

## Key Starting Points

- Domain scaffold only
- Add the first entry-point skills under `common/`, `platform/`, and `integration/`
- Keep product-family guidance separated unless the workflow is truly shared

## Common Multi-Step Flows

| Task | Recommended Sequence |
|------|----------------------|
| Extend a Fusion workflow | `common` → `platform` → `security` |
| Integrate Fusion with external systems | `common` → `integration` → `reporting` |
| Roll out a business configuration safely | `common` → product family (`erp`/`hcm`/`scm`/`cx`) → `security` |
