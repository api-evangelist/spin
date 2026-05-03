# Spin

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
