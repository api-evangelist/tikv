# TiKV (tikv)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

TiKV is a CNCF-graduated distributed transactional key-value database built in Rust with Raft consensus. Originally created to complement TiDB, it provides horizontal scalability, strong consistency, and high availability with ACID transaction support. Client APIs are available for Java, Rust, Python, Go, and C++. An HTTP management API provides status, configuration, and monitoring endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- ACID
- CNCF
- Database
- Distributed Systems
- Key-Value Store
- Open Source
- Rust

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### TiKV HTTP Management API

TiKV exposes an HTTP API for cluster management, status monitoring, configuration retrieval and updates, and Prometheus metrics collection.

- **Human URL:** [https://tikv.org/docs/dev/deploy/monitor/api/](https://tikv.org/docs/dev/deploy/monitor/api/)
- **Base URL:** `http://localhost:20160`

#### Tags

- Database
- Distributed Systems
- Monitoring
- Operations

#### Properties

- [Documentation](https://tikv.org/docs/dev/deploy/monitor/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tikv/refs/heads/main/openapi/tikv-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tikv-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tikv-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TiKV Java Client

The official Java client for TiKV. Supports raw key-value operations and transactional operations via gRPC. Available on Maven Central.

- **Human URL:** [https://github.com/tikv/client-java](https://github.com/tikv/client-java)

#### Tags

- Database
- Java
- Key-Value
- SDK

#### Properties

- [Documentation](https://github.com/tikv/client-java)
- [Git Hub](https://github.com/tikv/client-java)
- [Postman Collection](collections/tikv-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tikv-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TiKV Rust Client

The official Rust client for TiKV providing raw and transactional key-value access to TiKV clusters.

- **Human URL:** [https://github.com/tikv/client-rust](https://github.com/tikv/client-rust)

#### Tags

- Database
- Key-Value
- Rust
- SDK

#### Properties

- [Documentation](https://github.com/tikv/client-rust)
- [Git Hub](https://github.com/tikv/client-rust)
- [Postman Collection](collections/tikv-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tikv-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TiKV Python Client

The official Python client for TiKV supporting raw and transactional key-value operations.

- **Human URL:** [https://github.com/tikv/client-py](https://github.com/tikv/client-py)

#### Tags

- Database
- Key-Value
- Python
- SDK

#### Properties

- [Documentation](https://github.com/tikv/client-py)
- [Git Hub](https://github.com/tikv/client-py)
- [Postman Collection](collections/tikv-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tikv-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/pingcap)
- [Website](https://tikv.org/)
- [Documentation](https://tikv.org/docs/)
- [Getting Started](https://tikv.org/docs/7.1/concepts/overview/)
- [GitHub Organization](https://github.com/tikv)
- [GitHub Repository](https://github.com/tikv/tikv)
- [Governance](https://github.com/tikv/tikv/blob/master/GOVERNANCE.md)
- [C N C F](https://www.cncf.io/projects/tikv/)
- [Blog](https://tikv.org/blog/)
- [Community](https://tikv.org/community/)
- [Roadmap](https://github.com/tikv/tikv/blob/master/ROADMAP.md)
- [License](https://github.com/tikv/tikv/blob/master/LICENSE)
- [Slack](https://slack.tidb.io/invite?team=tikv-wg)
- [Forum](https://internals.tidb.io/)
- [SDK](https://github.com/tikv/client-java)
- [SDK](https://github.com/tikv/client-rust)
- [SDK](https://github.com/tikv/client-py)
- [SDK](https://github.com/tikv/client-go)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
