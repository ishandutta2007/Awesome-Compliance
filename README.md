# Awesome-Compliance

# Top Compliance Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Compliance Automation, SOC 2, ISO 27001, Evidence Collection, Continuous Control Monitoring & GRC*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Compliance** (especially compliance automation and continuous control monitoring). These systems connect to cloud, identity, HR, and code systems to collect evidence, map controls to frameworks, and prepare organizations for audits (SOC 2, ISO 27001, GDPR, HIPAA, and more).

**Examples** include Vanta, Drata, Secureframe, Thoropass, Sprinto, Hyperproof, OneTrust, AuditBoard, LogicGate, and Scytale (the category leaders).

**Open-source emphasis**: Full compliance automation platforms are largely commercial, but growing open alternatives exist—**Openlane**, **Continuous Compliance Framework (OSCAL-based)**, **OCEAN**, and related policy/evidence tooling. This section expands those while remaining realistic about the commercial gap for auditor-ready automation.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Vanta](https://www.vanta.com/)**  
  Leading compliance automation platform for SOC 2, ISO 27001, and many other frameworks—integrations, continuous monitoring, trust center, and auditor workflows.

- **[Drata](https://drata.com/)**  
  Compliance automation and GRC platform with strong control mapping, evidence collection, risk features, and multi-framework support.

- **[Secureframe](https://secureframe.com/)**  
  Compliance automation platform covering SOC 2, ISO, CMMC, and related frameworks with evidence automation and remediation support.

- **[Thoropass](https://thoropass.com/)**  
  Compliance platform that combines software with audit services for SOC 2 and other frameworks.

- **[Sprinto](https://sprinto.com/)**  
  Compliance automation platform focused on fast setup, engineering-friendly workflows, and multiple frameworks (SOC 2, ISO, GDPR, and more).

- **[Hyperproof](https://hyperproof.io/)**  
  Compliance and audit management platform with broad framework coverage, evidence, and program workflows.

- **[OneTrust](https://www.onetrust.com/)**  
  Broad GRC and privacy platform with compliance, risk, and trust capabilities across many regulatory domains.

- **[AuditBoard](https://www.auditboard.com/)**  
  Enterprise audit, risk, and compliance platform used for internal audit, SOX, and broader GRC programs.

- **[LogicGate](https://www.logicgate.com/)**  
  GRC platform (Risk Cloud) for risk, compliance, and control management with configurable workflows.

- **[Scytale](https://scytale.ai/)**  
  Compliance automation platform aimed at startups and growing companies preparing for SOC 2 and related audits.

## Open-Source GitHub Projects
- **[Openlane](https://github.com/theopenlane/core)**  
  Open-source compliance automation platform for SOC 2, GDPR, ISO 27001, NIST 800-53, and more—policies, controls, evidence, registry, and integrations (alternative to Vanta/Drata-style platforms).

- **[Continuous Compliance Framework / Compliance Framework](https://github.com/compliance-framework)**  
  Open-source suite for automated compliance testing and reporting built around OSCAL concepts (controls, assessments, attestations).

- **[OCEAN](https://github.com/grcengineering/OCEAN)**  
  Open-source CLI and library for evidence acquisition, active control testing, normalization, and continuous compliance monitoring.

- **[OSCAL (NIST)](https://github.com/usnistgov/OSCAL)**  
  Open Security Controls Assessment Language—standard formats for catalogs, profiles, implementations, and assessment results used by open and commercial tools.

- **[OpenControl](https://github.com/opencontrol)**  
  Earlier open-source compliance-as-code approach for documenting and validating controls (still referenced in compliance-as-code discussions).

- **[Policy-as-code open tools (OPA, Checkov, etc.)](https://github.com/open-policy-agent/opa)**  
  Open policy engines and IaC scanners used to enforce and evidence technical controls that map to compliance frameworks.

- **[CISO Assistant and open GRC experiments](https://github.com/)**  
  Community and open GRC/compliance projects that provide self-hosted program and control tracking options.

- **[Evidence collection open scripts and connectors](https://github.com/)**  
  Community connectors that pull configuration and identity evidence from AWS, GitHub, Okta, and similar systems for compliance packs.

- **[Awesome compliance resource lists](https://github.com/theopenlane/awesome-compliance)**  
  Curated open lists of compliance frameworks, libraries, and tooling.

- **[Documentation and open compliance playbooks](https://theopenlane.io/)**  
  Guides for running continuous control monitoring and evidence pipelines with open-source stacks.

### Additional Strong Open-Source Options
- Deploying **Openlane** for a full open compliance program system of record (people, systems, policies, controls, evidence).
- Using **OSCAL + Continuous Compliance Framework** for standards-aligned assessment and reporting.
- Combining **OCEAN** or custom collectors with policy-as-code tools for technical control evidence.
- Accepting that auditor networks, polished trust centers, hundreds of native integrations, and managed continuous monitoring still favor commercial platforms (Vanta, Drata, Secureframe, Sprinto, Hyperproof, etc.).
- Focusing open-source efforts on transparency, data ownership, and avoiding lock-in of compliance evidence.

**Frameworks for building custom systems**: Define controls in OSCAL or Openlane → collect evidence via APIs and policy-as-code → store attestations → generate reports for auditors. Suitable for engineering-led and security teams. Most startups and enterprises preparing for SOC 2/ISO still adopt commercial compliance automation for speed and auditor familiarity.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Compliance tools support—but do not replace—organizational responsibility for controls and audits. Open-source deployments require careful mapping to frameworks and auditor acceptance. This list is not legal or audit advice.

---
**Made for security, compliance, and open-source GRC advocates.**
Let's keep trust programs continuous, evidence-based, and as open as practical.
