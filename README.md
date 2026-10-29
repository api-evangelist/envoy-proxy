# Envoy Proxy

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

Envoy Proxy is an open-source edge and service proxy that is designed for cloud-native applications. It acts as a gateway for all incoming and outgoing traffic within a microservices architecture, providing functionalities such as load balancing, service discovery, encryption, authentication, and observability. Envoy Proxy is known for its high performance and low latency, making it a popular choice for companies seeking to optimize their network traffic and improve overall system efficiency.

**Areas:** Gateways · Proxies

## Envoy Proxy on APIs.io

Everything profiled for Envoy Proxy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/envoy-proxy/](https://apis.io/providers/envoy-proxy/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [Envoy Proxy Rate Limit Service API](https://apis.io/apis/envoy-proxy/rate-limit-service-api/) — The Envoy Rate Limit Service (RLS) is a gRPC-based API that allows Envoy to delegate rate limiting decisions to an external service. When a request matches…
- [Envoy Proxy Health Discovery Service API](https://apis.io/apis/envoy-proxy/health-discovery-service-api/) — The Envoy Health Discovery Service (HDS) is a gRPC-based API that enables a management server to instruct Envoy to perform health checks on behalf of the…
- [Envoy Proxy gRPC Access Log Service API](https://apis.io/apis/envoy-proxy/access-log-service-api/) — The Envoy gRPC Access Log Service (ALS) API provides a streaming gRPC interface for receiving access log entries from Envoy instances in real time. It…
- [Envoy Proxy External Processing API](https://apis.io/apis/envoy-proxy/external-processing-api/) — The Envoy External Processing API is a gRPC-based service that enables an external server to inspect and modify HTTP requests and responses as they pass…
- [Envoy Proxy External Authorization API](https://apis.io/apis/envoy-proxy/external-authorization-api/) — The Envoy External Authorization API provides a gRPC or HTTP interface for delegating authorization decisions to an external service. When a request…
- [Envoy Proxy Metrics Service API](https://apis.io/apis/envoy-proxy/metrics-service-api/) — The Envoy Metrics Service API is a gRPC-based interface for streaming Envoy's statistics and metrics to a remote metrics collection service. It allows…
- [Envoy Proxy Tap Service API](https://apis.io/apis/envoy-proxy/tap-service-api/) — The Envoy Tap Service API provides a mechanism for intercepting and recording HTTP and TCP traffic passing through Envoy. The tap filter matches requests…
- [Envoy Proxy Certificates API](https://apis.io/apis/envoy-proxy/envoy-proxy-certificates-api/) — TLS certificate information endpoints.
- [Envoy Proxy Cluster Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-cluster-discovery-api/) — Cluster Discovery Service (CDS) endpoints for dynamically discovering upstream clusters.
- [Envoy Proxy Clusters API](https://apis.io/apis/envoy-proxy/envoy-proxy-clusters-api/) — Cluster management and information endpoints.
- [Envoy Proxy Configuration API](https://apis.io/apis/envoy-proxy/envoy-proxy-configuration-api/) — Configuration inspection and dump endpoints.
- [Envoy Proxy Debugging API](https://apis.io/apis/envoy-proxy/envoy-proxy-debugging-api/) — Debugging and traffic inspection endpoints.
- [Envoy Proxy Endpoint Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-endpoint-discovery-api/) — Endpoint Discovery Service (EDS) endpoints for dynamically discovering cluster endpoints.
- [Envoy Proxy General API](https://apis.io/apis/envoy-proxy/envoy-proxy-general-api/) — General admin interface endpoints.
- [Envoy Proxy Health API](https://apis.io/apis/envoy-proxy/envoy-proxy-health-api/) — Health check management endpoints.
- [Envoy Proxy Listener Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-listener-discovery-api/) — Listener Discovery Service (LDS) endpoints for dynamically discovering listeners.
- [Envoy Proxy Listeners API](https://apis.io/apis/envoy-proxy/envoy-proxy-listeners-api/) — Listener management endpoints.
- [Envoy Proxy Logging API](https://apis.io/apis/envoy-proxy/envoy-proxy-logging-api/) — Logging level management endpoints.
- [Envoy Proxy Profiling API](https://apis.io/apis/envoy-proxy/envoy-proxy-profiling-api/) — CPU and heap profiling endpoints.
- [Envoy Proxy Route Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-route-discovery-api/) — Route Discovery Service (RDS) endpoints for dynamically discovering route configurations.
- [Envoy Proxy Runtime API](https://apis.io/apis/envoy-proxy/envoy-proxy-runtime-api/) — Runtime configuration management endpoints.
- [Envoy Proxy Runtime Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-runtime-discovery-api/) — Runtime Discovery Service (RTDS) endpoints for dynamically discovering runtime configuration layers.
- [Envoy Proxy Secret Discovery API](https://apis.io/apis/envoy-proxy/envoy-proxy-secret-discovery-api/) — Secret Discovery Service (SDS) endpoints for dynamically discovering TLS certificates and keys.
- [Envoy Proxy Server API](https://apis.io/apis/envoy-proxy/envoy-proxy-server-api/) — Server information and lifecycle endpoints.
- [Envoy Proxy Statistics API](https://apis.io/apis/envoy-proxy/envoy-proxy-statistics-api/) — Statistics and metrics endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Envoy Proxy Agentic Access](https://apis.io/agentic-access/envoy-proxy/envoy-proxy-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Envoy Proxy Cluster](https://apis.io/schemas/envoy-proxy/envoy-proxy-cluster/)
- [Envoy Proxy Endpoint](https://apis.io/schemas/envoy-proxy/envoy-proxy-endpoint/)
- [Envoy Proxy Listener](https://apis.io/schemas/envoy-proxy/envoy-proxy-listener/)
- [Envoy Proxy Route Configuration](https://apis.io/schemas/envoy-proxy/envoy-proxy-route/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Envoy Proxy Context](https://apis.io/jsonld/envoy-proxy/envoy-proxy-context/)

#### Collections (20)

Postman and Open Collection request collections.

- [Envoy Proxy Admin API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-admin-api/)
- [Envoy Proxy Admin Certificates API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-certificates-api/)
- [Envoy Proxy Admin Certificates Cluster Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-cluster-discovery-api/)
- [Envoy Proxy Admin Certificates Clusters API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-clusters-api/)
- [Envoy Proxy Admin Certificates Configuration API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-configuration-api/)
- [Envoy Proxy Admin Certificates Debugging API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-debugging-api/)
- [Envoy Proxy Admin Certificates Endpoint Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-endpoint-discovery-api/)
- [Envoy Proxy Admin Certificates General API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-general-api/)
- [Envoy Proxy Admin Certificates Health API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-health-api/)
- [Envoy Proxy Admin Certificates Listener Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-listener-discovery-api/)
- [Envoy Proxy Admin Certificates Listeners API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-listeners-api/)
- [Envoy Proxy Admin Certificates Logging API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-logging-api/)
- [Envoy Proxy Admin Certificates Profiling API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-profiling-api/)
- [Envoy Proxy Admin Certificates Route Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-route-discovery-api/)
- [Envoy Proxy Admin Certificates Runtime API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-runtime-api/)
- [Envoy Proxy Admin Certificates Runtime Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-runtime-discovery-api/)
- [Envoy Proxy Admin Certificates Secret Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-secret-discovery-api/)
- [Envoy Proxy Admin Certificates Server API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-server-api/)
- [Envoy Proxy Admin Certificates Statistics API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-statistics-api/)
- [Envoy Proxy xDS Discovery API](https://apis.io/collections/envoy-proxy/open-envoy-proxy-xds-discovery-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Envoy Proxy — jsonschema rules](https://apis.io/rules/envoy-proxy/envoy-proxy-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Envoy Proxy Domain Security](https://apis.io/security/envoy-proxy/envoy-proxy-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Envoy Proxy Plans Pricing](https://apis.io/plans/envoy-proxy/envoy-proxy-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Envoy Proxy Rate Limits](https://apis.io/rate-limits/envoy-proxy/envoy-proxy-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Envoy Proxy Finops](https://apis.io/finops/envoy-proxy/envoy-proxy-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.envoyproxy.io/)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/)
- [Getting started](https://www.envoyproxy.io/docs/envoy/latest/start/start)
- [Changelog](https://github.com/envoyproxy/envoy/releases)
- [Blog](https://blog.envoyproxy.io/)
- [Security](https://github.com/envoyproxy/envoy/blob/main/SECURITY.md)
- [GitHub](https://github.com/envoyproxy)

## API Evangelist rating

**Kin Score 35.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 45.2 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 35.7 |
| Access clarity | 5.3 |

**Agent readiness 15.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/envoy-proxy/](https://apis.io/providers/envoy-proxy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Envoy Proxy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/envoy-proxy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
