# Apache HttpComponents (apache-http)
Apache HttpComponents is a set of Java HTTP components, including a feature-rich HTTP client (HttpClient 5.x) and HTTP server components. It provides connection pooling, async I/O, TLS/SSL support, authentication, cookie management, and content negotiation for Java applications making HTTP requests.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-http/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, HTTP Client, Java, Open Source, SDK

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache HttpComponents Client API
Java HTTP client library API for executing HTTP requests with connection pooling, async I/O, TLS/SSL, authentication, cookie management, and proxy support via Apache HttpComponents 5.x.

**Human URL:** [https://hc.apache.org/httpcomponents-client-5.3.x/](https://hc.apache.org/httpcomponents-client-5.3.x/)

#### Tags:

 - Authentication, Connection Pooling, HTTP Client, Java, TLS

#### Properties

- [Documentation](https://hc.apache.org/httpcomponents-client-5.3.x/)
- [OpenAPI](openapi/apache-http-client-openapi.yml)
- [JSONSchema](json-schema/http-client-httprequest-schema.json)
- [JSON-LD](json-ld/apache-http-client-context.jsonld)

### Apache HttpComponents Java SDK
Maven artifact for Apache HttpComponents HttpClient 5.x providing full HTTP client functionality including fluent API, async client, and reactive streams support.

**Human URL:** [https://hc.apache.org/httpcomponents-client-5.3.x/dependency-info.html](https://hc.apache.org/httpcomponents-client-5.3.x/dependency-info.html)

#### Tags:

 - Java, Maven, SDK

#### Properties

- [Documentation](https://hc.apache.org/httpcomponents-client-5.3.x/dependency-info.html)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.httpcomponents.client5/httpclient5)

## Common Properties

- [Documentation](https://hc.apache.org/)
- [GettingStarted](https://hc.apache.org/httpcomponents-client-5.3.x/quickstart.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/httpcomponents-client)

## Features

| Name | Description |
|------|-------------|
| Connection Pooling | Configurable connection pool with per-route and total connection limits for efficient HTTP connection reuse. |
| Async HTTP Client | Non-blocking async HTTP client based on Java NIO for high-concurrency request execution. |
| TLS/SSL Support | Full TLS/SSL support with customizable trust stores, client certificates, and hostname verification. |
| Authentication Framework | Pluggable authentication framework supporting Basic, Digest, NTLM, and Bearer token schemes. |
| Cookie Management | RFC-compliant cookie management with customizable cookie stores and policies. |
| Proxy Support | HTTP, HTTPS, and SOCKS proxy support with proxy authentication. |
| Content Negotiation | Built-in content encoding, compression (gzip/deflate), and charset negotiation. |
| Fluent API | High-level fluent API for simplified one-liner HTTP request execution. |

## Use Cases

| Name | Description |
|------|-------------|
| REST API Client Integration | Consume REST APIs from Java applications with connection pooling and retry logic. |
| Web Scraping | Crawl and fetch web content with cookie handling and redirect following. |
| Microservices HTTP Communication | Make service-to-service HTTP calls with connection reuse and timeout configuration. |
| Authentication Token Refresh | Implement OAuth2 token refresh flows using the authentication interceptor framework. |
| File Upload and Download | Stream large file uploads and downloads via multipart or chunked transfer encoding. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Framework | Spring RestTemplate and WebClient use Apache HttpComponents as a configurable HTTP backend. |
| Apache CXF | Apache CXF JAX-RS client uses HttpComponents for HTTP transport in web service calls. |
| Elasticsearch Java Client | Elasticsearch Java client uses HttpComponents for transport-layer HTTP communication. |
| Apache Solr | Apache Solr Java client (SolrJ) uses HttpComponents for Solr HTTP API calls. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache HttpComponents Client API](openapi/apache-http-client-openapi.yml)

### JSON Schema

- 4 schema files in [json-schema/](json-schema/)

### JSON Structure

- 4 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache HttpComponents Client Context](json-ld/apache-http-client-context.jsonld)

### Examples

- 4 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache HttpComponents Client API](capabilities/shared/http-client.yaml) — 3 operations for request execution and configuration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache HttpComponents HTTP Client Integration](capabilities/http-client-integration.yaml) | http-client | 3 | Application Developer |

## Vocabulary

- [Apache HttpComponents Vocabulary](vocabulary/apache-http-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 3 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache HttpComponents Spectral Rules](rules/apache-http-spectral-rules.yml) — 7 rules across 4 categories enforcing Apache HttpComponents API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
