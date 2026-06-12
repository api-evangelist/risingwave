# RisingWave (risingwave)

RisingWave is a distributed SQL streaming platform that continuously ingests event streams from Kafka, Kinesis, and other sources, transforms them using PostgreSQL-compatible SQL, and serves low-latency results through incrementally maintained materialized views. It delivers sub-100ms freshness for operational workloads and supports streaming analytics via Apache Iceberg integration with exactly-once semantics.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/risingwave/refs/heads/main/apis.yml
- **Naftiko Fleet:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=risingwave-api-evangelist&utm_content=repo

## Tags

Streaming, SQL, Database, Real-Time, Kafka, Materialized Views, PostgreSQL, Apache Iceberg, Cloud

## APIs

| API | Description |
|-----|-------------|
| RisingWave SQL API | PostgreSQL-compatible SQL interface for ingesting streaming data, defining materialized views, and running analytical queries |
| RisingWave MCP Server | Model Context Protocol server exposing 100+ tools for AI agents to query and manage RisingWave instances |
| RisingWave Cloud CLI | CLI tool (rwc) for RisingWave Cloud infrastructure management and agent skill installation |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/risingwave-plans-pricing.yml](plans/risingwave-plans-pricing.yml) |
| Rate Limits | [rate-limits/risingwave-rate-limits.yml](rate-limits/risingwave-rate-limits.yml) |
| FinOps | [finops/risingwave-finops.yml](finops/risingwave-finops.yml) |

RisingWave Cloud billing is compute (RWU-hour at $0.227/RWU/hr on Basic), storage ($0.0299/GB-month), and network transfer (per GB). A 7-day free trial is included. Pro and Self-Managed plans are available with custom pricing and annual contracts.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://risingwave.com/ |
| Documentation | https://docs.risingwave.com |
| GitHub Organization | https://github.com/risingwavelabs |
| LinkedIn | https://www.linkedin.com/company/risingwave |
| X (Twitter) | https://x.com/RisingWaveLabs |
| Blog | https://risingwave.com/blog |
| Pricing | https://risingwave.com/pricing/ |
| Changelog | https://docs.risingwave.com/changelog/release-notes |
| Slack Community | https://go.risingwave.com/slack |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
