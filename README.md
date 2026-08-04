# Requesty (requesty)

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

Requesty is an LLM routing and gateway platform that exposes a single OpenAI-compatible API across 300+ models from providers like OpenAI, Anthropic, DeepSeek, and Together AI. The Requesty Router adds intelligent routing, automatic fallbacks, response caching, spend controls, and per-request cost observability on top of unified inference.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/requesty/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/requesty/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Routing
- Gateway
- Observability

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Requesty Chat Completions API

OpenAI-compatible chat completions routed across 300+ models from OpenAI, Anthropic, DeepSeek, Together AI, and more, with streaming, tool use, web search, automatic fallbacks, and response caching.

- **Human URL:** [https://docs.requesty.ai/api-reference/endpoint/chat-completions-create](https://docs.requesty.ai/api-reference/endpoint/chat-completions-create)
- **Base URL:** `https://router.requesty.ai/v1`

#### Tags

- Chat
- Completions
- Routing
- LLM

#### Properties

- [Documentation](https://docs.requesty.ai)
- [API Reference](https://docs.requesty.ai/api-reference/endpoint/chat-completions-create)
- [OpenAPI](openapi/requesty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/requesty-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/requesty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/requesty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Requesty Models API

Lists the 300+ models routable through the Requesty gateway with their identifiers, provider, context length, and per-token pricing.

- **Human URL:** [https://docs.requesty.ai](https://docs.requesty.ai)
- **Base URL:** `https://router.requesty.ai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.requesty.ai)
- [API Reference](https://www.requesty.ai/models)
- [OpenAPI](openapi/requesty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/requesty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/requesty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Requesty Usage & Analytics API

Retrieves per-key and organization-level usage statistics, request cost, and spend reporting for observability and FinOps across the gateway.

- **Human URL:** [https://docs.requesty.ai](https://docs.requesty.ai)
- **Base URL:** `https://router.requesty.ai/v1`

#### Tags

- Usage
- Analytics
- Observability
- FinOps

#### Properties

- [Documentation](https://docs.requesty.ai)
- [OpenAPI](openapi/requesty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/requesty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/requesty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Requesty API Keys API

Programmatically create, list, inspect, and delete API keys and manage their spending limits, labels, and expiration for governing gateway access.

- **Human URL:** [https://app.requesty.ai/api-keys](https://app.requesty.ai/api-keys)
- **Base URL:** `https://router.requesty.ai/v1`

#### Tags

- API Keys
- Management
- Governance

#### Properties

- [Documentation](https://docs.requesty.ai)
- [OpenAPI](openapi/requesty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/requesty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/requesty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/requestyai)
- [LinkedIn](https://www.linkedin.com/company/requesty)
- [Website](https://www.requesty.ai)
- [Documentation](https://docs.requesty.ai)
- [Plans](plans/requesty-plans-pricing.yml)
- [Rate Limits](rate-limits/requesty-rate-limits.yml)
- [Fin Ops](finops/requesty-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
