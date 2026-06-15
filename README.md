# Zipkin (zipkin)

Zipkin is an open source distributed tracing system for gathering timing data to troubleshoot latency problems in microservice architectures. It was originally developed at Twitter based on the Google Dapper paper, and is now a CNCF-related project maintained by the OpenZipkin community. Zipkin provides a collector, storage, and query service with a UI for visualizing trace data across distributed services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Distributed Tracing
- Observability
- Open Source
- Microservices

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Zipkin API V2

Zipkin's v2 HTTP API for querying and collecting distributed traces. Provides endpoints for submitting spans, querying traces, looking up services and span names, and retrieving dependency links between services.

- **Human URL:** [https://zipkin.io/zipkin-api/](https://zipkin.io/zipkin-api/)

#### Tags

- Dependencies
- Distributed Tracing
- Observability
- Spans
- Traces

#### Properties

- [Documentation](https://zipkin.io/zipkin-api/)
- [GitHub Repository](https://github.com/openzipkin/zipkin)
- [OpenAPI](openapi/zipkin-api-v2.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zipkin-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zipkin-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/zipkin-api-v2-span-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zipkin-api-v2-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zipkin-api-v2-annotation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zipkin-api-v2-dependency-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/zipkin-api-v2-span-structure.json)
- [JSON Structure](json-structure/zipkin-api-v2-endpoint-structure.json)
- [JSON Structure](json-structure/zipkin-api-v2-annotation-structure.json)
- [JSON Structure](json-structure/zipkin-api-v2-dependency-link-structure.json)
- [Example](examples/zipkin-api-v2-get-services-example.json)
- [Example](examples/zipkin-api-v2-get-dependencies-example.json)
- [Example](examples/zipkin-api-v2-report-spans-example.json)
- [Example](examples/zipkin-api-v2-search-traces-example.json)

## Common Properties

- [Website](https://zipkin.io)
- [Documentation](https://zipkin.io/pages/quickstart.html)
- [GitHub Organization](https://github.com/openzipkin)
- [SDK](https://github.com/openzipkin/brave)
- [SDK](https://github.com/openzipkin/zipkin-go)
- [SDK](https://github.com/openzipkin/zipkin-js)
- [SDK](https://github.com/openzipkin/zipkin-ruby)
- [JSON-LD](json-ld/zipkin-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/zipkin-spectral.yaml)
- [Vocabulary](vocabulary/zipkin-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
