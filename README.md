# Awesome-Enterprise-Asset-Management-EAM

# Top Enterprise Asset Management (EAM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Asset Lifecycle Management, Maintenance Operations & Reliability Engineering*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Asset Management (EAM)**. These tools enable organizations to manage the complete lifecycle of physical assets—from acquisition and deployment through maintenance, performance monitoring, and retirement—while optimizing costs, extending asset life, and ensuring regulatory compliance.

**Examples** include ServiceNow Enterprise Asset Management, IBM Maximo, SAP EAM, Infor EAM (HxGN EAM), IFS Cloud, Brightly Asset Essentials, Oracle Maintenance Cloud, MaintainX, UpKeep, and Fiix (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted CMMS/EAM platforms and maintenance management systems—ideal for maintenance teams, facility managers, and organizations building sovereign asset management infrastructure without per-asset or per-user licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Enterprise Asset Management](https://www.servicenow.com/)**  
  Enterprise EAM on the Now Platform covering the complete physical asset lifecycle from planning and acquisition through maintenance and retirement; features Enterprise Asset Workspace for full traceability, linear asset management for roadways/pipelines/cables, interactive indoor maps for asset visualization, stockroom operations with auto-replenishment rules, and integration with Field Service Management for seamless maintenance execution .

- **[IBM Maximo Application Suite](https://www.ibm.com/products/maximo)**  
  Unified asset and facilities management solution combining EAM, Asset Performance Management (APM), and Asset Investment Planning (AIP) with embedded AI; supports predictive maintenance via sensor data, visual inspection with AI-powered image analysis from cameras and drones, and specialized portfolios for facilities, energy, and data center infrastructure .

- **[SAP EAM](https://www.sap.com/)**  
  Enterprise asset management integrated with SAP S/4HANA and ERP; features closed-loop integration between asset strategy and maintenance execution, RCM/FMEA reliability engineering per SAE JA1012 standards, IoT connectivity for condition-based maintenance, and AI-assisted visual inspection for defect detection . The 2026 releases add barcode scanning for unplanned material movements and work permit visibility directly within the Perform Maintenance Jobs app .

- **[Infor EAM (HxGN EAM)](https://hexagon.com/)**  
  Hexagon's asset management platform (formerly Infor EAM) with 30+ years of development; features EAM Digital Work for self-service mobility with customizable interfaces, Constraint Optimizer leveraging ML for complex scheduling decisions, and availability in both cloud and on-premises deployments .

- **[IFS Cloud](https://www.ifs.com/)**  
  Enterprise asset management within IFS Cloud with capabilities for optimizing offshore maintenance operations between shore and offshore assets, including synchronization of business-critical data across unreliable communication links .

- **[Brightly Asset Essentials](https://www.brightlysoftware.com/)**  
  Cloud-based CMMS for facilities and maintenance teams; features centralized asset tracking across portfolios, streamlined work order management, preventive maintenance scheduling, and optional Smart Assets IoT module for remote monitoring and predictive maintenance .

- **[Oracle Maintenance Cloud](https://www.oracle.com/)**  
  Maintenance management within Oracle Cloud ERP with work requirement forecasting, asset inclusion methods, and interval-based scheduling; the 21D update adds historical completion dates and intervals for improved forecast accuracy, plus enhanced item picker with autosuggest and multi-field search .

- **[MaintainX](https://www.maintainx.com/)**  
  Mobile-first maintenance management platform with 5,000+ business customers; features customizable work orders and procedures with conditional logic, parts inventory management, safety inspections, and a unified mobile app for frontline teams .

- **[UpKeep](https://upkeep.com/)**  
  CMMS platform with 4,000+ teams using it for work orders, preventive maintenance, asset management, and parts inventory; features Nova AI assistant for autonomous data cleanup and smart scheduling, voice-to-work-order capabilities, and IoT sensor integration for predictive maintenance .

- **[Fiix](https://www.rockwellautomation.com/)**  
  Rockwell Automation's cloud-based CMMS with 4,500+ companies; features work order management, preventive maintenance, asset tracking, parts inventory, and AI-powered predictive insights; integrates with FactoryTalk Optix for condition-based maintenance triggered by real-time equipment data .

## Open-Source GitHub Projects

- **[Atlas CMMS](https://github.com/atlas-cmms/cmms)**  
  Leading open-source self-hosted CMMS for web and mobile (GPLv3 with commercial license for white-labeling/SSO); features work order creation and tracking with time logging and priority management, preventive maintenance automation, asset tracking with downtime and cost history, inventory management with stock alerts, purchase order automation, analytics dashboards, and Google Maps location integration; Java Spring Boot backend, React/TypeScript frontend, React Native mobile app; Docker-deployable with ~345 GitHub stars .

- **[CalemEAM](https://www.calemeam.com/)**  
  Enterprise-scale open-source EAM (GPLv2) with modular design for asset tracking, work orders, preventive maintenance, and purchasing integration; supports multi-site operations, role-based access, and analytics dashboards; used by medium to large manufacturers, utilities, and facilities groups .

- **[openMAINT](https://www.openmaint.org/)**  
  Open-source facility and plant asset management (AGPLv3) built on the CMDBuild framework; includes asset registry, work orders, energy tracking, document management, and IoT sensor connectors; used by industrial sites and public infrastructure organizations across Europe .

- **[BaseEAM](https://github.com/basemap/basemap)**  
  Open-source EAM (Apache 2.0) for asset lifecycle management with financial insight; features asset accounting, condition monitoring, capital project tracking, REST APIs, and cloud deployment support; used by manufacturing and energy companies implementing digital asset strategies .

- **[ERPNext (Asset Module)](https://github.com/frappe/erpnext)**  
  Integrated asset module within ERPNext covering procurement, depreciation, maintenance scheduling, and insurance; combines accounting with maintenance cost tracking; GPLv3 licensed and ideal for SMEs integrating asset and production management in one system .

- **[Snipe-IT](https://github.com/grokability/snipe-it)**  
  Lightweight IT and equipment asset management platform adaptable for manufacturing equipment and tools; tracks location, owner, warranty, and check-in/check-out history; well-suited for technical services and maintenance departments needing simple asset tracking without full CMMS complexity .

- **[SuperCMMS](https://github.com/SuperCMMS/Open-Source-CMMS)**  
  Free and open-source CMMS backend (frontend intentionally out of scope so organizations can build custom UIs); features asset management, work orders, preventive/predictive/corrective maintenance, checklists, QR codes, inventory management, and central document repository; currently in rapid development with production readiness pending .

- **[GMAO Factory](https://github.com/jsbsan/GMAO-FACTORY)**  
  Lightweight CMMS designed for offline-first/air-gapped environments (Python Flask + SQLite); features executive dashboard with KPIs, inventory management with attachment support, preventive maintenance auto-generation, corrective maintenance workflows, visual calendar/schedule views, role-based access control, and audit logging; suitable for workshops, property communities, and industrial SMEs .

- **[Microsoft Dynamics 365 Asset Management Mobile (Open Source)](https://github.com/microsoft/scmsamples-EnterpriseAssetManagement)**  
  MIT-licensed open-source release of Microsoft's Asset Management mobile app (June 2026); provides the same functionality as the original app with full customization freedom; build from source to avoid Microsoft update overwrites; suitable for organizations using Dynamics 365 Supply Chain Management and needing field work order management .

### Additional Strong Open-Source Options

- **owiin-ops** — Free and open-source Enterprise Asset Management alternative to IBM Maximo (Java); smaller project with limited recent activity but demonstrates open-source EAM ambitions .
- **Caldera CMMS (formerly EasyMaint)** — GPL-licensed CMMS with cost tracking, maintenance history, and spare-part management; suitable for SMEs migrating from spreadsheets to structured maintenance .
- **Eam360 (Community Edition)** — Mobile-first maintenance and inspection workflows with QR/barcode scanning and offline work-order functionality; designed for field technicians in distributed facilities .

**Frameworks for building custom systems**: Combine **Atlas CMMS** for a modern, Docker-deployable CMMS with web and mobile apps, **CalemEAM** or **BaseEAM** for enterprise-scale asset lifecycle management with financial tracking, and **GMAO Factory** for air-gapped/offline-first deployments in a self-hosted EAM stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- EAM platforms handling asset and maintenance data must comply with applicable safety regulations, industry standards, and organizational governance policies; maintenance records may be subject to audit and regulatory retention requirements.
- Self-hosted open-source solutions vary significantly in scope—Atlas CMMS provides a production-ready CMMS with mobile apps, while CalemEAM and BaseEAM offer broader EAM capabilities; full enterprise EAM with financial integration and multi-site consolidation typically requires commercial platforms or significant customization.
- Verify license terms for commercial use; Atlas CMMS uses GPLv3 with a commercial option for white-labeling/SSO, CalemEAM uses GPLv2, openMAINT uses AGPLv3, BaseEAM uses Apache 2.0, and ERPNext uses GPLv3.

---

**Made for maintenance managers, facility directors, reliability engineers, and asset operations teams.**  
Let's make enterprise asset management more open, maintainable, and lifecycle-aware.
