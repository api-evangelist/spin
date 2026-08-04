# Spin

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

Spin is an open source framework by Fermyon for building and running fast, secure, and composable cloud microservices with WebAssembly. Spin provides a developer experience for creating event-driven serverless applications that compile to WebAssembly and run on any platform that supports the Spin runtime including local dev environments, Kubernetes (via SpinKube), and Fermyon Cloud.

## APIs

### Spin HTTP Trigger API

Handles incoming HTTP requests routed to Spin components. Supported via the Spin SDK in Rust, Go, Python, JavaScript, and other WASI-compatible languages.

- **Documentation:** https://spinframework.dev/v3/http-trigger

### Spin Key-Value Store API

Provides Spin components with access to persistent key-value storage. Backed by in-memory, Redis, or cloud-managed stores depending on deployment target.

- **Documentation:** https://spinframework.dev/v3/kv-store-api

### Spin SQLite API

Provides Spin components with access to an embedded relational database for structured data persistence.

- **Documentation:** https://spinframework.dev/v3/sqlite-api

### Spin Serverless AI API

Enables Spin components to run AI inference using built-in language model support (Llama 2, CodeLlama) via the Spin SDK.

- **Documentation:** https://spinframework.dev/v3/serverless-ai-tutorial

### Spin Variables API

Provides runtime access to application configuration variables defined in spin.toml, with support for secrets and configurable providers.

- **Documentation:** https://spinframework.dev/v3/variables

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spin Rules | [rules/spin-rules.yml](rules/spin-rules.yml) |

## JSON Schema

| Schema | File |
|--------|------|
| Spin Application Manifest | [json-schema/spin-manifest.json](json-schema/spin-manifest.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| Spin Manifest | [json-structure/spin-manifest-structure.json](json-structure/spin-manifest-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| Spin Context | [json-ld/spin-context.jsonld](json-ld/spin-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Spin Manifest | [examples/spin-manifest-example.json](examples/spin-manifest-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spin Vocabulary | [vocabulary/spin-vocabulary.yml](vocabulary/spin-vocabulary.yml) |

## Links

- **Website:** https://spinframework.dev/
- **Documentation:** https://spinframework.dev/v3/
- **Quickstart:** https://spinframework.dev/v3/quickstart
- **GitHub (Fermyon Org):** https://github.com/fermyon
- **GitHub (Spin Repo):** https://github.com/fermyon/spin
- **Releases:** https://github.com/fermyon/spin/releases
- **Roadmap:** https://github.com/fermyon/spin/blob/main/ROADMAP.md
- **Fermyon Cloud:** https://www.fermyon.com/
- **Discord:** https://discord.gg/AAFNfS7NGf
- **Blog:** https://www.fermyon.com/blog
