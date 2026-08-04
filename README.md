# Siemens Healthineers (siemens-healthineers)

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

Siemens Healthineers AG is a German medical technology company (XETRA SHL) covering medical imaging, laboratory diagnostics, point-of-care testing, advanced therapies, and cancer care (following the April 2021 Varian Medical Systems acquisition for USD 16.4 billion). Its digital surface is anchored by the teamplay digital health platform, the Digital Marketplace, syngo.via OpenApps, and the Frontier Development Kit, with developer access offered through a gated teamplay developer portal that exposes APIs for single sign-on, licensing, user roles and permissions, the teamplay receiver plug-in, DICOM image access, customer-specific report submission, and status indicator notifications. No public OpenAPI specifications are published; the API catalog and reference documentation sit behind teamplay developer account authentication.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/siemens-healthineers/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Healthcare, Medical Imaging, Laboratory Diagnostics, Cancer Care, Radiation Oncology, DICOM, Digital Health, Healthcare IT, Medical Devices, Teamplay

## Segments

Medical Imaging, Laboratory Diagnostics, Cancer Care, Healthcare IT, Digital Health Platforms

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### teamplay Single Sign-On API
Authentication and identity federation surface that lets partner applications running on the teamplay digital health platform, syngo.via OpenApps, and Cios mobile C-arm systems sign users in using their teamplay credentials.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Authentication, Single Sign-On, Identity, Teamplay, Healthcare

### teamplay Licensing API
Licensing management surface used by partner applications to validate, provision, and reconcile subscription entitlements within the teamplay Cloud Platform and syngo.via OpenApps environments.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Licensing, Entitlements, Subscriptions, Teamplay, Healthcare

### teamplay User Roles and Permissions API
User management surface that exposes user roles and permission assignments to partner applications on the teamplay digital health platform, so partner solutions can align in-application access control with the customer's teamplay tenancy.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Authorization, Users, Roles, Permissions, Teamplay, Healthcare

### teamplay Receiver Plug-in API
Plug-in surface for the teamplay receiver, the on-premises agent that collects operational and clinical telemetry from imaging devices and transmits it to the teamplay Cloud Platform.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Data Collection, Telemetry, On-Premises Agent, Teamplay, Healthcare

### teamplay DICOM Image Access API
Imaging access surface enabling partner applications to retrieve DICOM studies and instances stored in the teamplay digital health platform, supporting secure peer sharing and processing use cases.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** DICOM, Medical Imaging, Images, Teamplay, Healthcare

### teamplay Reports and Results Submission API
Submission surface allowing partner applications to push customer-specific reports and clinical results back into the teamplay digital health platform.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Reports, Results, Clinical Data, Teamplay, Healthcare

### teamplay Status Indicator Notifications API
Notification surface that lets partner applications publish status indicators (operational state, health, processing progress) into the teamplay digital health platform.

**Human URL:** [Digital Marketplace for Partners](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)

**Tags:** Notifications, Status, Operations, Teamplay, Healthcare

### syngo.via Frontier Development Kit
Research-oriented SDK that lets clinicians, researchers, and developers turn research ideas into deployable image-post-processing applications inside syngo.via. Distributed through the Digital Marketplace and installed into syngo.via OpenApps.

**Human URL:** [syngo.via Frontier](https://www.siemens-healthineers.com/digital-health-solutions/syngovia-frontier)

**Tags:** SDK, Research, Medical Imaging, Post-Processing, syngo.via, Healthcare

### syngo.via OpenApps Platform
Application platform inside syngo.via that hosts third-party and Siemens Healthineers research and clinical apps distributed through the Digital Marketplace. Apps can be trialed commitment-free for 90 days.

**Human URL:** [syngo.via OpenApps](https://www.siemens-healthineers.com/medical-imaging-it/syngo-carbon-products/openapps)

**Tags:** Platform, Applications, Medical Imaging, syngo.via, Healthcare

### Siemens Healthineers Digital Marketplace
Curated catalog distributing Siemens Healthineers and partner clinical and operational applications across the teamplay digital health platform, syngo.via OpenApps, and Cios mobile C-arm systems. All applications are security-scanned and run inside the Healthineers privacy-by-design infrastructure. Available in 60+ countries.

**Human URL:** [Digital Marketplace](https://www.siemens-healthineers.com/digital-health-solutions/digital-marketplace)

**Base URL:** `https://marketplace.teamplay.siemens.com/`

**Tags:** Marketplace, Catalog, Applications, Healthcare

### K2s Kubernetes Distribution for Windows Hosts
Open-source Kubernetes distribution built specifically for Windows hosts, published from the Siemens-Healthineers GitHub org.

**Human URL:** [github.com/Siemens-Healthineers/K2s](https://github.com/Siemens-Healthineers/K2s)

**Tags:** Kubernetes, Windows, Infrastructure, Open Source, PowerShell

### SHIELD-DAVE Medical Device Cybersecurity Platform
PHP-based platform focused on medical device cybersecurity and US FDA compliance workflows.

**Human URL:** [github.com/Siemens-Healthineers/SHIELD-DAVE](https://github.com/Siemens-Healthineers/SHIELD-DAVE)

**Tags:** Cybersecurity, Medical Devices, FDA Compliance, Open Source, PHP

### ETWAnalyzer Command Line Tool
C# command-line tool for analyzing Event Tracing for Windows (ETW) capture files using a query syntax.

**Human URL:** [github.com/Siemens-Healthineers/ETWAnalyzer](https://github.com/Siemens-Healthineers/ETWAnalyzer)

**Tags:** CLI, Diagnostics, Performance, Windows, Open Source, C#

### Patch-CLIP Embedding Model
Python research project extending the CLIP architecture with patch-level embeddings for image understanding.

**Human URL:** [github.com/Siemens-Healthineers/patch-clip](https://github.com/Siemens-Healthineers/patch-clip)

**Tags:** Machine Learning, Embeddings, Medical Imaging, Research, Open Source, Python

## Common Properties

- [Website](https://www.siemens-healthineers.com/)
- [Developer Portal (US)](https://devportal.us.api.teamplay.siemens-healthineers.com/)
- [Developer Portal (Frontier)](https://developer.frontier.api.teamplay.siemens-healthineers.com/)
- [Sign Up](https://devportal.us.api.teamplay.siemens-healthineers.com/signup)
- [Sign In](https://devportal.us.api.teamplay.siemens-healthineers.com/signin)
- [Marketplace](https://marketplace.teamplay.siemens.com/)
- [Partner Program](https://www.siemens-healthineers.com/en-us/digital-health-solutions/digital-marketplace-for-partners)
- [Digital Health Platform (teamplay)](https://www.siemens-healthineers.com/digital-health-solutions/digital-solutions-overview/service-line-managment-solutions/teamplay)
- [GitHub Org](https://github.com/Siemens-Healthineers)
- [Press](https://www.siemens-healthineers.com/press)
- [Investor Relations](https://www.siemens-healthineers.com/investor-relations)
- [Vocabulary](vocabulary/siemens-healthineers-vocabulary.yml)
- [JSON-LD Context](json-ld/siemens-healthineers-context.jsonld)

## Notable Absences

- No public OpenAPI / Swagger specifications — the API catalog is gated behind a teamplay developer account at `devportal.us.api.teamplay.siemens-healthineers.com`.
- No public SDKs in language package registries from the Siemens-Healthineers GitHub org. The 13 public repos are mostly upstream contributions (SW360, fossology, NUnit) plus internal tooling (K2s, SHIELD-DAVE, ETWAnalyzer).
- No public pricing page for teamplay or Digital Marketplace partner subscriptions.
- No public status page for the teamplay digital health platform.
- No public changelog or RSS feed for API or platform releases.
- No webhooks documentation publicly visible.
- No published rate-limit policy.
- The Frontier Development Kit is referenced but not distributed via a public download or package registry — access is gated through the syngo.via Frontier program.

## Maintainers

- Kin Lane (kin@apievangelist.com)
