# Requesty (requesty)

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
