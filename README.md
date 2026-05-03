# Zipkin (zipkin)
Zipkin is an open source distributed tracing system for gathering timing data to troubleshoot latency problems in microservice architectures. It was originally developed at Twitter based on the Google Dapper paper, and is now a CNCF-related project maintained by the OpenZipkin community. Zipkin provides a collector, storage, and query service with a UI for visualizing trace data across distributed services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Tracing, Observability, Open Source, Microservices

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### Zipkin API V2
Zipkin's v2 HTTP API for querying and collecting distributed traces. Provides endpoints for submitting spans, querying traces, looking up services and span names, and retrieving dependency links between services.

**Human URL:** [https://zipkin.io/zipkin-api/](https://zipkin.io/zipkin-api/)

#### Tags:

 - Dependencies, Distributed Tracing, Observability, Spans, Traces

#### Properties

- [Documentation](https://zipkin.io/zipkin-api/)
- [GitHubRepository](https://github.com/openzipkin/zipkin)
- [OpenAPI](openapi/zipkin-api-v2.yml)
- [JSONSchema - Span](json-schema/zipkin-api-v2-span-schema.json)
- [JSONSchema - Endpoint](json-schema/zipkin-api-v2-endpoint-schema.json)
- [JSONSchema - Annotation](json-schema/zipkin-api-v2-annotation-schema.json)
- [JSONSchema - DependencyLink](json-schema/zipkin-api-v2-dependency-link-schema.json)
- [JSONStructure - Span](json-structure/zipkin-api-v2-span-structure.json)
- [JSONStructure - Endpoint](json-structure/zipkin-api-v2-endpoint-structure.json)
- [JSONStructure - Annotation](json-structure/zipkin-api-v2-annotation-structure.json)
- [JSONStructure - DependencyLink](json-structure/zipkin-api-v2-dependency-link-structure.json)
- [Example - Get Services](examples/zipkin-api-v2-get-services-example.json)
- [Example - Get Dependencies](examples/zipkin-api-v2-get-dependencies-example.json)
- [Example - Report Spans](examples/zipkin-api-v2-report-spans-example.json)
- [Example - Search Traces](examples/zipkin-api-v2-search-traces-example.json)

## Common Properties

- [Website](https://zipkin.io)
- [Documentation](https://zipkin.io/pages/quickstart.html)
- [GitHubOrganization](https://github.com/openzipkin)
- [SDK - Brave (Java)](https://github.com/openzipkin/brave)
- [SDK - zipkin-go (Go)](https://github.com/openzipkin/zipkin-go)
- [SDK - zipkin-js (JavaScript/Node.js)](https://github.com/openzipkin/zipkin-js)
- [SDK - zipkin-ruby (Ruby)](https://github.com/openzipkin/zipkin-ruby)
- [JSONLD](json-ld/zipkin-context.jsonld)
- [SpectralRules](rules/zipkin-spectral.yaml)
- [NaftikoCapability](capabilities/distributed-tracing-investigation.yaml)
- [Vocabulary](vocabulary/zipkin-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Distributed Tracing | End-to-end tracing of requests across microservices. |
| Span Collection | Ingestion of spans via HTTP, Kafka, and other transports. |
| Trace Search | Query traces by service, span name, tags, and time range. |
| Dependency Graph | Derived service-to-service dependency links from spans. |
| UI | Web-based UI for exploring traces and dependency graphs. |
| Pluggable Storage | Pluggable backends including in-memory, MySQL, Cassandra, and Elasticsearch. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Latency Debugging | Identify slow services and operations in a microservice architecture. |
| Error Investigation | Trace failed requests across services to find error origin. |
| Service Dependency Mapping | Visualize which services call which, with call counts. |
| Performance Optimization | Identify hotspots and optimize critical-path operations. |

## Integrations

| Name | Description |
|------|-------------|
| Brave | Java instrumentation library for OpenZipkin. |
| OpenTelemetry | OpenTelemetry can export traces to Zipkin. |
| Spring Cloud Sleuth | Spring framework integration emitting Zipkin traces. |
| Kafka | Span transport via Kafka for asynchronous ingestion. |
| Elasticsearch | Storage backend for spans and traces at scale. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Zipkin API V2](openapi/zipkin-api-v2.yml)

### JSON Schema

- [Span](json-schema/zipkin-api-v2-span-schema.json)
- [Endpoint](json-schema/zipkin-api-v2-endpoint-schema.json)
- [Annotation](json-schema/zipkin-api-v2-annotation-schema.json)
- [DependencyLink](json-schema/zipkin-api-v2-dependency-link-schema.json)

### JSON Structure

- [Span](json-structure/zipkin-api-v2-span-structure.json)
- [Endpoint](json-structure/zipkin-api-v2-endpoint-structure.json)
- [Annotation](json-structure/zipkin-api-v2-annotation-structure.json)
- [DependencyLink](json-structure/zipkin-api-v2-dependency-link-structure.json)

### JSON-LD

- [Zipkin Context](json-ld/zipkin-context.jsonld)

### Examples

- [Get Services](examples/zipkin-api-v2-get-services-example.json)
- [Get Dependencies](examples/zipkin-api-v2-get-dependencies-example.json)
- [Report Spans](examples/zipkin-api-v2-report-spans-example.json)
- [Search Traces](examples/zipkin-api-v2-search-traces-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zipkin API V2](capabilities/shared/zipkin-api-v2.yaml) — 9 operations for distributed tracing ingestion and query

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Distributed Tracing Investigation](capabilities/distributed-tracing-investigation.yaml) | zipkin-api-v2 | 6 | Site Reliability Engineer |

## Vocabulary

- [Zipkin Vocabulary](vocabulary/zipkin-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 9 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Zipkin Spectral Ruleset](rules/zipkin-spectral.yaml) — 6 rules across naming, operation, and structure categories enforcing Zipkin API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
