# Oracle Cloud Infrastructure Skills

This domain is scaffolded for future Oracle Cloud Infrastructure skills.

This domain will cover OCI service usage, architecture, automation, security, and operational workflows.

## How to Use This Domain

1. Start with the routing table below.
2. Read only the specific file or category you need.
3. Add new OCI skills under the planned category structure as content lands.

## Directory Structure

```text
skills/oci/
├── core/           Planned: tenancy, regions, compartments, IAM
├── compute/        Planned: instances, images, autoscaling
├── networking/     Planned: VCN, load balancers, DNS, connectivity
├── storage/        Planned: object, block, file, backup
├── databases/      Planned: OCI database services and operations
├── security/       Planned: IAM, vault, key management, guardrails
├── observability/  Planned: logging, monitoring, alarms, tracing
├── devops/         Planned: pipelines, resource manager, automation
└── integration/    Planned: functions, events, api gateway, messaging
```

## Category Routing

| Topic | Directory |
|-------|-----------|
| Tenancy structure, compartments, IAM, quotas, tagging | `skills/oci/core/` |
| Compute instances, custom images, autoscaling, OS management | `skills/oci/compute/` |
| VCN, subnets, gateways, load balancers, DNS, connectivity | `skills/oci/networking/` |
| Object Storage, Block Volumes, File Storage, backups | `skills/oci/storage/` |
| OCI database services, lifecycle operations, connectivity | `skills/oci/databases/` |
| Vault, keys, secrets, security zones, cloud guard | `skills/oci/security/` |
| Logging, Monitoring, Alarms, Events, tracing | `skills/oci/observability/` |
| Resource Manager, CLI, Terraform, pipelines, automation | `skills/oci/devops/` |
| Functions, API Gateway, Streaming, Notifications, integration patterns | `skills/oci/integration/` |

## Key Starting Points

- Domain scaffold only
- Add the first entry-point skills under `core/`, `networking/`, and `devops/`
- Prefer OCI documentation and service-specific examples

## Common Multi-Step Flows

| Task | Recommended Sequence |
|------|----------------------|
| Provision a secure OCI environment | `core` → `networking` → `security` |
| Deploy an application on OCI | `compute` → `networking` → `observability` |
| Automate OCI infrastructure changes | `devops` → `security` → `observability` |
