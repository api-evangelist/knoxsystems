# Knox Systems

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
