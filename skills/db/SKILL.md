# Oracle Database Skills

This domain contains Oracle Database skills for administration, SQL and PL/SQL development, performance tuning, security, ORDS, SQLcl, migrations, frameworks, OCR container guidance, and agent-safe database workflows.

## How to Use This Domain

1. Start with the routing table below.
2. Read only the specific file or category you need.

## Directory Structure

```text
skills/db/
├── admin/
├── ai/
├── agent/
├── appdev/
├── architecture/
├── containers/
├── design/
├── devops/
├── features/
├── frameworks/
├── migrations/
├── monitoring/
├── ords/
├── performance/
├── plsql/
├── security/
├── sql-dev/
└── sqlcl/
```

## Category Routing

| Topic | Directory |
|-------|-----------|
| Backup, recovery, RMAN, Data Guard, redo/undo logs, users | `skills/db/admin/` |
| Select AI, AI Vector Search, embeddings, vector indexes, RAG, AI profiles, AI security | `skills/db/ai/` |
| Safe DML, destructive operation guards, idempotency, schema discovery, ORA- error handling | `skills/db/agent/` |
| JDBC, pooling, JSON, XML, spatial, Oracle Text, transactions, MLE, language drivers | `skills/db/appdev/` |
| RAC, Multitenant, Exadata, In-Memory, OCI database services, Data Guard architecture | `skills/db/architecture/` |
| OCR database-category container images and pull guidance | `skills/db/containers/` |
| ERD, data modeling, partitioning, tablespaces | `skills/db/design/` |
| Schema migrations, online operations, edition-based redefinition, testing, version control | `skills/db/devops/` |
| AQ, DBMS_SCHEDULER, materialized views, DBLinks, APEX, vector search, SELECT AI | `skills/db/features/` |
| SQLAlchemy, Django, Pandas, Spring JPA, MyBatis, TypeORM, Sequelize, Dapper, GORM | `skills/db/frameworks/` |
| Migrations from PostgreSQL, MySQL, SQL Server, MongoDB, Snowflake, and more | `skills/db/migrations/` |
| Alert log, ADR, health monitor, space management, top SQL | `skills/db/monitoring/` |
| ORDS architecture, installation, REST design, authentication, monitoring | `skills/db/ords/` |
| AWR, ASH, explain plan, indexes, optimizer stats, wait events, memory | `skills/db/performance/` |
| Package design, error handling, performance, collections, cursors, debugging | `skills/db/plsql/` |
| Privileges, VPD, masking, auditing, encryption, network security | `skills/db/security/` |
| SQL tuning, SQL patterns, dynamic SQL, injection avoidance | `skills/db/sql-dev/` |
| SQLcl basics, scripting, Liquibase, formatting, DDL generation, data loading, MCP server | `skills/db/sqlcl/` |

## Key Starting Points

- `skills/db/sqlcl/sqlcl-mcp-server.md`
- `skills/db/ai/select-ai.md`
- `skills/db/ai/ai-vector-search.md`
- `skills/db/migrations/migration-assessment.md`
- `skills/db/performance/explain-plan.md`
- `skills/db/plsql/plsql-package-design.md`
- `skills/db/devops/schema-migrations.md`
- `skills/db/agent/schema-discovery.md`
- `skills/db/containers/container-selection-matrix.md`

## Common Multi-Step Flows

| Task | Recommended Sequence |
|------|----------------------|
| Diagnose a slow query | `explain-plan` → `wait-events` → `optimizer-stats` → `awr-reports` |
| Plan a migration | `migration-assessment` → `oracle-migration-tools` → source-specific `migrate-*.md` → `migration-cutover-strategy` |
| Build RAG on Oracle Database | `ai/select-ai.md` → `select-ai-rag` → `vector-embeddings` → `vector-indexes` |
| Perform agent-safe schema change | `schema-discovery` → `destructive-op-guards` → `idempotency-patterns` → `schema-migrations` |
