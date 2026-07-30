# Knox Systems

Knox Systems is a federal cloud compliance and managed-security company that provides an accelerated path to FedRAMP authorization for SaaS and AI vendors selling into the U.S. government, marketed as "FedRAMP in 90 days for 90% less." Its platform combines a pre-authorized FedRAMP boundary, a deployable Landing Zone, hardened images, and Knox AI — a continuous-monitoring and automated remediation engine — running across AWS, Azure, and GCP at FedRAMP Moderate, FedRAMP High, and DISA Impact Level 4.

Website: https://knoxsystems.com — Backed by: Felicis

## API surface

**Knox Systems publishes no public API.** As of the 2026-07-19 enrichment pass there is no developer portal, API documentation, OpenAPI definition, SDK, CLI, MCP server, sandbox, or changelog. `/docs`, `/developers`, `/api`, and `/llms.txt` all return 404, and no `/.well-known/` discovery documents are served. The business is sales-led and partner-led; `trust.knoxsystems.com` resolves to an authenticated product application rather than a trust center.

Artifacts in this repo therefore cover company identity, compliance posture, and security posture only — no spec-derived artifacts were generated, because there is no spec to derive them from.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `conformance/knoxsystems-conformance.yml` | Conformance / Compliance | searched |
| `security/knoxsystems-vulnerability-disclosure.yml` | VulnerabilityDisclosure | searched |
| `security/knoxsystems-domain-security.yml` | DomainSecurity | probed |
| `well-known/knoxsystems-well-known.yml` | (negative result — no pointer) | probed |
| `llms/knoxsystems-llms.txt` | LLMsTxt | generated |

## Compliance posture

FedRAMP Moderate and High authorized boundary, DISA IL4 (IL5 targeted late 2026), aligned to NIST 800-53. Reports 15+ ATOs across federal and DoD agencies. No SOC 2, ISO 27001, CMMC, StateRAMP, or FIPS 140-3 attestation is published.
