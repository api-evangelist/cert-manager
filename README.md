# cert-manager (cert-manager)

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

cert-manager is a CNCF Graduated (September 2024) open-source project that automates the management and issuance of TLS certificates in Kubernetes and OpenShift clusters. It obtains certificates from a variety of issuers (Let's Encrypt / ACME, HashiCorp Vault, Venafi, AWS PCA, internal CAs) and ensures certificates remain valid through automatic renewal. cert-manager supports certificate issuance for Ingress, Gateway API, and arbitrary workloads via the Certificate custom resource.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cert-manager/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Certificates, TLS, Kubernetes, Security, Cloud Native, CNCF, Graduated

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-23

## APIs

### cert-manager Kubernetes API
Extends the Kubernetes API with custom resources (Certificate, Issuer, ClusterIssuer, CertificateRequest, Order) for declarative TLS certificate management, automatic renewal, and ACME integration.

**Human URL:** [https://cert-manager.io/docs/](https://cert-manager.io/docs/)

#### Tags
- Kubernetes API, Certificates, TLS

#### Properties
- [Documentation](https://cert-manager.io/docs/)
- [Reference](https://cert-manager.io/docs/reference/api-docs/)
- [Getting Started](https://cert-manager.io/docs/getting-started/)
- [GitHubRepository](https://github.com/cert-manager/cert-manager)

### cert-manager CLI (cmctl)
Command-line tool for managing cert-manager resources, checking certificate status, triggering renewals, and approving/denying CertificateRequests.

**Human URL:** [https://cert-manager.io/docs/reference/cmctl/](https://cert-manager.io/docs/reference/cmctl/)

#### Tags
- CLI, Certificate Management

### trust-manager
cert-manager companion for managing TLS trust bundles in Kubernetes clusters, distributing CA bundles via the Bundle custom resource.

**Human URL:** [https://cert-manager.io/docs/trust/trust-manager/](https://cert-manager.io/docs/trust/trust-manager/)

#### Tags
- Kubernetes, TLS, Trust Bundles

### cert-manager approver-policy
Policy plugin that automatically approves or denies CertificateRequest resources based on defined CertificateRequestPolicy custom resources.

**Human URL:** [https://cert-manager.io/docs/policy/approval/approver-policy/](https://cert-manager.io/docs/policy/approval/approver-policy/)

#### Tags
- Policy, Certificate Approval, Security

### cert-manager csi-driver
CSI plugin for mounting certificate key pairs as ephemeral volumes directly into pods.

**Human URL:** [https://cert-manager.io/docs/usage/csi-driver/](https://cert-manager.io/docs/usage/csi-driver/)

#### Tags
- CSI, Kubernetes, Certificate Management

### cert-manager csi-driver-spiffe
CSI plugin to deliver SPIFFE SVIDs as X.509 certificate key pairs to mounted pods using ephemeral volumes.

**Human URL:** [https://cert-manager.io/docs/usage/csi-driver-spiffe/](https://cert-manager.io/docs/usage/csi-driver-spiffe/)

#### Tags
- CSI, SPIFFE, Identity, Kubernetes

## Common Properties

- [Website](https://cert-manager.io)
- [Documentation](https://cert-manager.io/docs/)
- [Getting Started](https://cert-manager.io/docs/getting-started/)
- [Reference](https://cert-manager.io/docs/reference/)
- [GitHubOrganization](https://github.com/cert-manager)
- [GitHubRepository](https://github.com/cert-manager/cert-manager)
- [Change Log](https://github.com/cert-manager/cert-manager/releases)
- [JSONSchema](json-schema/cert-manager-certificate-schema.json)
- [JSONSchema](json-schema/cert-manager-issuer-schema.json)
- [JSON-LD](json-ld/cert-manager-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
