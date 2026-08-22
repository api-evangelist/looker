# Looker (looker)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
