# Nx

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

Nx is a smart, fast, extensible monorepo build system and integrated CI platform created and maintained by Nrwl. The Nx CLI (Rust core, TypeScript plugins) provides task orchestration, dependency-graph analysis, affected-only execution, local caching, and code generation across Angular, React, Next.js, Node, Vue, Vite, Webpack, Jest, Cypress, Playwright, Storybook, Gradle, .NET, Go, and dozens of other ecosystems. Nx Cloud extends the CLI with remote caching, distributed task execution via Nx Agents, atomized E2E test splitting, and AI-powered Self-Healing CI that detects, fixes, and retries failing pipelines. The Nx Console IDE extension and Nx MCP server make the workspace graph and generators consumable by editors and AI agents including Claude Code, Cursor, and Copilot. MIT licensed, with 28k+ GitHub stars, millions of monthly npm downloads, and adoption by 30% of the Fortune 500.

**Areas:** Monorepo · Builds · Build Systems · TaskRunner · Dependency-Graph · Cache · Remote Cache · CI · DistributedExecution · Developer Tools · Developer Experience · IDE

## Nx on APIs.io

Everything profiled for Nx is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nx-dev/](https://apis.io/providers/nx-dev/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Nx CLI](https://apis.io/apis/nx-dev/nx-cli/) — The Nx command-line interface — the primary surface for running, caching, and orchestrating tasks across a monorepo. Built in Rust for performance and…
- [Nx Plugin System](https://apis.io/apis/nx-dev/nx-plugin-system/) — The Nx plugin system lets you package generators, executors, and inferred-task plugins for any tech stack. Official plugins cover Angular, React, Next.js,…
- [Nx Graph and Affected](https://apis.io/apis/nx-dev/nx-graph-and-affected/) — Nx builds a project graph and a task graph from your workspace, then uses them to run only the tasks affected by a given change set. `nx graph` opens an…
- [Nx Cache](https://apis.io/apis/nx-dev/nx-cache/) — Nx caches task outputs locally based on a hash of inputs (source files, env vars, configuration, and dependencies). Cached tasks are replayed instantly…
- [Nx Release](https://apis.io/apis/nx-dev/nx-release/) — `nx release` is Nx's first-class versioning, changelog generation, and publishing pipeline for monorepos. Supports independent and fixed versioning,…
- [Nx Console](https://apis.io/apis/nx-dev/nx-console/) — Nx Console is the official IDE extension for Nx and Lerna, available for Visual Studio Code, Cursor, and JetBrains IDEs (WebStorm, IntelliJ, RustRover).…
- [Nx Cloud Remote Cache](https://apis.io/apis/nx-dev/nx-cloud-remote-cache/) — Nx Cloud Remote Cache shares cached task outputs across machines and CI agents. Cache hits skip redundant builds and tests in CI and on teammates' machines.…
- [Nx Agents (Distributed Task Execution)](https://apis.io/apis/nx-dev/nx-agents/) — Nx Agents distribute task execution across managed CI machines with automatic load-balancing, flaky-task retries, and dynamic agent allocation sized to the…
- [Nx Self-Healing CI](https://apis.io/apis/nx-dev/nx-self-healing-ci/) — AI-powered CI agent that watches Nx Cloud pipelines, detects failing tasks, analyzes root causes, proposes fixes as PR suggestions, and re-runs flaky tests…
- [Nx MCP Server](https://apis.io/apis/nx-dev/nx-mcp/) — The Nx MCP server exposes the Nx project graph, task graph, generator catalog, and documentation to MCP-compatible AI agents (Claude Code, Cursor, Copilot,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Nx Dev Domain Security](https://apis.io/security/nx-dev/nx-dev-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nx Dev Plans Pricing](https://apis.io/plans/nx-dev/nx-dev-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nx.dev/)
- [Documentation](https://nx.dev/docs)
- [Getting started](https://nx.dev/getting-started/intro)
- [Pricing](https://nx.dev/pricing)
- [Changelog](https://nx.dev/changelog)
- [Blog](https://nx.dev/blog)
- [GitHub](https://github.com/nrwl)
- [Status](https://status.nx.app)

## API Evangelist rating

**Kin Score 29.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 6.5 |
| Contract governance | 0.0 |
| Operational transparency | 36.8 |
| Developer ergonomics | 38.1 |
| Access clarity | 55.3 |

**Agent readiness 1.3** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nx-dev/](https://apis.io/providers/nx-dev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nx: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nx-dev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
