# Apache Flume (apache-flume)

Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log and event data. It provides a simple and flexible architecture based on streaming data flows with pluggable sources, channels, and sinks, plus a REST monitoring API for agent metrics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Data Collection
- ETL
- Log Aggregation
- Open Source
- Streaming

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Flume Monitoring API

REST API for monitoring Apache Flume agents, retrieving component metrics for sources, channels, and sinks, and accessing agent health information.

- **Human URL:** [https://flume.apache.org/FlumeUserGuide.html](https://flume.apache.org/FlumeUserGuide.html)
- **Base URL:** `http://localhost:41414`

#### Tags

- Monitoring
- Metrics
- REST API

#### Properties

- [Documentation](https://flume.apache.org/FlumeUserGuide.html)
- [OpenAPI](openapi/apache-flume-monitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-flume-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-flume-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flume-monitoring-agent-metrics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-flume-monitoring-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache Flume Java API

Java API for building custom Flume sources, channels, sinks, and interceptors. Provides interfaces for developing pluggable data ingestion components.

- **Human URL:** [https://flume.apache.org/FlumeDeveloperGuide.html](https://flume.apache.org/FlumeDeveloperGuide.html)

#### Tags

- Java
- SDK
- Extension

#### Properties

- [Documentation](https://flume.apache.org/FlumeDeveloperGuide.html)
- [SDK](https://search.maven.org/artifact/org.apache.flume/flume-ng-core)
- [Postman Collection](collections/apache-flume-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-flume-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://flume.apache.org/documentation.html)
- [Getting Started](https://flume.apache.org/FlumeUserGuide.html)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/flume)
- [Spectral Rules](rules/apache-flume-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-flume-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
