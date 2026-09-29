# Awesome-Cloud-Carbon-Accounting

# Top Cloud Carbon Accounting Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on GHG Emissions Calculation, Scope 1/2/3 Reporting, Regulatory Compliance & Supply Chain Engagement*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Carbon Accounting**. These tools help organizations measure, manage, and report greenhouse gas (GHG) emissions across Scopes 1, 2, and 3, comply with regulatory frameworks like CSRD, ISSB, and CDP, and drive decarbonization initiatives.

**Examples** include Microsoft Cloud for Sustainability, IBM Envizi, Watershed, Sweep, Persefoni, Normative, Greenly, Plan A, Emitwise, and SpheraCloud (the category leaders).

**Open-source emphasis**: Cloud carbon accounting is a **commercially dominated category**. Leading platforms like Watershed, Persefoni, and Sweep are proprietary SaaS. However, a **small but growing open-source ecosystem** exists, led by **CarbonInk** (local-first desktop GHG accounting with AI bill extraction), **GreenOps** (full-stack Django/React ESG platform), **OpenGHG** (transparent, auditable carbon calculator), and **SCOOP** (IEEE-backed metrology-grade carbon accounting). This section documents these self-hostable solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Cloud for Sustainability](https://www.microsoft.com/en-us/sustainability/cloud)**
  Microsoft's enterprise sustainability platform built on Dynamics 365 and Power Platform. Provides carbon accounting across Scopes 1-3, standardized data models, real-time sustainability data capture, and integration with Microsoft's broader ecosystem. Offers published tenant pricing .

- **[IBM Envizi](https://www.ibm.com/products/envizi)**
  Enterprise ESG data management and carbon accounting platform. Strong for asset-heavy industrial companies with complex data pipelines, metering, and CSRD governance. Named a Leader in Verdantix Green Quadrant 2026 .

- **[Watershed](https://watershed.com/)**
  Climate-first enterprise carbon accounting platform. Manages 3 gigatonnes of emissions. Features AI-assisted disclosure drafting, CDP API submission, strong data ingestion and quality controls, and broad ESG metric support. Pricing is quote-based. Named a Leader in Verdantix Green Quadrant 2026 .

- **[Sweep](https://www.sweep.net/)**
  Sustainability intelligence platform with "report once, file everywhere" multi-framework mapping (CSRD, ISSB, GRI, CDP, SASB, TCFD, SB 253/261, UK SRS). Audit-ready filing with full data lineage, direct auditor access, supplier interfaces for Scope 3 data collection. Named a Leader in Verdantix Green Quadrant 2026 .

- **[Persefoni](https://www.persefoni.com/)**
  Climate management and accounting platform. Best free on-ramp with Pro covering Scopes 1-3. Strong financed emissions capabilities (PCAF-aligned). Named in IDC MarketScape 2026 .

- **[Normative](https://normative.io/)**
  Integrated carbon accounting platform. Strong for supplier engagement, product carbon footprint (PCF) management, and financed emissions tracking. Named in IDC MarketScape 2026 .

- **[Greenly](https://greenly.earth/)**
  User-friendly carbon accounting and product lifecycle assessment (LCA) tools. Pricing starts at $1,950/year. Good for smaller organizations early in their sustainability journey .

- **[Plan A](https://plana.earth/)**
  Carbon accounting platform for EU decarbonization-first teams. Climate-first with regulatory mapping for CSRD/ISSB .

- **[Emitwise](https://www.emitwise.com/)**
  Climate-first carbon accounting platform. Focuses on supply chain emissions and decarbonization planning .

- **[SpheraCloud](https://sphera.com/)**
  Enterprise ESG and carbon management platform. Strong product carbon footprinting capabilities for complex industrial supply chains. Named a Leader in Verdantix Green Quadrant 2026 .

## Open-Source GitHub Projects

- **[CarbonInk](https://github.com/lxzxl/carbonink)**
  **Free, open-source, local-first GHG carbon accounting for desktop.** Import bills, AI extracts activity data, produces ISO 14064-1 inventory report entirely on your own machine. **No account, no cloud, no subscription.** Features: inventory with Scope 1/2/3, AI extraction from utility bills/fuel receipts/freight/travel, questionnaires for customer disclosures and supplier Scope 3 data, one-click ISO 14064-1 PDF report, and MCP server exposing inventory to Claude/Cursor. **MIT License**. macOS + Windows .

- **[GreenOps](https://github.com/cherryaugusta/greenops-carbon-accounting-platform)**
  **Full-stack ESG carbon accounting platform.** Django 5.2 + Django REST Framework + React + TypeScript + Docker. Features: employee carbon logging (travel and energy), automatic CO₂e calculation using emission factors, manager approval workflow via Django Admin, **full audit trail** (django-simple-history), JWT-secured API, Swagger UI, dashboard with charts and KPI summaries, multi-step validated form, and drag-and-drop report builder. PostgreSQL + Redis. **Open source** .

- **[OpenGHG](https://github.com/mindsongreen/OpenGHG)**
  **Transparent, auditable carbon footprint calculator.** Key principles: separation of data domains (activity data, emission factors, conversions, parameters), federated database architecture allowing customer-hosted sensitive data, explicit unit and pair-of-units algebra, no black-box calculations, full traceability from input to results. PHP backend (PDO, PostgreSQL), HTML/JavaScript frontend. **Open source** .

- **[SCOOP Carbon Accounting Project](https://github.com/scoop-carbon)**
  **Open-source carbon accounting that uses metrology discipline with the rigor of financial reporting frameworks.** Supports IEEE standards efforts including P7802 and P3469, translating scientific principles into practical projects. Presented at IEEE SusTech 2026 .

- **[OpenClimate (Open-Earth-Foundation)](https://github.com/Open-Earth-Foundation)**
  Open-source climate data infrastructure. Repositories include: **ClimateTRACE_C40** (comparing emissions estimates to GPC inventory data), **OpenClimate-pyclient** (Python client), **OpenClimate-Schema** (actor emissions schema), **intake-OpenClimate** (catalog for actor emissions), and **blockchain-carbon-accounting** (fork of Hyperledger Labs). **Open source** .

- **[moja global FLINT](https://github.com/moja-global/FLINT)**
  **Full Lands Integration Tool (FLINT)** for measuring, reporting, and verifying (MRV) greenhouse gas emissions from land use. Government-backed open-source tool for agriculture, forestry, and other land use (AFOLU) carbon accounting. Includes Generic Carbon Budget Model (GCBM). **Open source** .

### Additional Strong Open-Source Options

- **Desktop/Local-First**: **CarbonInk** (MIT, AI bill extraction, ISO 14064-1, offline) .
- **Full-Stack Platforms**: **GreenOps** (Django/React, audit trails, report builder) .
- **Transparent Calculators**: **OpenGHG** (explicit formulas, federated databases, full traceability) .
- **Standards-Based**: **SCOOP** (IEEE metrology discipline, P7802/P3469) .
- **Climate Data Infrastructure**: **OpenClimate** (ClimateTRACE, blockchain carbon accounting) .
- **Land Use MRV**: **moja global FLINT** (government-backed, AFOLU carbon accounting) .

**Frameworks for building custom systems**: Combine **CarbonInk** for local-first desktop GHG accounting with AI bill extraction, **GreenOps** for full-stack ESG reporting with audit trails, **OpenGHG** for transparent and auditable calculations, and **SCOOP** for metrology-grade standards compliance. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Carbon accounting platforms handle sensitive emissions and supply chain data; ensure compliance with GHG Protocol, ISO 14064, CSRD, ISSB, and relevant regional disclosure regulations.
- **Open-source reality**: The open-source ecosystem for carbon accounting is **developing but not yet equivalent to commercial platforms**. **CarbonInk** provides local-first desktop GHG accounting with AI extraction . **GreenOps** delivers full-stack ESG reporting . **OpenGHG** offers transparent calculations . **SCOOP** brings metrology-grade standards . However, commercial platforms (Watershed, Sweep, Persefoni, IBM Envizi) provide deeper multi-framework mapping, supplier engagement at scale, and audit-ready workflows that open-source alternatives cannot match without significant institutional investment .

---

**Made for sustainability managers, ESG analysts, carbon accountants, and corporate climate teams.**
Let's make carbon accounting more open, transparent, and auditable.
