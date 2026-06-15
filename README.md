# TiKV (tikv)

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
