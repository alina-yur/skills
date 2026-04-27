# Oracle Graal Skills

This domain is scaffolded for future Graal and GraalVM-related Oracle skills.

This domain will cover GraalVM development, native image workflows, polyglot runtime usage, performance tuning, and deployment patterns.

## How to Use This Domain

1. Start with the routing table below.
2. Read only the specific file or category you need.
3. Add new Graal skills under the planned category structure as content lands.

## Directory Structure

```text
skills/graal/
├── core/           Planned: GraalVM setup, runtimes, tooling
├── java/           Planned: JVM mode, optimization, framework usage
├── native-image/   Planned: builds, config, debugging, startup tuning
├── polyglot/       Planned: JS, Python, Ruby, interop patterns
├── frameworks/     Planned: Spring, Micronaut, Quarkus, Helidon
├── observability/  Planned: diagnostics, profiling, troubleshooting
└── deployment/     Planned: containers, serverless, OCI integration
```

## Category Routing

| Topic | Directory |
|-------|-----------|
| GraalVM installation, runtimes, tooling basics | `skills/graal/core/` |
| Java on GraalVM, JVM mode, performance tuning | `skills/graal/java/` |
| Native image configuration, builds, debugging, optimization | `skills/graal/native-image/` |
| Polyglot runtimes and language interop | `skills/graal/polyglot/` |
| Framework-specific GraalVM guidance | `skills/graal/frameworks/` |
| Diagnostics, profiling, troubleshooting | `skills/graal/observability/` |
| Container, serverless, and OCI deployment patterns | `skills/graal/deployment/` |

## Key Starting Points

- Domain scaffold only
- Add the first entry-point skills under `core/`, `native-image/`, and `deployment/`
- Keep framework-specific guidance separate from runtime fundamentals

## Common Multi-Step Flows

| Task | Recommended Sequence |
|------|----------------------|
| Build and tune a native image | `core` → `native-image` → `observability` |
| Deploy a GraalVM application | `java` or `frameworks` → `deployment` → `observability` |
| Add polyglot runtime capabilities | `core` → `polyglot` → `deployment` |
