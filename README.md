# Awesome-Procurement-Service-Management

## Top Procurement Service Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Intake-to-Pay Workflows, Guided Buying & Procurement Help Desk Automation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Procurement Service Management**. These tools enable organizations to streamline how employees request goods and services, automate procurement help desk inquiries, enforce spending policies at the point of request, and provide end-to-end visibility from intake through payment.



**Examples** include ServiceNow Procurement Service Management, Coupa, SAP Ariba, Ivalua, Jaggaer, Zip, Airbase, Tipalti, GEP SMART, and Procurify (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted procurement workflow automation and vendor management—ideal for organizations building sovereign procurement operations infrastructure without per-transaction or per-seat licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Procurement Service Management](https://www.servicenow.com/)**  

  Procurement service delivery platform on the Now Platform with a unified employee portal (ShoppingHub) for catalog and non-catalog purchases, virtual agent for common inquiry deflection, intelligent task orchestration across requisitions and approvals, and real-time ERP integration for end-to-end visibility from request to payment .



- **[Coupa](https://www.coupa.com/)**  

  AI-native total spend management platform with procurement, invoicing, and supply chain unified; features prescriptive AI insights trained on $8T+ in transactional spend, guided buying for direct and indirect spend, intelligent fraud detection, and pre-built integrations with Amazon Business .



- **[SAP Ariba](https://www.sap.com/)**  

  Comprehensive source-to-pay suite with a unified intake entry point for business users, AI-powered Joule assistant for guided decision-making, intelligent sourcing automation, and open APIs for integration with SAP and third-party ERP systems .



- **[Ivalua](https://www.ivalua.com/)**  

  Cloud-based source-to-pay platform trusted by 500+ organizations; highly configurable for non-standard procurement methods, with comprehensive eRFX support and analytical tools for sourcing oversight, though Gartner reviewers note UI/UX can feel dated and certain functionalities require maturing .



- **[Jaggaer](https://www.jaggaer.com/)**  

  Procurement orchestration platform with 1,000+ ERP/app connectors, 600+ REST API endpoints, ISO 27001/27017/27018 certification, and AI Management System ISO 42001 certified; supports 28+ languages and 70+ countries with pre-built accelerators for SAP, Oracle, and Workday .



- **[Zip](https://zip.com/)**  

  Intake-to-pay and procurement orchestration platform providing an intuitive starting point for employee purchase and vendor requests; centralizes approval workflows and provides visibility across business spend, though Gartner reviewers note limited flexibility for complex enterprise workflow customization .



- **[Airbase](https://www.airbase.com/)**  

  Procure-to-pay solution for mid-market and larger organizations (now part of Paylocity) with guided procurement intake, spend analytics, vendor management, AP automation, expense management, and corporate cards in a unified platform; Forrester TEI study reports 272% ROI over three years .



- **[Tipalti](https://tipalti.com/)**  

  AI-powered accounts payable automation with procurement and spend controls; processes invoices in ~2 minutes with line-level AI capture, supports payments to 200+ countries in 120 currencies, and includes built-in tax compliance (W-9, W-8, VAT, DAC7) .



- **[GEP SMART](https://www.gep.com/)**  

  End-to-end AI-powered procurement software covering spend visibility, sourcing (RFx, e-Auction, auto-scoring), contract management with AI-based risk assessment, supplier performance dashboards, and procure-to-pay with guided buying and autonomous procurement capabilities .



- **[Procurify](https://www.procurify.com/)**  

  Agentic procurement platform connecting requests, POs, invoices, and payments; features structured intake with approval routing, product catalogs with PunchOut shopping, automated invoice matching, and spend analytics dashboards .



## Open-Source GitHub Projects



- **[VendSync (BidFlow)](https://github.com/RavalMunjal/VendSync)**  

  Full-stack Procurement & Vendor Management ERP (React/Node.js/MongoDB) digitizing the entire purchasing lifecycle from RFQ creation to invoice generation; features role-based access (Admin, Manager, Procurement Officer, Vendor), vendor portal for independent quotation submission, side-by-side quotation comparison with lowest-price highlighting, structured approval workflows, auto-generated POs and invoices with PDF export, and real-time analytics dashboards .



- **[mcp-procurement](https://github.com/zavora-ai/mcp-procurement)**  

  AI-powered procurement engine with 37 MCP tools covering the source-to-pay lifecycle: supplier management, RFQ creation and comparison, purchase orders with approval gates, contracts, goods receipt, three-way matching, budgets, and diversity tracking; includes intelligence tools for supplier risk scoring, price benchmarking, demand forecasting, and negotiation briefs.



- **[e-procure](https://github.com/Gichure/e-procure)**  

  Spring Boot microservices-based e-procurement system with modules for purchase requisition, purchase orders, vendor management, bid management, invoice management, payment processing, and BPMN workflow via Camunda; includes Kafka messaging, Keycloak authentication, and Docker/Kubernetes deployment support.



- **[OpenTradeIntel](https://pypi.org/project/opentradeintel/)**  

  Open-source procurement and B2B sourcing intelligence engine that queries EU public procurement notices from the TED Search API, normalizes them into typed tenders, and ranks them against local supplier catalogs with deterministic 0–100 matching scores; includes CLI, FastAPI, and MCP adapter for local, offline-capable tender discovery.



### Additional Strong Open-Source Options



- **GitHub `procurement-system` topic** — 37+ public repositories covering AI-powered procurement intelligence agents, multi-agent procurement collaboration platforms, and transparent tendering foundations for public-sector workflows.

- **AI-powered procurement intelligence agents** — Community projects with local LLM integration, document OCR, vendor scoring, and web research for analyzing bids privately.

- **aribaiq** — Python library for AI-powered procurement analytics with supplier intelligence scoring, spend optimization signals, ESG-weighted evaluation, and GenAI-ready prompt generation.



**Frameworks for building custom systems**: Combine **VendSync** for full RFQ-to-invoice workflow with vendor portal, **mcp-procurement** for AI-assisted source-to-pay orchestration with supplier intelligence, and **e-procure** for microservices-based enterprise procurement with BPMN workflows in a self-hosted procurement service management stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Procurement platforms handling supplier and financial data must comply with applicable regulations (anti-corruption laws, public procurement rules, data privacy requirements).

- Self-hosted open-source solutions require proper security hardening, ERP/finance integration planning, and workflow customization for approval gates and compliance controls.

- Verify license terms for commercial use; VendSync is open-source (hackathon project), mcp-procurement is an open-source MCP server, and e-procure uses MIT.



---



**Made for procurement teams, P2P automation engineers, finance operations, and supply chain analysts.**  

Let's make procurement service management more open, guided, and compliant.
