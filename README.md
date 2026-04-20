# Aqua Security (aqua-security)
Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and compliance enforcement.

**URL:** [https://www.aquasec.com/](https://www.aquasec.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Native, Containers, Kubernetes, Runtime Protection, Security, Vulnerability Scanning

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Aqua Security
Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and compliance enforcement.

**Human URL:** [https://www.aquasec.com/](https://www.aquasec.com/)

#### Tags:

 - Cloud Native Security, Container Security, Kubernetes, Runtime Protection, Security, Vulnerability Scanning, CSPM, DevSecOps

#### Properties

- [Documentation](https://docs.aquasec.com/)
- [GettingStarted](https://docs.aquasec.com/docs/getting-started)
- [APIReference](https://docs.aquasec.com/reference/api-overview)
- [Authentication](https://docs.aquasec.com/reference/authentication)
- [OpenAPI](openapi/aqua-security-api.yaml)
- [JSONSchema](json-schema/)

### Trivy
Trivy is a comprehensive open source security scanner for containers, Kubernetes, code repositories, clouds, and more — finding vulnerabilities, misconfigurations, secrets, and SBOMs.

**Human URL:** [https://trivy.dev/](https://trivy.dev/)

#### Tags:

 - Container Scanning, Open Source, Vulnerability Scanner, SBOM, Kubernetes Security

#### Properties

- [Documentation](https://aquasecurity.github.io/trivy/)
- [GettingStarted](https://aquasecurity.github.io/trivy/latest/getting-started/installation/)
- [GitHubRepository](https://github.com/aquasecurity/trivy)

### Tracee
Tracee is a runtime security and forensics tool for Linux that uses eBPF technology to trace system events and detect suspicious behavioral patterns.

**Human URL:** [https://aquasecurity.github.io/tracee/](https://aquasecurity.github.io/tracee/)

#### Tags:

 - eBPF, Runtime Security, Linux Security, Forensics, Open Source

#### Properties

- [Documentation](https://aquasecurity.github.io/tracee/)
- [GitHubRepository](https://github.com/aquasecurity/tracee)

## Common Properties

- [Portal](https://www.aquasec.com/)
- [Documentation](https://docs.aquasec.com/)
- [GitHubOrganization](https://github.com/aquasecurity)
- [Blog](https://www.aquasec.com/blog/)
- [Pricing](https://www.aquasec.com/aqua-cloud/)
- [SignUp](https://www.aquasec.com/demo/)
- [Support](https://support.aquasec.com/)
- [StatusPage](https://status.aquasec.com/)
- [TermsOfService](https://www.aquasec.com/aqua-cloud/terms-of-service/)
- [PrivacyPolicy](https://www.aquasec.com/privacy-policy/)
- [ReleaseNotes](https://docs.aquasec.com/docs/release-notes)

## Features

| Name | Description |
|------|-------------|
| Vulnerability Scanning | Comprehensive scanning of container images, VM workloads, and serverless functions for known CVEs and misconfigurations. |
| Runtime Protection | Real-time protection of running containers and cloud workloads using behavioral analysis and policy enforcement. |
| CSPM | Cloud Security Posture Management to identify and remediate misconfigurations across AWS, Azure, and GCP. |
| Supply Chain Security | Protect the software supply chain by scanning code, open source dependencies, and CI/CD pipelines. |
| Kubernetes Security | Native Kubernetes security including admission control, runtime policies, and compliance benchmarks. |
| Compliance Enforcement | Automated compliance checks against CIS, PCI-DSS, HIPAA, NIST, and other regulatory frameworks. |
| Secrets Detection | Detect and prevent secrets and credentials from being embedded in container images and code repositories. |
| Network Policy | Visualize and enforce container network connectivity and micro-segmentation policies. |

## Use Cases

| Name | Description |
|------|-------------|
| Container Security | Secure Docker and OCI containers throughout the build-to-runtime lifecycle. |
| Kubernetes Security | Enforce security policies, runtime protection, and compliance for Kubernetes clusters. |
| Serverless Security | Protect AWS Lambda, Azure Functions, and Google Cloud Functions from vulnerabilities and runtime attacks. |
| DevSecOps | Integrate security scanning into CI/CD pipelines to shift security left and prevent vulnerabilities from reaching production. |
| Cloud Workload Protection | Protect VMs and cloud workloads across multi-cloud environments from threats and misconfigurations. |
| SBOM Generation | Generate Software Bill of Materials (SBOM) for container images and code repositories to understand component risk. |

## Integrations

| Name | Description |
|------|-------------|
| AWS | Native integrations with AWS ECS, EKS, Lambda, ECR, Security Hub, and other AWS services. |
| Azure | Integrations with Azure Kubernetes Service, Azure Container Registry, and Azure Security Center. |
| Google Cloud | Support for GKE, Google Container Registry, and Cloud Run on Google Cloud Platform. |
| GitHub Actions | Trivy GitHub Action for automated vulnerability scanning in CI/CD workflows. |
| Jenkins | Jenkins plugin for container image scanning and policy enforcement in pipelines. |
| Terraform | Terraform provider for declarative management of Aqua Security platform configuration. |
| Helm | Official Helm charts for deploying Aqua Security components on Kubernetes. |
| Splunk | Integration with Splunk for centralized security event logging and SIEM. |
| PagerDuty | Alert routing to PagerDuty for runtime security event notifications. |
| Slack | Security alert notifications delivered to Slack channels. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Aqua Security REST API](openapi/aqua-security-api.yaml)

### JSON Schema

- [Login Request](json-schema/aqua-security-api-login-request-schema.json)
- [Login Response](json-schema/aqua-security-api-login-response-schema.json)
- [Image](json-schema/aqua-security-api-image-schema.json)
- [Image Detail](json-schema/aqua-security-api-image-detail-schema.json)
- [Image List](json-schema/aqua-security-api-image-list-schema.json)
- [Image Request](json-schema/aqua-security-api-image-request-schema.json)
- [Container](json-schema/aqua-security-api-container-schema.json)
- [Container List](json-schema/aqua-security-api-container-list-schema.json)
- [Policy](json-schema/aqua-security-api-policy-schema.json)
- [Policy List](json-schema/aqua-security-api-policy-list-schema.json)
- [Policy Request](json-schema/aqua-security-api-policy-request-schema.json)
- [Registry](json-schema/aqua-security-api-registry-schema.json)
- [Registry List](json-schema/aqua-security-api-registry-list-schema.json)
- [User](json-schema/aqua-security-api-user-schema.json)
- [User List](json-schema/aqua-security-api-user-list-schema.json)
- [Vulnerability Counts](json-schema/aqua-security-api-vulnerability-counts-schema.json)
- [Error Response](json-schema/aqua-security-api-error-response-schema.json)

### JSON Structure

- [Login Request Structure](json-structure/aqua-security-api-login-request-structure.json)
- [Image Structure](json-structure/aqua-security-api-image-structure.json)
- [Container Structure](json-structure/aqua-security-api-container-structure.json)
- [Policy Structure](json-structure/aqua-security-api-policy-structure.json)

### JSON-LD

- [Aqua Security API Context](json-ld/aqua-security-api-context.jsonld)

### Examples

- [Image Example](examples/aqua-security-api-image-example.json)
- [Container Example](examples/aqua-security-api-container-example.json)
- [Policy Example](examples/aqua-security-api-policy-example.json)
- [Registry Example](examples/aqua-security-api-registry-example.json)
- [User Example](examples/aqua-security-api-user-example.json)

## Vocabulary

- [Aqua Security Vocabulary](vocabulary/aqua-security-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 8 actions, 0 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Aqua Security Spectral Rules](rules/aqua-security-spectral-rules.yml) — 28 rules across 13 categories enforcing Aqua Security API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
