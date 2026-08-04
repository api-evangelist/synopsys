# Synopsys (synopsys)

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

Synopsys is a global leader in semiconductor design EDA tools and software security testing. The company's Software Integrity Group (now rebranded as Black Duck) provides application security testing products including Polaris, Coverity (SAST), Black Duck (SCA), and Seeker (IAST). Synopsys also offers cloud-based EDA and semiconductor design services through the Synopsys Cloud platform with the OpenLink API for license entitlement management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/apis.yml)

## Tags

- Software Security
- Application Security Testing
- Static Analysis
- Software Composition Analysis
- EDA Tools
- Semiconductor Design

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Synopsys Polaris API

The Polaris Software Integrity Platform API provides programmatic access to application security testing orchestration, project management, scan configuration, and issue tracking. Polaris integrates with GitHub, GitLab, Bitbucket, and Azure DevOps for event-driven security scanning automation across SAST, SCA, and IAST testing.

- **Human URL:** [https://polaris.synopsys.com/developer/default/documentation](https://polaris.synopsys.com/developer/default/documentation)
- **Base URL:** `https://polaris.synopsys.com/api`

#### Tags

- Application Security
- Static Analysis
- Software Composition Analysis
- DevSecOps
- CI/CD Integration

#### Properties

- [Documentation](https://polaris.synopsys.com/developer/default/documentation)
- [A P I Quickstart](https://polaris.synopsys.com/developer/default/documentation/t_api-quickstart)
- [OpenAPI](openapi/synopsys-polaris-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synopsys-polaris.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-polaris.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/synopsys-rules.yml)

### Synopsys Coverity REST API

The Coverity Platform REST API provides programmatic access to Coverity static analysis results, project and stream management, defect management, and security findings. Coverity performs deep source code examination across 20+ programming languages and 70+ frameworks to detect critical quality and security defects.

- **Human URL:** [https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api](https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api)
- **Base URL:** `https://coverity.synopsys.com/api`

#### Tags

- Static Analysis
- SAST
- Code Quality
- Defect Management
- Security Testing

#### Properties

- [Documentation](https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api)
- [Open A P I Spec](https://documentation.blackduck.com/bundle/coverity-docs/page/cim-api-docs/openapi/cim-openapi.html)
- [Postman Collection](collections/synopsys-cloud-openlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-cloud-openlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/synopsys-polaris.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-polaris.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synopsys Cloud OpenLink API

The Synopsys Cloud OpenLink API enables semiconductor vendors to interoperate with Synopsys Cloud for managing product entitlements and license distribution. The API supports API key and OAuth2 authentication with JSON payloads over HTTPS. It exposes vendor entitlement endpoints and license request endpoints for both synchronous and asynchronous license delivery.

- **Human URL:** [https://www.synopsys.com/cloud/openlink/api.html](https://www.synopsys.com/cloud/openlink/api.html)
- **Base URL:** `https://api.synopsys.com/openlink`

#### Tags

- EDA Tools
- License Management
- Semiconductor Design
- Cloud Platform

#### Properties

- [Documentation](https://www.synopsys.com/cloud/openlink/api.html)
- [OpenAPI](openapi/synopsys-cloud-openlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synopsys-cloud-openlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-cloud-openlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synopsys Seeker REST API

The Seeker REST API provides programmatic access to Seeker IAST (Interactive Application Security Testing) functionality including project management, vulnerability export, compliance reporting, and administration automation.

- **Human URL:** [https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html](https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html)
- **Base URL:** `https://seeker.synopsys.com/api`

#### Tags

- IAST
- Interactive Testing
- Vulnerability Management
- Application Security

#### Properties

- [Documentation](https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html)
- [Postman Collection](collections/synopsys-cloud-openlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-cloud-openlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/synopsys-polaris.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synopsys-polaris.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/synopsys)
- [Website](https://www.synopsys.com)
- [Developer Portal](https://polaris.synopsys.com/developer/)
- [Community](https://community.synopsys.com/)
- [Git Hub Org](https://github.com/synopsys-sig)
- [J S O N L D Context](json-ld/synopsys-context.jsonld)
- [Vocabulary](vocabulary/synopsys-vocabulary.yml)
