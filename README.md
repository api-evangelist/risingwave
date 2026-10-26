# RisingWave (risingwave)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
