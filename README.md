# Sysdig (sysdig)

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

Sysdig is a cloud and container security platform that provides runtime threat detection, vulnerability management, cloud security posture management (CSPM), compliance automation, and observability for containers, Kubernetes, and cloud environments. Sysdig Monitor offers full-stack monitoring and alerting while Sysdig Secure delivers runtime security, vulnerability scanning, policy enforcement, incident response, and compliance reporting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Security
- Containers
- Kubernetes
- Runtime Security
- Security
- Vulnerability Management
- Monitoring
- Observability
- CSPM
- Compliance

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Sysdig Monitor

The Sysdig Monitor API provides programmatic access to monitoring and observability capabilities including dashboards, alerts, events, metrics, teams, notification channels, and scanning results for cloud-native environments.

- **Human URL:** [https://docs.sysdig.com/en/developer-tools/sysdig-api/](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- **Base URL:** `https://api.us1.sysdig.com`

#### Tags

- Monitoring
- Observability
- Alerts
- Dashboards
- Metrics
- Events

#### Properties

- [Documentation](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-monitor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.sysdig.com/en/getting-started/)
- [Authentication](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- [Postman Collection](collections/sysdig-monitor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sysdig-monitor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sysdig-secure.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sysdig-secure.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sysdig Secure

The Sysdig Secure API provides programmatic access to cloud and container security capabilities including vulnerability management, runtime policies, compliance checks, activity audit, incident response, image scanning, SBOM retrieval, and Falco rules management.

- **Human URL:** [https://docs.sysdig.com/en/developer-tools/sysdig-api/](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- **Base URL:** `https://api.us1.sysdig.com`

#### Tags

- Security
- Vulnerability Management
- Compliance
- Runtime Security
- Falco
- Scanning
- CSPM

#### Properties

- [Documentation](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-secure-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.sysdig.com/en/getting-started/)
- [Postman Collection](collections/sysdig-monitor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sysdig-monitor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sysdig-secure.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sysdig-secure.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/sysdig)
- [Website](https://sysdig.com/)
- [Documentation](https://docs.sysdig.com/)
- [Developer  Portal](https://docs.sysdig.com/en/developer-tools/)
- [Getting Started](https://docs.sysdig.com/en/getting-started/)
- [GitHub Organization](https://github.com/sysdiglabs)
- [Blog](https://sysdig.com/blog/)
- [Pricing](https://sysdig.com/pricing/)
- [Sign Up](https://sysdig.com/company/free-trial/)
- [Terraform  Provider](https://registry.terraform.io/providers/sysdiglabs/sysdig/latest)
- [Python  S D K](https://github.com/sysdiglabs/sysdig-sdk-python)
- [C L I](https://sysdiglabs.github.io/sysdig-platform-cli/)
- [Kubernetes  Operator](https://github.com/sysdiglabs/sysdig-operator)
- [Helm  Charts](https://github.com/sysdiglabs/charts)
- [Spectral  Rules](https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/rules/sysdig-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/vocabulary/sysdig-vocabulary.yml)
- [Changelog](https://docs.sysdig.com/en/release-notes/)
- [Support](https://sysdig.com/support/)
- [Status Page](https://status.sysdig.com/)
- [M C P Server](https://github.com/sysdiglabs/sysdig-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
