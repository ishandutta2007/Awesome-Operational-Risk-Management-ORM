# Awesome-Operational-Risk-Management-ORM

## Top Operational Risk Management (ORM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Risk Registers, Control Assessments & Operational Resilience*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Operational Risk Management (ORM)**. These tools enable organizations to identify, assess, prioritize, and mitigate operational risks—from process failures and third-party disruptions to compliance breaches and cyber incidents—through structured risk registers, control frameworks, and continuous monitoring.



**Examples** include ServiceNow Operational Risk Management, MetricStream, Archer, Workiva, LogicGate, Riskonnect, Protecht, SAI360, Camms, and Resolver (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted GRC and risk management—ideal for organizations building sovereign operational risk infrastructure without per-seat or per-module licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Operational Risk Management](https://www.servicenow.com/)**  

  Enterprise ORM on the Now Platform integrated with Integrated Risk Management (IRM); provides risk registers, control assessments, loss event tracking, key risk indicators (KRIs), and regulatory change management with workflow automation and CMDB context for operational impact analysis.



- **[MetricStream](https://www.metricstream.com/)**  

  AI-powered GRC platform recognized as a Category Leader across all seven GRC categories by Chartis Research; features continuous risk sensing, AI assistants for risk and compliance workflows, autonomous evidence gathering, and outcome assurance for remediation validation.



- **[Archer](https://www.archerirm.com/)**  

  Enterprise GRC platform with integrated risk register, quantitative risk insights with dollar-value exposure, third-party risk governance, and audit-ready evidence with timestamped trails; serves 1,500+ customers across 48 countries including 50% of Fortune 500.



- **[Workiva](https://www.workiva.com/)**  

  Financial compliance and SEC reporting platform with ICFR (internal controls over financial reporting) and SOX compliance capabilities; provides a single source of truth with data traceability and streamlined audit interactions.



- **[LogicGate](https://www.logicgate.ai/)**  

  AI GRC platform with GRC Agents for ERM, TPRM, AI Governance, and Business Continuity Management; features Automated Control Testing with detailed rationale, Bulk Record Linking, GRC Lifecycle Management for production-to-development syncing, and upcoming MCP Server Access for natural language Risk Cloud queries.



- **[Riskonnect](https://www.riskonnect.com/)**  

  Integrated risk management platform covering ERM, operational risk, compliance, audit, and business continuity with a unified risk register and reporting dashboards.



- **[Protecht](https://www.protechtgroup.com/)**  

  Risk management and compliance platform with operational risk modules, control assurance, incident management, and regulatory compliance tracking for financial services and enterprises.



- **[SAI360](https://www.sai360.com/)**  

  GRC and compliance platform with operational risk management, control testing, regulatory change management, and ethics/compliance training integration.



- **[Camms](https://www.cammsgroup.com/)**  

  Integrated risk, compliance, and strategy management platform with operational risk registers, control assessments, and enterprise-wide reporting for public sector and regulated industries.



- **[Resolver](https://www.resolver.com/)**  

  Risk intelligence platform with operational risk management, incident tracking, control testing, and corporate security capabilities unified in a single system.



## Open-Source GitHub Projects



- **[Probo](https://github.com/getprobo/probo)**  

  Self-hostable GRC platform (ISC licensed) covering the full lifecycle: **risk register with inherent/residual scoring and treatment strategies (mitigate, accept, avoid, transfer)**, control library with maturity levels, vendor risk, data privacy (DPIA/TIA), access reviews, audit programs, and document approval workflows; exposes 270+ MCP tools for AI agent automation, `prb` CLI with 44+ command groups, GraphQL API, and n8n community node; Docker-deployable .



- **[Cairn](https://github.com/frousselet/cairn)**  

  Self-hosted GRC platform (AGPL-3.0) with **risk management using ISO 27005 and EBIOS RM methodologies**, a three-level register, treatment plans, and formal risk acceptance; also covers governance (ISO 27001 context), assets with CIA valuation and dependency mapping, compliance frameworks with inter-framework mappings, incidents with sealed evidence and statutory notification clocks, and a public Trust Center; every feature is API-accessible via REST and built-in MCP server; optional AI supports Mistral, OpenAI, Claude, or local Ollama .



- **[MONARC](https://github.com/monarc-project/MonarcAppFO)**  

  Open-source risk analysis method and platform (AGPL-3.0) developed by CASES Luxembourg; capitalizes on risk analyses from similar business contexts to make structured risk assessment accessible to organizations of all sizes; includes comprehensive REST API for managing risk analyses, assets, threats, vulnerabilities, and operational risks; supports Docker deployment and provides a MOSP (MONARC Objects Sharing Platform) for reusable risk objects .



- **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)**  

  Open-source GRC platform for cybersecurity management with **risk documentation, control creation, and framework mapping** to ISO 27001, NIST CSF, SOC 2, and custom frameworks; features reusable control objects, assessment tracking, and reporting views; Docker-based self-hosted deployment with role-based access controls; community-contributed framework library with APIs, n8n, MCP, and Kafka integrations .



- **[SimpleRisk](https://www.simplerisk.com/)**  

  Free, open-source risk management platform for identifying, assessing, prioritizing, and tracking security and operational risks; provides risk mitigation tracking, security controls and compliance management, and centralized visibility into organizational risks; Docker-deployable .



- **[RiskLab](https://github.com/prashant-fintech/risklab)**  

  Modular, plugin-based financial risk management platform (MIT) with an **operational risk module using Loss Distribution Approach (LDA)**; includes VaR/ES calculation, stress testing, and portfolio analytics; Python 3.12+ with FastAPI backend and Streamlit UI .



- **[Risk Shield](https://github.com/cary-williams/risk-shield)**  

  Web-based risk register generator for structured risk assessments; documents risks using likelihood and impact scoring, distinguishes inherent vs. residual risk with control effectiveness, and visualizes risk through charts and heat maps; built with Vite/React/TypeScript and deployable on Vercel or GitHub Pages .



### Additional Strong Open-Source Options



- **evidentia** — Open-source GRC tool for gap analysis, risk statements, evidence collection, and compliance automation with a web UI .

- **CompliEdge** — Django-based GRC system with risk identification/scoring, compliance checklists, policy management, and AI-driven insights; includes RBAC, 2FA, and audit logs .

- **Risk Register Templates** — CSV/Excel templates and lightweight web apps for basic risk tracking when full GRC platforms are overkill .



**Frameworks for building custom systems**: Combine **Probo** for full GRC lifecycle with risk scoring and treatment tracking, **Cairn** for ISO 27005/EBIOS RM-aligned risk assessment with regulatory compliance mapping, **MONARC** for context-based risk capitalization across similar business scenarios, and **CISO Assistant** for cybersecurity framework alignment in a self-hosted operational risk management stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Operational risk platforms handling risk assessments and loss data must comply with applicable regulations (Basel III, Solvency II, DORA, etc.) and organizational governance policies.

- Self-hosted open-source solutions vary in ORM depth—Probo and Cairn provide strong foundational risk registers and control tracking, but may require customization for industry-specific regulatory calculations and quantitative risk modeling.

- Verify license terms for commercial use; Probo uses ISC, Cairn uses AGPL-3.0, MONARC uses AGPL-3.0, and RiskLab uses MIT.



---



**Made for risk managers, compliance officers, operational resilience teams, and GRC analysts.**  

Let's make operational risk management more open, structured, and audit-ready.
