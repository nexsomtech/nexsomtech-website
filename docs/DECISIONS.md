# Nexsom Technology Website
# Website Decisions Register

**Document ID:** NT-WEB-DEC-001  
**Version:** 1.1.0  
**Status:** Active  
**Effective Date:** 12 July 2026  
**Last Updated:** 27 September 2026  
**Product:** Nexsom Technology Website  
**Owner:** Nexsom Technology  
**Classification:** Product Governance  
**Repository:** `nexsomtech-website`  
**Source Format:** Markdown  

---

## 1. Purpose

This register records the approved decisions that govern the design, architecture, development, deployment, maintenance, and future expansion of the Nexsom Technology website.

It contains only website-specific decisions.

Company-level decisions, including corporate identity, company purpose, brand governance, management-system rules, service architecture, and enterprise technology direction, are maintained separately in:

> `nexsom-company-governance/docs/DECISIONS.md`

The website must comply with approved company governance and corporate standards.

---

## 2. Decision Status Definitions

- **Active:** The decision is currently approved and applicable.
- **Superseded:** The decision has been replaced by a later approved decision.
- **Retired:** The decision is no longer applicable but remains recorded for traceability.
- **Planned:** The decision is approved in principle but has not yet been fully implemented.

Approved decisions must not be deleted solely because they have been replaced.

Superseded and retired decisions must remain recorded with the relevant replacement reference.

---

# Website Decisions

## Decision WD-001 — Website Hosting and Deployment

**Legacy Reference:** Decision 006  
**Status:** Active  

**Decision:**  
Cloudflare Pages shall be used as the current website hosting and deployment platform.

Cloudflare may also provide:

- DNS integration
- SSL
- Security controls
- Performance services
- Deployment integration
- Edge delivery

**Reason:**  
Cloudflare provides suitable free hosting, automated deployment, SSL, security, and performance for the current website stage.

**Expected Benefit:**  
Provides a reliable and cost-effective deployment environment while Nexsom develops its business and technical capacity.

**Governance Note:**  
Cloudflare is a current service provider. The website must not become structurally dependent on Cloudflare-specific features that prevent practical migration.

---

## Decision WD-002 — Source Repository

**Status:** Active  

**Decision:**  
The official website source repository is:

> `nexsomtech-website`

The repository shall contain:

- Website source code
- Website assets
- Website configuration
- Website-specific documentation
- Website decisions
- Website roadmap
- Website changelog
- Website development standards
- Website architecture

**Reason:**  
The website requires a dedicated product repository with clear ownership and an independent development history.

**Expected Benefit:**  
Separates website implementation from company governance and future Nexsom products.

---

## Decision WD-003 — Website Branch Strategy

**Legacy Reference:** Decision 009  
**Status:** Active  

**Decision:**  
The website shall use the following branch structure:

- `main` — production website
- `website-v2` — Website Version 2 development

Development changes must be completed and reviewed on `website-v2` before being merged into `main`.

**Reason:**  
The production website must remain protected while Website V2 is developed and tested.

**Expected Benefit:**  
Reduces deployment risk, protects the live website, and provides controlled development history.

---

## Decision WD-004 — Initial Website Technology Architecture

**Legacy Reference:** Decision 010  
**Status:** Active  

**Decision:**  
Website V2 shall initially be developed using standard:

- HTML5
- CSS3
- Vanilla JavaScript

A framework such as React, Vue, Svelte, Astro, Next.js, or another technology shall not be introduced unless a clear functional, operational, architectural, or commercial requirement justifies it.

**Reason:**  
The current website does not require unnecessary framework complexity.

**Expected Benefit:**  
Provides fast performance, low operating cost, full code ownership, simple maintenance, and high portability.

**Governance Note:**  
This decision is incorporated into the wider Website V2 Architecture established by Decision WD-009.

---

## Decision WD-005 — Website Project Structure

**Legacy Reference:** Decision 011  
**Status:** Active  

**Decision:**  
The website repository shall maintain a clear and product-specific file structure.

The current approved structure includes:

```text
nexsomtech-website/
├── css/
├── docs/
│   ├── CHANGELOG.md
│   ├── DECISIONS.md
│   ├── DEVELOPMENT-STANDARDS.md
│   ├── ROADMAP.md
│   └── WEBSITE-ARCHITECTURE.md
├── images/
├── js/
├── .gitignore
├── index-v1.html
├── index.html
├── README.md
└── wrangler.jsonc
```

Future files and folders may be added where implementation, maintainability, language, testing, content, or scalability requirements justify them.

**Reason:**  
A predictable structure improves maintainability, development discipline, onboarding, version control, and future expansion.

**Expected Benefit:**  
Keeps the website repository understandable and prevents uncontrolled file organization.

---

## Decision WD-006 — Language Strategy

**Legacy Reference:** Decision 012  
**Status:** Active  

**Decision:**  
Use English as the primary language and Somali as the secondary language.

Planned initial structure:

- `index.html` — English
- `so.html` — Somali

**Reason:**  
English supports professional, donor, institutional, and international positioning.

Somali supports local business customers and accessibility.

**Expected Benefit:**  
Allows Nexsom Technology to serve both professional/international audiences and local Somali-speaking customers through one consistent website architecture.

**Governance Note:**  
Both language versions must remain aligned in structure, positioning, services, navigation, calls to action, and brand implementation.

---

## Decision WD-007 — Documentation First

**Legacy Reference:** Decision 014  
**Status:** Active  

**Decision:**  
Website documentation shall be established before uncontrolled expansion of the website.

Core controlled website documents include:

- Website Decisions Register
- Website Changelog
- Website Development Standards
- Website V2 Roadmap
- Website V2 Architecture
- Repository README

**Reason:**  
Documentation creates consistency, improves future collaboration, preserves decisions, and prevents random technical implementation.

**Expected Benefit:**  
Reduces rework and provides a controlled foundation for future website development.

---

## Decision WD-008 — Version 1 Backup

**Legacy Reference:** Decision 015  
**Status:** Active  

**Decision:**  
The original homepage shall be preserved as:

> `index-v1.html`

while Website V2 is developed.

**Reason:**  
This allows comparison between Version 1 and Version 2 and provides an easy reference point during development.

**Expected Benefit:**  
Protects the original implementation and provides a simple fallback/reference while Website V2 remains under development.

---

## Decision WD-009 — Website V2 Architecture Baseline

**Status:** Active  

**Decision:**  
Nexsom Technology adopts the Website V2 Architecture defined in:

> `docs/WEBSITE-ARCHITECTURE.md`

**Document ID:** NT-WEB-ARC-001  
**Version:** 1.0.0  

The approved architecture establishes the following baseline:

### Technology

Website V2 shall use:

- HTML5
- CSS3
- Vanilla JavaScript

No mandatory framework or build system is required.

### Public Information Architecture

The approved top-level structure is:

- Home
- About
- Services
- Solutions
- Industries
- Why Nexsom
- Contact
- Language

### Service Architecture

The website shall implement the company-approved service hierarchy:

1. Business Software & POS Solutions
2. Website & Application Development
3. Network Infrastructure Services
4. CCTV & Surveillance Solutions
5. Hardware Solutions
6. IT Consulting & Digital Solutions
7. Professional & Creative Services

Professional & Creative Services contains:

- Proposal Development & Technical Documentation
- Editorial & Publishing Services
- Design & Illustration Services

### Page Strategy

Website V2 shall use a hybrid page architecture.

Initial primary language entry files are:

- `index.html`
- `so.html`

Dedicated pages may be introduced later where content, usability, SEO, or commercial need justifies them.

### Language Architecture

- English — primary
- Somali — secondary

Both language versions must remain aligned in navigation, service structure, positioning, calls to action, branding, and major content architecture.

### Application Boundary

The public corporate website shall remain logically separate from operational applications such as:

- Nexsom POS
- ERP systems
- Customer portals
- Dashboards
- Authentication systems
- Customer accounts
- Future SaaS products

Operational applications should normally maintain independent repositories, security controls, architecture, deployment lifecycles, and product governance.

### Infrastructure

Cloudflare remains the current website deployment provider.

Website source code must remain portable to another suitable standards-compatible hosting environment.

### Quality Requirements

Website architecture shall treat the following as built-in requirements:

- Accessibility
- Responsive behavior
- SEO
- Performance
- Security
- Privacy
- Maintainability
- Cross-browser compatibility
- Migration readiness
- Backup readiness

### Brand Authority

Website implementation shall follow the authoritative Corporate Brand System maintained in:

> `nexsom-company-governance/docs/BRAND-SYSTEM.md`

The website may implement brand rules but must not independently redefine corporate identity.

**Reason:**  
Website V2 requires one authoritative architecture before substantial implementation proceeds.

The architecture separates company governance from product implementation, prevents unnecessary framework complexity, preserves migration flexibility, incorporates the approved company service portfolio, and establishes clear boundaries for future Nexsom applications.

**Expected Benefit:**  
Provides a scalable and controlled foundation for Website V2 while reducing architectural ambiguity, technical debt, duplicated decisions, and future migration risk.

**Governance Note:**  
Material changes to the approved architecture must be reviewed before implementation and recorded in this Website Decisions Register where appropriate.

---

# 3. Governance Requirements

Every future website-level decision added to this register must include:

- Decision ID
- Decision title
- Status
- Decision
- Reason
- Expected benefit
- Supersession reference where applicable

Website-level decisions must remain within the `nexsomtech-website` product-governance boundary.

Company-level decisions must not be duplicated as independent website decisions.

Where the website implements a company-level standard, the website register should reference the authoritative company source rather than redefine it.

---

# 4. Historical Recovery Note

During the separation of company governance from website governance, the regenerated Website Decisions Register created in commit:

> `29ad0ef`

was later found to contain only 162 lines and to end partway through Decision WD-005.

Git history confirmed that the earlier mixed register in commit:

> `4ecef04`

preserved additional website-specific historical decisions.

The following decisions were recovered from that historical source and incorporated into the current Website Decisions Register:

- Legacy Decision 012 — Language Strategy
- Legacy Decision 014 — Documentation First
- Legacy Decision 015 — Version 1 Backup

Company-level legacy decisions remain under the authority of the company-governance repository and were not reintroduced into this website register.

This recovery preserves historical traceability without restoring the former mixed company/product governance structure.

---

# 5. Source-of-Truth Statement

This Markdown file is the authoritative editable Website Decisions Register.

Published Word or PDF versions may be generated for formal use, but they must remain synchronized with this source document.