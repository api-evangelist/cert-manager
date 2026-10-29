# Cert-Manager

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

cert-manager is a powerful and extensible X.509 certificate controller for Kubernetes and OpenShift workloads. It obtains certificates from a variety of issuers, including Let's Encrypt, HashiCorp Vault, and Venafi, and ensures certificates are valid and up-to-date, attempting to renew them before expiry. It supports certificate issuance for Ingress, Gateway API, and arbitrary workloads via Certificate resources.

**Areas:** Certificates · Cloud-Native · Graduated · Kubernetes · Security · TLS

## Cert-Manager on APIs.io

Everything profiled for Cert-Manager is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cert-manager/](https://apis.io/providers/cert-manager/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [cert-manager Kubernetes API](https://apis.io/apis/cert-manager/cert-manager-api/) — The cert-manager API extends the Kubernetes API with custom resources including Certificate, Issuer, ClusterIssuer, CertificateRequest, and Order. These…
- [cert-manager CLI (cmctl)](https://apis.io/apis/cert-manager/cmctl-cli/) — cmctl is the command-line tool for managing cert-manager resources. It provides commands for checking certificate status, manually triggering renewals,…
- [trust-manager](https://apis.io/apis/cert-manager/trust-manager/) — trust-manager is a cert-manager companion project for managing TLS trust bundles in Kubernetes and OpenShift clusters. It distributes CA bundles via a…
- [cert-manager approver-policy](https://apis.io/apis/cert-manager/approver-policy/) — approver-policy is a cert-manager policy plugin that automatically approves or denies CertificateRequest resources based on defined CertificateRequestPolicy…
- [cert-manager csi-driver](https://apis.io/apis/cert-manager/csi-driver/) — csi-driver is a Kubernetes Container Storage Interface plugin that works alongside cert-manager to seamlessly request and mount certificate key pairs as…
- [cert-manager csi-driver-spiffe](https://apis.io/apis/cert-manager/csi-driver-spiffe/) — csi-driver-spiffe is a Kubernetes CSI plugin that works alongside cert-manager to transparently deliver SPIFFE SVIDs as X.509 certificate key pairs to…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [cert-manager Certificate](https://apis.io/schemas/cert-manager/cert-manager-certificate/)
- [cert-manager Issuer and ClusterIssuer](https://apis.io/schemas/cert-manager/cert-manager-issuer/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cert Manager Context](https://apis.io/jsonld/cert-manager/cert-manager-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cert-Manager — jsonschema rules](https://apis.io/rules/cert-manager/cert-manager-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cert Manager Domain Security](https://apis.io/security/cert-manager/cert-manager-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cert Manager Plans Pricing](https://apis.io/plans/cert-manager/cert-manager-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cert Manager Rate Limits](https://apis.io/rate-limits/cert-manager/cert-manager-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cert Manager Finops](https://apis.io/finops/cert-manager/cert-manager-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cert-manager.io)
- [Documentation](https://cert-manager.io/docs/)
- [Getting started](https://cert-manager.io/docs/getting-started/)
- [Changelog](https://github.com/cert-manager/cert-manager/releases)
- [GitHub](https://github.com/cert-manager)

## API Evangelist rating

**Kin Score 33.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 22.7 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 31.0 |
| Access clarity | 7.9 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
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

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cert-manager/](https://apis.io/providers/cert-manager/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cert-Manager: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cert-manager/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
