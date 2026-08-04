# Zipkin (zipkin)

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
