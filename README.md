# Wolfram|Alpha (wolframalpha)

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

Wolfram|Alpha is a computational knowledge engine that provides answers to natural language queries using a vast curated knowledge base and computational algorithms. The Wolfram|Alpha API suite gives developers programmatic access to computational intelligence for web, mobile, voice, and AI agent applications. APIs range from the full-featured Full Results API to specialized LLM, Short Answers, Simple, Spoken Results, Conversational, Fast Query Recognizer, Summary Boxes, and Instant Calculators APIs.

**APIs.json:** [https://products.wolframalpha.com/api/](https://products.wolframalpha.com/api/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- Computational Knowledge
- Machine Learning
- Natural Language Processing
- Public APIs
- Search

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Wolfram|Alpha LLM API

The LLM API delivers computational knowledge results optimized for consumption by large language models and AI chat applications. Built on the same engine as the full API, it returns structured text with query interpretation, computed results, and relevant data formatted for LLM processing. Authentication uses an AppID query parameter or Bearer token.

- **Human URL:** [https://products.wolframalpha.com/llm-api/documentation](https://products.wolframalpha.com/llm-api/documentation)
- **Base URL:** `https://www.wolframalpha.com/api/v1/`

#### Tags

- AI
- Computational Knowledge
- LLM

#### Properties

- [Documentation](https://products.wolframalpha.com/llm-api/documentation)
- [OpenAPI](openapi/wolframalpha-llm-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-llm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-llm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wolframalpha-llm-api-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wolframalpha-llm-api-response-structure.json)
- [JSON-LD](json-ld/wolframalpha-llm-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/wolframalpha-queryllmapi-example.json)
- [Example](examples/wolframalpha-llm-api-response-example.json)

### Wolfram|Alpha Full Results API

The Full Results API provides full programmatic access to all Wolfram|Alpha capabilities, including disambiguation, drilldown, asynchronous delivery, and results in multiple formats (XML, JSON). It supports customizable pod selection, location-aware queries, and display formatting.

- **Human URL:** [https://products.wolframalpha.com/api/documentation](https://products.wolframalpha.com/api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v2/`

#### Tags

- Computation
- Full Results
- Natural Language Processing

#### Properties

- [Documentation](https://products.wolframalpha.com/api/documentation)
- [OpenAPI](openapi/wolframalpha-full-results-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-full-results-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-full-results-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wolframalpha-full-results-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wolframalpha-pod-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wolframalpha-subpod-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wolframalpha-full-results-response-structure.json)
- [JSON Structure](json-structure/wolframalpha-pod-structure.json)
- [JSON Structure](json-structure/wolframalpha-subpod-structure.json)
- [JSON-LD](json-ld/wolframalpha-full-results-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/wolframalpha-full-results-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/wolframalpha-queryfullresults-example.json)
- [Example](examples/wolframalpha-full-results-response-example.json)
- [Example](examples/wolframalpha-pod-example.json)
- [Example](examples/wolframalpha-subpod-example.json)

### Wolfram|Alpha Short Answers API

The Short Answers API returns a single concise plain-text result from Wolfram|Alpha, ideal for chatbots, mobile apps, and constrained displays. Returns HTTP 501 when no brief answer is available.

- **Human URL:** [https://products.wolframalpha.com/short-answers-api/documentation](https://products.wolframalpha.com/short-answers-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Natural Language Processing
- Short Answers
- Text

#### Properties

- [Documentation](https://products.wolframalpha.com/short-answers-api/documentation)
- [OpenAPI](openapi/wolframalpha-short-answers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-short-answers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-short-answers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/wolframalpha-queryshortanswer-example.json)

### Wolfram|Alpha Simple API

The Simple API returns complete Wolfram|Alpha results as a rendered image, requiring minimal coding. Suitable for embedding computational results visually in web applications without handling complex XML/JSON responses.

- **Human URL:** [https://products.wolframalpha.com/simple-api/documentation](https://products.wolframalpha.com/simple-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Images
- Natural Language Processing
- Visual Results

#### Properties

- [Documentation](https://products.wolframalpha.com/simple-api/documentation)
- [OpenAPI](openapi/wolframalpha-simple-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-simple-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-simple-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/wolframalpha-querysimpleapi-example.json)

### Wolfram|Alpha Spoken Results API

The Spoken Results API returns answers optimized for audio delivery, suitable for voice assistants, automotive systems, and accessibility features. Results are plain text formatted to be read aloud naturally.

- **Human URL:** [https://products.wolframalpha.com/spoken-results-api/documentation](https://products.wolframalpha.com/spoken-results-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Audio
- Natural Language Processing
- Voice

#### Properties

- [Documentation](https://products.wolframalpha.com/spoken-results-api/documentation)
- [OpenAPI](openapi/wolframalpha-spoken-results-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-spoken-results-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-spoken-results-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/wolframalpha-queryspokenresults-example.json)

### Wolfram|Alpha Fast Query Recognizer API

The Fast Query Recognizer API classifies queries in under 10 milliseconds to determine whether Wolfram|Alpha is likely to provide a useful response. Useful for routing queries efficiently before invoking the full computational engine.

- **Human URL:** [https://products.wolframalpha.com/query-recognizer/documentation](https://products.wolframalpha.com/query-recognizer/documentation)
- **Base URL:** `https://www.wolframalpha.com/queryrecognizer/`

#### Tags

- Classification
- Natural Language Processing
- Routing

#### Properties

- [Documentation](https://products.wolframalpha.com/query-recognizer/documentation)
- [OpenAPI](openapi/wolframalpha-fast-query-recognizer-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolframalpha-fast-query-recognizer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolframalpha-fast-query-recognizer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wolframalpha-query-recognizer-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wolframalpha-query-recognizer-response-structure.json)
- [Example](examples/wolframalpha-recognizequery-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.wolframalpha.com)
- [Developer Portal](https://developer.wolframalpha.com/)
- [Portal](https://products.wolframalpha.com/api/)
- [Sign Up](https://developer.wolframalpha.com/)
- [Authentication](https://products.wolframalpha.com/api/documentation)
- [Pricing](https://products.wolframalpha.com/api/)
- [Plans](plans/wolframalpha-plans-pricing.yml)
- [Rate Limits](rate-limits/wolframalpha-rate-limits.yml)
- [Fin Ops](finops/wolframalpha-finops.yml)
- [Terms of Service](https://products.wolframalpha.com/api/documentation)
- [GitHub Organization](https://github.com/WolframResearch)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [LinkedIn](https://www.linkedin.com/company/wolfram-alpha-llc)
- [SDK](https://github.com/WolframResearch/WolframClientForPython)
- [SDK](https://pypi.org/project/wolframclient/)
- [SDK](https://github.com/WolframResearch/WolframWebEngineForPython)
- [SDK](https://github.com/WolframResearch/wolfram-library-link-rs)
- [SDK](https://github.com/WolframResearch/wstp-rs)
- [SDK](https://github.com/WolframResearch/wolfram-expr-rs)
- [I D E Support](https://github.com/WolframResearch/vscode-wolfram)
- [I D E Support](https://github.com/WolframResearch/Sublime-WolframLanguage)
- [Tools](https://github.com/WolframResearch/AgentTools)
- [Tools](https://github.com/WolframResearch/AgentTools/blob/main/docs/docker.md)
- [Tools](https://github.com/WolframResearch/skills)
- [Tools](https://github.com/WolframResearch/Chatbook)
- [Tools](https://github.com/WolframResearch/AWSLambda-WolframLanguage)
- [Tools](https://github.com/WolframResearch/WolframLanguageForJupyter)
- [Tools](https://github.com/WolframResearch/LSPServer)
- [Spectral Rules](rules/wolframalpha-rules.yml)
- [Vocabulary](vocabulary/wolframalpha-vocabulary.yml)
- [JSON-LD](json-ld/wolframalpha-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
