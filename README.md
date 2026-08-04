# Nx (nx-dev)

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

Nx is a smart, fast, extensible monorepo build system and integrated CI platform created and maintained by Nrwl. The Nx CLI (Rust core, TypeScript plugins) provides task orchestration, dependency-graph analysis, affected-only execution, local caching, and code generation across Angular, React, Next.js, Node, Vue, Vite, Webpack, Jest, Cypress, Playwright, Storybook, Gradle, .NET, Go, and dozens of other ecosystems. Nx Cloud extends the CLI with remote caching, distributed task execution via Nx Agents, atomized E2E test splitting, and AI-powered Self-Healing CI. The Nx Console IDE extension and Nx MCP server make the workspace graph and generators consumable by editors and AI agents including Claude Code, Cursor, and Copilot. MIT licensed.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/nx-dev/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

 - Monorepo, Build, BuildSystem, TaskRunner, DependencyGraph, Cache, RemoteCache, CI, DistributedExecution, DeveloperTools, DeveloperExperience, IDE, AI, Agents, MCP, ModelContextProtocol, TypeScript, JavaScript, Rust, OpenSource

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Project At a Glance

| Field | Value |
|---|---|
| Project | Nx |
| Maintainer | Nrwl |
| Repository | [github.com/nrwl/nx](https://github.com/nrwl/nx) |
| License | MIT |
| Primary Languages | TypeScript, Rust |
| Latest Version | 22.7 (released 2026-04-24) |
| CLI Command | `nx` (`npx nx`) |
| npm Package | [`nx`](https://www.npmjs.com/package/nx) |
| Scaffolder | [`create-nx-workspace`](https://www.npmjs.com/package/create-nx-workspace) |
| Hosted Offering | Nx Cloud (Hobby free, Team pay-as-you-go, Enterprise) |
| GitHub Stars | 28.8k |

## APIs

### Nx CLI
The Nx command-line interface — the primary surface for running, caching, and orchestrating tasks across a monorepo. Built in Rust for performance and extensible via TypeScript plugins. Supports `nx run`, `nx affected`, `nx graph`, `nx generate`, `nx migrate`, `nx release`, `nx sync`, and `nx init` to incrementally adopt Nx in existing npm, pnpm, or yarn workspaces.

**Human URL:** [https://nx.dev/reference/nx-commands](https://nx.dev/reference/nx-commands)

- [Documentation](https://nx.dev/reference/nx-commands)
- [Getting Started](https://nx.dev/getting-started/intro)
- [Package — nx on npm](https://www.npmjs.com/package/nx)

### Nx Plugin System
Package generators, executors, and inferred-task plugins for any tech stack. Official plugins cover Angular, React, Next.js, Remix, Nuxt, Vue, Node, Express, Nest, Expo, React Native, Detox, Vite, Webpack, Rspack, Esbuild, Rollup, Jest, Vitest, Cypress, Playwright, Storybook, ESLint, Gradle, and .NET.

**Human URL:** [https://nx.dev/extending-nx/intro/getting-started](https://nx.dev/extending-nx/intro/getting-started)

- [Documentation](https://nx.dev/extending-nx/intro/getting-started)
- [Plugin Registry](https://nx.dev/plugin-registry)
- [Inferred Tasks](https://nx.dev/concepts/inferred-tasks)

### Nx Graph and Affected
Nx builds a project graph and a task graph from your workspace, then uses them to run only the tasks affected by a given change set. `nx graph` opens an interactive visualization; `nx affected -t build` runs only what is needed.

**Human URL:** [https://nx.dev/features/explore-graph](https://nx.dev/features/explore-graph)

- [Documentation — Explore the Graph](https://nx.dev/features/explore-graph)
- [Documentation — Run Tasks](https://nx.dev/features/run-tasks)
- [Documentation — Affected in CI](https://nx.dev/ci/features/affected)

### Nx Cache
Nx caches task outputs locally based on a hash of inputs (sources, env vars, configuration, dependencies). Nx 22.7 introduces worktree-aware caching across git worktrees and faster cache replay (1110 tasks restored in ~1.16s).

**Human URL:** [https://nx.dev/features/cache-task-results](https://nx.dev/features/cache-task-results)

- [Documentation](https://nx.dev/features/cache-task-results)
- [How Caching Works](https://nx.dev/concepts/how-caching-works)

### Nx Release
`nx release` is Nx's first-class versioning, changelog generation, and publishing pipeline for monorepos. Supports independent and fixed versioning, conventional commits, semantic versioning, GitHub Releases, and npm publishing.

**Human URL:** [https://nx.dev/features/manage-releases](https://nx.dev/features/manage-releases)

- [Documentation](https://nx.dev/features/manage-releases)
- [Recipes — nx release](https://nx.dev/recipes/nx-release)

### Nx Console
Nx Console is the official IDE extension for Nx and Lerna, available for Visual Studio Code, Cursor, and JetBrains IDEs (WebStorm, IntelliJ, RustRover). Provides project detail views, generator UI, workspace and task visualization, Nx Cloud CI notifications, and AI chat enrichment.

**Human URL:** [https://nx.dev/getting-started/editor-setup](https://nx.dev/getting-started/editor-setup)

- [Documentation](https://nx.dev/getting-started/editor-setup)
- [Source — nrwl/nx-console](https://github.com/nrwl/nx-console)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
- [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/21060-nx-console)

### Nx Cloud Remote Cache
Nx Cloud Remote Cache shares cached task outputs across machines and CI agents. Cache hits skip redundant builds and tests in CI and on teammates' machines. Authenticated via `NX_CLOUD_ACCESS_TOKEN`. Hobby tier includes 50,000 monthly credits free.

**Human URL:** [https://nx.dev/ci/features/remote-cache](https://nx.dev/ci/features/remote-cache)

- [Documentation](https://nx.dev/ci/features/remote-cache)
- [Access Tokens](https://nx.dev/ci/recipes/security/access-tokens)

### Nx Agents (Distributed Task Execution)
Nx Agents distribute task execution across managed CI machines with automatic load balancing, flaky-task retries, and dynamic agent allocation sized to the affected task graph. Includes Atomized E2E test splitting that breaks Cypress and Playwright suites into file-level units.

**Human URL:** [https://nx.dev/ci/features/distribute-task-execution](https://nx.dev/ci/features/distribute-task-execution)

- [Documentation](https://nx.dev/ci/features/distribute-task-execution)
- [Dynamic Agents](https://nx.dev/ci/features/dynamic-agents)

### Nx Self-Healing CI
AI-powered CI agent that watches Nx Cloud pipelines, detects failing tasks, analyzes root causes, proposes fixes as PR suggestions, and re-runs flaky tests automatically. Supports GitHub, GitLab, Bitbucket, and Azure DevOps.

**Human URL:** [https://nx.dev/ci/features/self-healing-ci](https://nx.dev/ci/features/self-healing-ci)

- [Documentation](https://nx.dev/ci/features/self-healing-ci)

### Nx MCP Server
The Nx MCP server exposes the Nx project graph, task graph, generator catalog, and documentation to MCP-compatible AI agents (Claude Code, Cursor, Copilot, Windsurf). Ships inside the nx-console extension and as a standalone command.

**Human URL:** [https://nx.dev/features/enhance-AI](https://nx.dev/features/enhance-AI)

- [Documentation — Enhance AI](https://nx.dev/features/enhance-AI)
- [Source — nx-console](https://github.com/nrwl/nx-console)

## Common Resources

- [Portal — Nx](https://nx.dev)
- [Documentation](https://nx.dev/docs)
- [Getting Started](https://nx.dev/getting-started/intro)
- [Installation](https://nx.dev/getting-started/installation)
- [Tutorials](https://nx.dev/getting-started/tutorials)
- [Concepts](https://nx.dev/concepts)
- [nx.json Reference](https://nx.dev/reference/nx-json)
- [Project Configuration Reference](https://nx.dev/reference/project-configuration)
- [CLI Reference](https://nx.dev/reference/nx-commands)
- [Plugin Registry](https://nx.dev/plugin-registry)
- [Community](https://nx.dev/community)
- [Blog](https://nx.dev/blog)
- [Changelog](https://nx.dev/changelog)
- [Nx Cloud Pricing](https://nx.dev/pricing)
- [Nx Cloud Sign Up](https://cloud.nx.app/get-started)
- [Status — Nx Cloud](https://status.nx.app)
- [GitHub — Nrwl Organization](https://github.com/nrwl)
- [GitHub — nrwl/nx](https://github.com/nrwl/nx)
- [GitHub — nrwl/nx-console](https://github.com/nrwl/nx-console)
- [GitHub — nrwl/nx-examples](https://github.com/nrwl/nx-examples)
- [GitHub — nrwl/nx-recipes](https://github.com/nrwl/nx-recipes)
- [GitHub — nrwl/nx-labs](https://github.com/nrwl/nx-labs)
- [Helm Charts — nx-cloud-helm](https://github.com/nrwl/nx-cloud-helm)
- [npm — nx](https://www.npmjs.com/package/nx)
- [npm — create-nx-workspace](https://www.npmjs.com/package/create-nx-workspace)
- [npm — @nx scope](https://www.npmjs.com/org/nx)
- [Editor Setup](https://nx.dev/getting-started/editor-setup)
- [Nx Console for VS Code](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
- [Nx Console for JetBrains](https://plugins.jetbrains.com/plugin/21060-nx-console)
- [Discord](https://discord.gg/nx)
- [X — @nxdevtools](https://x.com/nxdevtools)
- [YouTube — @nxdevtools](https://www.youtube.com/@nxdevtools)
- [Nrwl Portal](https://nrwl.io)
- [Nrwl Services](https://nrwl.io/services)
- [Monorepo World Conference](https://nx.dev/conf)

## Features

- Nx CLI — Rust-powered task runner with `nx run`, `nx affected`, `nx graph`, `nx generate`, `nx migrate`, `nx release`, `nx sync`, and `nx init`
- Polyglot plugin system — first-party plugins for Angular, React, Next.js, Remix, Nuxt, Vue, Node, Express, Nest, Expo, React Native, Detox, Vite, Webpack, Rspack, Esbuild, Rollup, Jest, Vitest, Cypress, Playwright, Storybook, ESLint, Web Components, Gradle, and .NET
- Inferred tasks — auto-discovers `package.json` scripts and tasks from Vite, Webpack, Jest, Vitest, ESLint, Gradle, Maven, .NET, Go, and more
- Project graph and task graph with `nx graph` interactive visualization
- Affected commands (`nx affected -t build|test|lint`) run only what changed since a base ref
- Local task caching with input-hash invalidation; worktree-aware in Nx 22.7
- Task sandboxing (Nx 22.6) traces undeclared file I/O similar to Bazel
- `nx release` for versioning, changelog generation, and publishing
- `nx migrate` automates version upgrades with codemods for major Nx and plugin releases
- `nx sync` synchronizes generated files (TypeScript references, package.json deps) across the workspace
- Nx Console IDE extension for VS Code, Cursor, and JetBrains IDEs
- Nx MCP server — exposes workspace graph, generators, and docs to MCP-compatible AI agents
- AI-enhanced chat in VS Code/Cursor through Nx Console workspace context injection
- Nx Cloud Remote Cache shares cache hits across teammates and CI
- Nx Agents distribute tasks across managed CI machines with dynamic agent allocation
- Atomized E2E test splitting for Cypress and Playwright
- Self-Healing CI — AI agent detects failed tasks, proposes fixes as PR suggestions, retries flaky tests
- CI provider integrations: GitHub, GitLab, Bitbucket, Azure DevOps, CircleCI, Jenkins
- Nx Cloud self-hosted deployment via Helm charts (Enterprise)
- `create-nx-workspace` scaffolds new workspaces; `nx init` adopts Nx incrementally
- Conformance rules and circular-dependency detection (Enterprise)
- Workspace analytics with CI duration percentiles

## Pricing

| Tier | Cost | Includes |
|---|---|---|
| Hobby | Free | 50,000 monthly credits, 5 contributors, 10 concurrent CI connections, community support |
| Team | Pay-as-you-go | Additional contributors at $19 each, extra credits at $5.50 per 10,000, concurrent connections at $2.25 each, email support |
| Enterprise | Custom | Self-healing CI, conformance rules, circular-dependency detection, cross-repository visibility, dedicated support with SLAs, self-hosted deployment, volume discounts |

## Maintainers

| FN | Url | Email | X |
|---|---|---|---|
| Kin Lane | [https://apievangelist.com](https://apievangelist.com) | info@apievangelist.com | apievangelist |
