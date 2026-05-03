# Sysdig

Sysdig is a cloud and container security platform that provides runtime threat detection, vulnerability management, cloud security posture management (CSPM), compliance automation, and observability for containers, Kubernetes, and cloud environments. Sysdig Monitor offers full-stack monitoring and alerting while Sysdig Secure delivers runtime security, vulnerability scanning, policy enforcement, incident response, and compliance reporting.

**Website:** [https://sysdig.com/](https://sysdig.com/)
**Documentation:** [https://docs.sysdig.com/](https://docs.sysdig.com/)
**Developer Portal:** [https://docs.sysdig.com/en/developer-tools/](https://docs.sysdig.com/en/developer-tools/)

## APIs

### Sysdig Monitor

Programmatic access to monitoring and observability capabilities including dashboards, alerts, events, metrics, teams, and notification channels for cloud-native environments.

- **Documentation:** [https://docs.sysdig.com/en/developer-tools/sysdig-api/](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- **OpenAPI:** [openapi/sysdig-monitor-openapi.yml](openapi/sysdig-monitor-openapi.yml)
- **Base URL:** https://api.us1.sysdig.com

### Sysdig Secure

Programmatic access to cloud and container security including vulnerability management, runtime policies, compliance, activity audit, image scanning, SBOM retrieval, and Falco rules management.

- **Documentation:** [https://docs.sysdig.com/en/developer-tools/sysdig-api/](https://docs.sysdig.com/en/developer-tools/sysdig-api/)
- **OpenAPI:** [openapi/sysdig-secure-openapi.yml](openapi/sysdig-secure-openapi.yml)
- **Base URL:** https://api.us1.sysdig.com

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [sysdig-monitor-openapi.yml](openapi/sysdig-monitor-openapi.yml) | Sysdig Monitor - alerts, dashboards, events, metrics, teams |
| [sysdig-secure-openapi.yml](openapi/sysdig-secure-openapi.yml) | Sysdig Secure - vulnerabilities, policies, compliance, Falco rules |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [sysdig-rules.yml](rules/sysdig-rules.yml) | Spectral linting rules for Sysdig API conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [cloud-security-monitoring.yaml](capabilities/cloud-security-monitoring.yaml) | Unified workflow combining Monitor + Secure for cloud security operations |

**Shared Definitions:**

| Shared File | Description |
|-------------|-------------|
| [shared/sysdig-monitor.yaml](capabilities/shared/sysdig-monitor.yaml) | Sysdig Monitor per-API capability definition |
| [shared/sysdig-secure.yaml](capabilities/shared/sysdig-secure.yaml) | Sysdig Secure per-API capability definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [sysdig-alert-schema.json](json-schema/sysdig-alert-schema.json) | Schema for Sysdig Monitor alert definitions |
| [sysdig-vulnerability-schema.json](json-schema/sysdig-vulnerability-schema.json) | Schema for Sysdig Secure vulnerability findings |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [sysdig-alert-structure.json](json-structure/sysdig-alert-structure.json) | Field documentation for Sysdig alert objects |

### JSON-LD

| Context | Description |
|---------|-------------|
| [sysdig-context.jsonld](json-ld/sysdig-context.jsonld) | Linked data context for Sysdig entities |

### Examples

| Example | Description |
|---------|-------------|
| [sysdig-list-alerts-example.json](examples/sysdig-list-alerts-example.json) | Example request/response for listing alerts |
| [sysdig-list-vulnerability-results-example.json](examples/sysdig-list-vulnerability-results-example.json) | Example request/response for listing vulnerability results |

### Vocabulary

| File | Description |
|------|-------------|
| [sysdig-vocabulary.yml](vocabulary/sysdig-vocabulary.yml) | Domain vocabulary for Sysdig platform concepts |

## Developer Tools

- **Python SDK:** [https://github.com/sysdiglabs/sysdig-sdk-python](https://github.com/sysdiglabs/sysdig-sdk-python)
- **CLI:** [https://sysdiglabs.github.io/sysdig-platform-cli/](https://sysdiglabs.github.io/sysdig-platform-cli/)
- **Terraform Provider:** [https://registry.terraform.io/providers/sysdiglabs/sysdig/latest](https://registry.terraform.io/providers/sysdiglabs/sysdig/latest)
- **Kubernetes Operator:** [https://github.com/sysdiglabs/sysdig-operator](https://github.com/sysdiglabs/sysdig-operator)
- **Helm Charts:** [https://github.com/sysdiglabs/charts](https://github.com/sysdiglabs/charts)
- **GitHub Organization:** [https://github.com/sysdiglabs](https://github.com/sysdiglabs)

## Authentication

All Sysdig APIs use Bearer token authentication. Set the `Authorization: Bearer {token}` header using one of:

- **API Token** - user-scoped token from Settings > User Profile
- **Team-Based Service Account** - team-scoped programmatic credential
- **Global Service Account** - organization-wide programmatic credential

## Regional Endpoints

| Region | Base URL |
|--------|----------|
| US East | https://api.us1.sysdig.com |
| EU Central | https://api.eu1.sysdig.com |
| Asia Pacific | https://api.au1.sysdig.com |
