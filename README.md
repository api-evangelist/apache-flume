# Apache Flume (apache-flume)
Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log and event data. It provides a simple and flexible architecture based on streaming data flows with pluggable sources, channels, and sinks, plus a REST monitoring API for agent metrics.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-flume/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Data Collection, ETL, Log Aggregation, Open Source, Streaming

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Flume Monitoring API
REST API for monitoring Apache Flume agents, retrieving component metrics for sources, channels, and sinks, and accessing agent health information.

**Human URL:** [https://flume.apache.org/FlumeUserGuide.html](https://flume.apache.org/FlumeUserGuide.html)

#### Tags:

 - Monitoring, Metrics, REST API

#### Properties

- [Documentation](https://flume.apache.org/FlumeUserGuide.html)
- [OpenAPI](openapi/apache-flume-monitoring-openapi.yml)
- [JSONSchema](json-schema/flume-monitoring-agent-metrics-schema.json)
- [JSON-LD](json-ld/apache-flume-monitoring-context.jsonld)

### Apache Flume Java API
Java API for building custom Flume sources, channels, sinks, and interceptors. Provides interfaces for developing pluggable data ingestion components.

**Human URL:** [https://flume.apache.org/FlumeDeveloperGuide.html](https://flume.apache.org/FlumeDeveloperGuide.html)

#### Tags:

 - Java, SDK, Extension

#### Properties

- [Documentation](https://flume.apache.org/FlumeDeveloperGuide.html)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.flume/flume-ng-core)

## Common Properties

- [Documentation](https://flume.apache.org/documentation.html)
- [GettingStarted](https://flume.apache.org/FlumeUserGuide.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/flume)

## Features

| Name | Description |
|------|-------------|
| Pluggable Sources | Extensible source architecture supporting Avro, Thrift, Exec, Taildir, Kafka, HTTP, Syslog, and custom sources. |
| Durable Channels | Multiple channel implementations including memory, file-backed, and Kafka-backed channels for different durability requirements. |
| Multi-Destination Sinks | Write events to HDFS, HBase, Solr, Elasticsearch, Kafka, and custom sink destinations. |
| Fan-In Consolidation | Aggregate events from multiple agent sources into a single destination for centralized log collection. |
| Fan-Out Distribution | Route events from a single source to multiple channel/sink combinations for parallel processing. |
| Interceptors | Event transformation interceptors for filtering, enrichment, and routing based on event content. |
| SSL/TLS Security | TLS encryption support across Avro, Thrift, Kafka, HTTP, and Syslog components. |
| Monitoring REST API | HTTP monitoring endpoint exposing source, channel, and sink metrics for agent health monitoring. |
| Multi-Hop Flows | Chain multiple Flume agents via Avro/Thrift RPC for tiered log aggregation architectures. |

## Use Cases

| Name | Description |
|------|-------------|
| Centralized Log Aggregation | Collect application logs from hundreds of servers and aggregate them into HDFS, Kafka, or Elasticsearch. |
| Real-Time Log Tailing | Tail application log files in real time using Taildir source for immediate event processing. |
| Syslog Ingestion | Ingest RFC-3164 and RFC-5424 syslog events from network devices into centralized storage. |
| Kafka Event Ingestion | Bridge Kafka topics to HDFS or other storage for batch analytics on streaming event data. |
| Multi-Tier Architectures | Build tiered data collection with edge collectors forwarding to aggregation agents and final destinations. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Kafka source and channel for consuming events, and Kafka sink for writing events to topics. |
| Apache HDFS | Primary sink for writing log data to Hadoop Distributed File System for batch analytics. |
| Apache HBase | HBase sink for writing events directly to HBase tables for random-access analytics. |
| Apache Solr | Solr sink for indexing log events for full-text search capabilities. |
| Elasticsearch | Elasticsearch sink for indexing and searching aggregated log data. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Flume Monitoring API](openapi/apache-flume-monitoring-openapi.yml)

### JSON Schema

- 2 schema files in [json-schema/](json-schema/)

### JSON Structure

- 2 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Flume Monitoring Context](json-ld/apache-flume-monitoring-context.jsonld)

### Examples

- 2 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Flume Monitoring API](capabilities/shared/flume-monitoring.yaml) — 1 operation for agent metrics retrieval

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Flume Log Collection](capabilities/flume-log-collection.yaml) | flume-monitoring | 1 | Data Engineer, Platform Operator |

## Vocabulary

- [Apache Flume Vocabulary](vocabulary/apache-flume-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 1 action, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Flume Spectral Rules](rules/apache-flume-spectral-rules.yml) — 7 rules across 4 categories enforcing Apache Flume API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
