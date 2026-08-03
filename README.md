# Adaptive Shield (adaptive-shield)

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

Adaptive Shield (now CrowdStrike Falcon Shield) is a SaaS Security Posture Management (SSPM) platform that continuously monitors, remediates, and governs SaaS application security configurations and identity risks. Acquired by CrowdStrike, the platform covers 200+ SaaS integrations with over 3,500 built-in security checks, helping organizations detect misconfigurations, manage human and non-human identities, discover shadow applications, and maintain compliance across their entire SaaS stack. The REST API (v1) enables programmatic access to alerts, user inventory, device inventory, integrations, security checks, and compliance data.

**URL:** [https://www.crowdstrike.com/platform/falcon-shield/](https://www.crowdstrike.com/platform/falcon-shield/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - SaaS Security, SSPM, Security Posture Management, Cybersecurity, Cloud Security, Identity Management, Compliance

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

## APIs

### Adaptive Shield REST API
The Adaptive Shield REST API v1 provides programmatic access to SaaS security posture data including alerts, user and device inventory, integration configurations, security check results, violations, and compliance controls. Authentication uses a per-user API key (access token). Regional endpoints are available for US (api.adaptive-shield.com) and EU (eu.api.adaptive-shield.com) regions.

**Human URL:** [https://www.crowdstrike.com/platform/falcon-shield/](https://www.crowdstrike.com/platform/falcon-shield/)

#### Tags:

 - SaaS Security, SSPM, REST API, Alerts, Compliance

#### Properties

- [Documentation](https://www.crowdstrike.com/platform/falcon-shield/)
- [Authentication](https://www.adaptive-shield.com/support)

## Common Properties

- [Website](https://www.crowdstrike.com/platform/falcon-shield/)
- [Portal](https://www.crowdstrike.com/platform/falcon-shield/)
- [Blog](https://www.adaptive-shield.com/blog/)
- [Resources](https://www.adaptive-shield.com/resources)
- [Integrations](https://www.adaptive-shield.com/integrations)
- [Support](https://www.adaptive-shield.com/support)

## Features

| Name | Description |
|------|-------------|
| SaaS Misconfiguration Detection | Continuously monitors 200+ SaaS applications with 3,500+ built-in security checks to detect and remediate misconfigurations that expose organizations to security risks. |
| Identity And Access Governance | Manages both human and non-human identities (NHI) across SaaS platforms, detecting over-privileged accounts and suspicious access patterns. |
| Shadow App Discovery | Discovers unsanctioned and shadow SaaS applications connected to the organization's environment, providing visibility into unauthorized integrations. |
| AI Agent Visibility And Control | Provides visibility into and governance over AI agents operating within enterprise SaaS platforms including Microsoft 365, Salesforce, and OpenAI. |
| Compliance Monitoring | Tracks compliance posture across SaaS applications against frameworks such as SOC 2, ISO 27001, GDPR, and HIPAA using automated security check mappings. |
| REST API Access | Public REST API v1 with API key authentication enables programmatic access to alerts, user/device inventory, integration data, security check results, violations, and compliance controls. US and EU regional endpoints available. |
| SIEM And Platform Integrations | Integrates with SIEM platforms (Splunk, Datadog), security platforms (CrowdStrike Falcon), and vulnerability management platforms via API and native connectors. |

## Use Cases

| Name | Description |
|------|-------------|
| SaaS Security Posture Management | Security teams can continuously monitor and remediate misconfigurations across the organization's entire SaaS stack from a single dashboard. |
| Identity Risk Detection | Detect and remediate over-privileged users, dormant accounts, and suspicious login behavior across all connected SaaS applications. |
| Compliance Audit Automation | Automate compliance evidence collection and posture monitoring for SOC 2, ISO 27001, GDPR, and other frameworks across SaaS applications. |
| Third-Party App Risk Management | Identify and assess risk from third-party OAuth apps and browser extensions connected to critical SaaS platforms. |
| Security Operations Integration | Pull SaaS security alerts and posture data into SIEM and SOAR platforms via the REST API for unified security operations workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft 365 | SaaS security monitoring for Microsoft 365 suite including Exchange, Teams, SharePoint, and OneDrive. |
| Salesforce | Security posture monitoring and misconfiguration detection for Salesforce CRM. |
| Slack | Configuration monitoring and security checks for Slack workspace settings. |
| Zoom | Security configuration monitoring for Zoom video conferencing accounts. |
| Okta | Identity provider integration for user access and authentication configuration monitoring. |
| Datadog | Sends SaaS posture alerts as Datadog Events via OAuth integration. |
| Splunk | Splunk add-on for ingesting Adaptive Shield security events and alerts. |
| CrowdStrike Falcon | Native integration with CrowdStrike Falcon platform following acquisition. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
