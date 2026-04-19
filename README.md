# Looker (looker)
Looker is a business intelligence and data analytics platform that enables organizations to explore, analyze, and share real-time business analytics.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/looker/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, BI Platform, Business Intelligence, Data Analytics, Data Visualization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Looker API
The Looker API provides programmatic access to Looker functionality including running queries, managing users, creating dashboards, and administering the platform.

**Human URL:** [https://developers.looker.com/api/explorer/4.0](https://developers.looker.com/api/explorer/4.0)

#### Tags:

 - Analytics, Dashboards, Queries, REST API

#### Properties

- [Documentation](https://developers.looker.com/api/getting-started)
- [OpenAPI](openapi/looker-api-openapi.yml)

### LookML API
API for programmatically managing LookML projects, models, and views.

**Human URL:** [https://developers.looker.com/api/explorer/4.0/methods/Project](https://developers.looker.com/api/explorer/4.0/methods/Project)

#### Tags:

 - Data Modeling, LookML, Projects

#### Properties

- [Documentation](https://developers.looker.com/api/explorer/4.0/methods/Project)

### Looker Action API
The Looker Action API enables developers to define custom actions, or destinations, to which Looker can send query results, dashboard results, or user interactions via a webhook-like API.

**Human URL:** [https://docs.cloud.google.com/looker/docs/actions-overview](https://docs.cloud.google.com/looker/docs/actions-overview)

#### Tags:

 - Actions, Data Delivery, Integrations, Webhooks

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/actions-overview)
- [GitHubRepository](https://github.com/looker-open-source/actions)

### Looker Embed SDK
The Looker Embed SDK is a JavaScript library for embedding Looker content into web applications.

**Human URL:** [https://docs.cloud.google.com/looker/docs/embed-sdk-intro](https://docs.cloud.google.com/looker/docs/embed-sdk-intro)

#### Tags:

 - Dashboards, Embedding, JavaScript SDK, SSO

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/embed-sdk-intro)
- [GitHubRepository](https://github.com/looker-open-source/embed-sdk)

### Looker Extension Framework API
The Looker Extension Framework provides APIs and SDKs for building custom extensions that run inside the Looker UI.

**Human URL:** [https://developers.looker.com/extensions/overview/](https://developers.looker.com/extensions/overview/)

#### Tags:

 - Extensions, JavaScript, React, UI Components

#### Properties

- [Documentation](https://docs.cloud.google.com/looker/docs/intro-to-extension-framework)
- [CodeExamples](https://docs.cloud.google.com/looker/docs/extension-framework-react-and-js-code-examples)

### Looker (Google Cloud core) API
The Looker (Google Cloud core) REST API provides management capabilities for Looker instances running on Google Cloud.

**Human URL:** [https://cloud.google.com/looker/docs/reference/rest](https://cloud.google.com/looker/docs/reference/rest)

#### Tags:

 - Backups, Google Cloud, Infrastructure, Instance Management

#### Properties

- [Documentation](https://cloud.google.com/looker/docs/reference/rest)

## Common Properties

- [DeveloperPortal](https://developers.looker.com/)
- [GitHubOrganization](https://github.com/looker-open-source)
- [Support](https://cloud.google.com/looker/docs/support)
- [StatusPage](https://status.looker.com/)
- [PrivacyPolicy](https://looker.com/privacy)
- [TermsOfService](https://looker.com/terms)

## Features

| Name | Description |
|------|-------------|
| Self-Service Analytics | Enable business users to explore data, build visualizations, and create dashboards without SQL knowledge using LookML models. |
| Data Modeling with LookML | Define reusable data models in LookML that provide a semantic layer between databases and end-user analytics. |
| Embedded Analytics | Embed interactive dashboards, reports, and data explorations directly into web applications using SSO and cookieless authentication. |
| Scheduled Reports | Schedule and deliver reports and dashboards via email, Slack, S3, or custom action destinations. |
| Custom Actions | Build webhook-based actions to send query results to any external destination or trigger workflows. |
| API-Driven Administration | Programmatically manage users, roles, dashboards, queries, and platform settings through the Looker API. |

## Use Cases

| Name | Description |
|------|-------------|
| Executive Dashboards | Build real-time executive dashboards aggregating KPIs from multiple data sources for leadership visibility. |
| Customer-Facing Analytics | Embed analytics into SaaS products to provide customers with self-service reporting and data exploration. |
| Data Governance Reporting | Monitor data quality, usage patterns, and access controls across the organization through audit reports. |
| Marketing Performance Analytics | Analyze campaign performance, attribution, and ROI across marketing channels with unified data models. |
| Operational Monitoring | Track operational metrics and KPIs in real time with automated alerting and scheduled report delivery. |

## Integrations

| Name | Description |
|------|-------------|
| Google BigQuery | Native optimized connector for querying and analyzing data in Google BigQuery data warehouse. |
| Snowflake | High-performance connector for Snowflake cloud data warehouse with push-down query optimization. |
| Amazon Redshift | Native connector for querying and visualizing data in Amazon Redshift data warehouse. |
| Slack | Deliver scheduled reports and dashboard snapshots to Slack channels with interactive query capabilities. |
| Google Sheets | Export query results and dashboard data directly to Google Sheets for collaborative analysis. |
| Salesforce | Connect to Salesforce data for CRM analytics and combine with other data sources for unified views. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Looker API](openapi/looker-api-openapi.yml)

### JSON-LD

- [Looker Context](json-ld/looker-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Looker API](capabilities/shared/looker-api.yaml) -- 29 operations for business intelligence management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Analytics and Reporting](capabilities/analytics-and-reporting.yaml) | Looker API | 21 | Data Analyst |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
