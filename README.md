# Synopsys

Synopsys is a global leader in semiconductor design EDA tools and software security testing. The company's Software Integrity Group (now Black Duck) provides application security testing products including Polaris, Coverity (SAST), Black Duck (SCA), and Seeker (IAST). Synopsys also offers cloud-based EDA and semiconductor design services through the Synopsys Cloud platform.

**Type:** Company
**Website:** [synopsys.com](https://www.synopsys.com)
**Developer Portal:** [polaris.synopsys.com/developer](https://polaris.synopsys.com/developer/)

## APIs

### Polaris API

The Polaris Software Integrity Platform API provides programmatic access to application security testing orchestration, project management, scan configuration, and issue tracking. Integrates with GitHub, GitLab, Bitbucket, and Azure DevOps.

- **Documentation:** [polaris.synopsys.com/developer/default/documentation](https://polaris.synopsys.com/developer/default/documentation)
- **OpenAPI:** [openapi/synopsys-polaris-openapi.yml](openapi/synopsys-polaris-openapi.yml)

| Method | Path | Summary |
|--------|------|---------|
| GET | /portfolios/projects | List Projects |
| GET | /portfolios/projects/{projectId} | Get Project |
| GET | /portfolios/branches | List Branches |
| GET | /jobs/runs | List Scans |
| GET | /jobs/runs/{runId} | Get Scan Run |
| GET | /issues | List Issues |
| GET | /issues/{issueId} | Get Issue |
| POST | /reports | Generate Report |
| GET | /reports/{reportId} | Get Report |

### Cloud OpenLink API

The Synopsys Cloud OpenLink API enables semiconductor vendors to interoperate with Synopsys Cloud for managing product entitlements and license distribution, supporting both synchronous and asynchronous license file delivery.

- **Documentation:** [synopsys.com/cloud/openlink/api.html](https://www.synopsys.com/cloud/openlink/api.html)
- **OpenAPI:** [openapi/synopsys-cloud-openlink-openapi.yml](openapi/synopsys-cloud-openlink-openapi.yml)

| Method | Path | Summary |
|--------|------|---------|
| POST | /entitlements | Get Vendor Entitlements |
| POST | /licenses | Generate License File |
| GET | /licenses/{licenseId} | Download License File |

### Coverity REST API

The Coverity Platform REST API provides programmatic access to static analysis results, project management, and defect tracking.

- **Documentation:** [community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api](https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api)

### Seeker REST API

The Seeker REST API provides access to IAST vulnerability findings, project management, and compliance reporting.

- **Documentation:** [Seeker API Documentation](https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html)

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/polaris.yaml](capabilities/shared/polaris.yaml) | Polaris API consumed definition |
| [capabilities/shared/cloud-openlink.yaml](capabilities/shared/cloud-openlink.yaml) | Cloud OpenLink API consumed definition |

### Workflow Capabilities

| Capability | Description | Tools |
|-----------|-------------|-------|
| [application-security-testing.yaml](capabilities/application-security-testing.yaml) | Unified AppSec testing (projects + scans + issues + reports) | 6 tools |
| [eda-license-management.yaml](capabilities/eda-license-management.yaml) | EDA tool license management (entitlements + license generation) | 3 tools |

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [openapi/synopsys-polaris-openapi.yml](openapi/synopsys-polaris-openapi.yml) |
| OpenAPI | [openapi/synopsys-cloud-openlink-openapi.yml](openapi/synopsys-cloud-openlink-openapi.yml) |
| Spectral Rules | [rules/synopsys-rules.yml](rules/synopsys-rules.yml) |
| JSON Schema | [json-schema/synopsys-security-issue-schema.json](json-schema/synopsys-security-issue-schema.json) |
| JSON Structure | [json-structure/synopsys-security-issue-structure.json](json-structure/synopsys-security-issue-structure.json) |
| JSON-LD Context | [json-ld/synopsys-context.jsonld](json-ld/synopsys-context.jsonld) |
| Vocabulary | [vocabulary/synopsys-vocabulary.yml](vocabulary/synopsys-vocabulary.yml) |

## Examples

| File | Description |
|------|-------------|
| [examples/synopsys-polaris-listIssues-example.json](examples/synopsys-polaris-listIssues-example.json) | List security issues response |
| [examples/synopsys-cloud-openlink-getEntitlements-example.json](examples/synopsys-cloud-openlink-getEntitlements-example.json) | Get license entitlements response |

## Features

- Static Application Security Testing (SAST) via Coverity
- Software Composition Analysis (SCA) via Black Duck
- Interactive Application Security Testing (IAST) via Seeker
- DevSecOps Pipeline Integration
- GitHub, GitLab, Bitbucket, Azure DevOps Integration
- CWE and CVE-based Issue Classification
- Security Report Generation (PDF, JSON, CSV)
- EDA Tool License Entitlement Management
- Synchronous and Asynchronous License Delivery
- GitHub Actions Integration

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
