# TiKV

TiKV is a CNCF-graduated distributed transactional key-value database built in Rust with Raft consensus. Originally created to complement TiDB, it provides horizontal scalability, strong consistency, and high availability with ACID transaction support. Client APIs are available for Java, Rust, Python, Go, and C++. An HTTP management API provides status, configuration, and monitoring endpoints.

**Human URL:** https://tikv.org/

## APIs

| Name | Description |
|---|---|
| [TiKV HTTP Management API](https://tikv.org/docs/dev/deploy/monitor/api/) | HTTP API for node status, config, metrics, and region inspection |
| [TiKV Java Client](https://github.com/tikv/client-java) | Java client via gRPC |
| [TiKV Rust Client](https://github.com/tikv/client-rust) | Rust client via gRPC |
| [TiKV Python Client](https://github.com/tikv/client-py) | Python client via gRPC |

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [TiKV HTTP API](openapi/tikv-http-api-openapi.yml) | Node status, config, metrics, and region endpoints |

## Capabilities

| Capability | APIs Used | Description |
|---|---|---|
| [Cluster Operations](capabilities/cluster-operations.yaml) | HTTP Management API | Node health, config, metrics, and region management |

### Shared API Definitions

| Shared Definition | Description |
|---|---|
| [tikv-http-api.yaml](capabilities/shared/tikv-http-api.yaml) | TiKV HTTP management API consumed definition |

## Rules

| Ruleset | Description |
|---|---|
| [tikv-rules.yml](rules/tikv-rules.yml) | Spectral ruleset for TiKV API conventions |

## Schemas

| Schema | Description |
|---|---|
| [tikv-region-schema.json](json-schema/tikv-region-schema.json) | JSON Schema for TiKV Raft region |

## Structures

| Structure | Description |
|---|---|
| [tikv-region-structure.json](json-structure/tikv-region-structure.json) | Raft region field structure |

## JSON-LD

| Context | Description |
|---|---|
| [tikv-context.jsonld](json-ld/tikv-context.jsonld) | JSON-LD context for TiKV concepts |

## Examples

| Example | Description |
|---|---|
| [Get Status](examples/tikv-getStatus-example.json) | TiKV node status response |
| [Get Region by ID](examples/tikv-getRegionById-example.json) | Region metadata response |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [tikv-vocabulary.yml](vocabulary/tikv-vocabulary.yml) | TiKV distributed systems vocabulary |

## Common Properties

- **Website:** https://tikv.org/
- **Documentation:** https://tikv.org/docs/
- **GitHub:** https://github.com/tikv
- **CNCF:** https://www.cncf.io/projects/tikv/
- **Blog:** https://tikv.org/blog/
- **License:** Apache 2.0

## Maintainers

**Kin Lane** (kin@apievangelist.com)
