# Looker (looker)

Looker is a business intelligence and data analytics platform that enables organizations to explore, analyze, and share real-time business analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Analytics
- BI Platform
- Business Intelligence
- Data Analytics
- Data Visualization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Looker API

The Looker API provides programmatic access to Looker functionality including running queries, managing users, creating dashboards, and administering the platform.

- **Human URL:** [https://developers.looker.com/api/explorer/4.0](https://developers.looker.com/api/explorer/4.0)
- **Base URL:** `https://your-instance.looker.com:19999/api/4.0`

#### Tags

- Analytics
- Dashboards
- Queries
- REST API

#### Properties

- [Documentation](https://developers.looker.com/api/getting-started)
- [OpenAPI](openapi/looker-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.looker.com/api/getting-started#authentication)
- [SDK](https://developers.looker.com/api/sdks)
- [Console](https://developers.looker.com/api/explorer/4.0)
- [Rate Limits](https://cloud.google.com/looker/docs/api-rate-limits)
- [API Reference](https://docs.cloud.google.com/looker/docs/reference/looker-api/latest)
- [Getting Started](https://docs.cloud.google.com/looker/docs/api-getting-started)
- [Versioning](https://docs.cloud.google.com/looker/docs/api-versioning)

### LookML API

API for programmatically managing LookML projects, models, and views.

- **Human URL:** [https://developers.looker.com/api/explorer/4.0/methods/Project](https://developers.looker.com/api/explorer/4.0/methods/Project)
- **Base URL:** `https://your-instance.looker.com:19999/api/4.0`

#### Tags

- Data Modeling
- LookML
- Projects

#### Properties

- [Documentation](https://developers.looker.com/api/explorer/4.0/methods/Project)
- [Tutorials](https://developers.looker.com/api/lookml-validation)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Action API

The Looker Action API enables developers to define custom actions, or destinations, to which Looker can send query results, dashboard results, or user interactions via a webhook-like API.

- **Human URL:** [https://docs.cloud.google.com/looker/docs/actions-overview](https://docs.cloud.google.com/looker/docs/actions-overview)
- **Base URL:** `https://your-instance.looker.com:19999/api/4.0`

#### Tags

- Actions
- Data Delivery
- Integrations
- Webhooks

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/actions-overview)
- [GitHub Repository](https://github.com/looker-open-source/actions)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Embed SDK

The Looker Embed SDK is a JavaScript library for embedding Looker content such as dashboards, Looks, Explores, reports, and extensions into web applications, with support for signed SSO and cookieless authentication.

- **Human URL:** [https://docs.cloud.google.com/looker/docs/embed-sdk-intro](https://docs.cloud.google.com/looker/docs/embed-sdk-intro)
- **Base URL:** `https://your-instance.looker.com:19999/api/4.0`

#### Tags

- Dashboards
- Embedding
- JavaScript SDK
- SSO

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/embed-sdk-intro)
- [GitHub Repository](https://github.com/looker-open-source/embed-sdk)
- [API Reference](https://looker-open-source.github.io/embed-sdk/)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Extension Framework API

The Looker Extension Framework provides APIs and SDKs for building custom extensions that run inside the Looker UI, with access to the Looker API, Looker components library, and the Embed SDK.

- **Human URL:** [https://developers.looker.com/extensions/overview/](https://developers.looker.com/extensions/overview/)
- **Base URL:** `https://your-instance.looker.com:19999/api/4.0`

#### Tags

- Extensions
- JavaScript
- React
- UI Components

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/intro-to-extension-framework)
- [Code Examples](https://docs.cloud.google.com/looker/docs/extension-framework-react-and-js-code-examples)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker (Google Cloud core) API

The Looker (Google Cloud core) REST API provides management capabilities for Looker instances running on Google Cloud, including instance lifecycle management, backups, and operations.

- **Human URL:** [https://cloud.google.com/looker/docs/reference/rest](https://cloud.google.com/looker/docs/reference/rest)
- **Base URL:** `https://looker.googleapis.com/v1`

#### Tags

- Backups
- Google Cloud
- Infrastructure
- Instance Management

#### Properties

- [Documentation](https://cloud.google.com/looker/docs/reference/rest)
- [Console](https://console.cloud.google.com/apis/library/looker.googleapis.com)
- [Postman Collection](collections/looker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/looker)
- [Developer Portal](https://developers.looker.com/)
- [GitHub Organization](https://github.com/looker-open-source)
- [Support](https://cloud.google.com/looker/docs/support)
- [Status Page](https://status.looker.com/)
- [Privacy Policy](https://looker.com/privacy)
- [Terms of Service](https://looker.com/terms)
- [SDK](https://docs.cloud.google.com/looker/docs/api-sdk)
- [Changelog](https://github.com/looker-open-source/sdk-codegen/blob/main/CHANGELOG.md)
- [Release Notes](https://docs.cloud.google.com/looker/docs/release-notes)
- [Pricing](https://cloud.google.com/looker/pricing)
- [Getting Started](https://docs.cloud.google.com/looker/docs/api-getting-started)
- [Authentication](https://docs.cloud.google.com/looker/docs/api-auth)
- [Tutorials](https://developers.looker.com/api/tutorials/interactive-api-docs-whats-next/)
- [JSON Schema](json-schema/looker-dashboard-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/looker-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
