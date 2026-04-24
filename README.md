# cert-manager (cert-manager)
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
