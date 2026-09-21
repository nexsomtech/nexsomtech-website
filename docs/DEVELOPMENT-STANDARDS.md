# Nexsom Technology Website
# Website Development Standards

**Document ID:** NT-WEB-DEV-001  
**Document Version:** 2.0.0  
**Status:** Active  
**Effective Date:** 21 September 2026  
**Product:** Nexsom Technology Website  
**Owner:** Nexsom Technology  
**Classification:** Product Governance / Engineering Standard  
**Repository:** `nexsomtech-website`  
**Primary Branch:** `main`  
**Development Branch:** `website-v2`  
**Source Format:** Markdown  

---

## 1. Purpose

This document defines the engineering and implementation standards for the Nexsom Technology website.

Its purpose is to ensure that Website V2 and future website improvements remain:

- Professional
- Maintainable
- Secure
- Accessible
- Responsive
- Fast
- Standards-based
- Portable
- Migration-ready
- Consistent with Nexsom company governance

This document governs website development only.

It does not define company-wide brand, business, or management-system policy.

---

## 2. Authority and Governance

Website development must follow approved Nexsom governance in the following order:

1. Nexsom company governance
2. Corporate Brand System
3. Website Technology Strategy
4. Website Architecture
5. Website Development Standards
6. Website Decisions Register
7. Website Roadmap
8. Implementation tasks

Where documents conflict, the higher-authority document governs until the conflict is formally resolved.

The authoritative Corporate Brand System is maintained in:

> `nexsom-company-governance/docs/BRAND-SYSTEM.md`

The authoritative Website Decisions Register is maintained in:

> `nexsomtech-website/docs/DECISIONS.md`

The Website Changelog is maintained in:

> `nexsomtech-website/docs/CHANGELOG.md`

---

## 3. Website Development Objective

The Nexsom website must provide a professional, trustworthy, clear, and efficient digital experience while remaining technically simple enough to maintain and flexible enough to support future growth.

Website implementation should strengthen:

- Customer confidence
- Business credibility
- Product visibility
- Usability
- Performance
- Maintainability
- Security
- Future integration capability

---

## 4. Core Engineering Principles

All website development should follow these principles.

### 4.1 Simplicity Before Complexity

Use the simplest technology that satisfies the approved requirement.

Do not introduce frameworks, libraries, build systems, or external services without a clear need.

### 4.2 Standards Before Proprietary Dependencies

Prefer open web standards and portable formats.

Primary technologies should remain based on:

- HTML
- CSS
- JavaScript
- Markdown
- SVG
- JSON
- Git

### 4.3 Mobile-First Development

Design and implement from smaller screens upward.

Desktop layouts should extend the mobile experience rather than replace it.

### 4.4 Performance by Design

Performance must be considered during implementation, not only after development.

### 4.5 Security by Design

Security must be considered whenever adding forms, scripts, APIs, analytics, authentication, external services, or user data.

### 4.6 Accessibility by Design

Accessibility is a development requirement, not an optional enhancement.

### 4.7 Reusability

Repeated interface patterns should use reusable classes, tokens, components, or functions.

### 4.8 Maintainability

Code must remain understandable to future Nexsom developers.

### 4.9 Progressive Enhancement

Core content and navigation should remain usable even when optional JavaScript features fail.

### 4.10 Controlled Evolution

Technology may change when justified by business or technical requirements.

Technology must not be adopted simply because it is popular.

---

## 5. Approved Current Technology Stack

The current Website V2 implementation stack is:

- HTML5
- CSS3
- Vanilla JavaScript
- Git
- GitHub
- VS Code
- Cloudflare Pages / current Cloudflare website infrastructure
- Markdown documentation

Design work may use:

- Penpot
- Figma

provided final assets are retained in portable formats.

These tools are current implementation choices, not permanent architectural dependencies.

---

## 6. Technology Adoption Rule

A new framework, library, plugin, service, platform, or integration must not be introduced until evaluated against:

1. Business value
2. Technical suitability
3. Security
4. Performance
5. Maintainability
6. Cost
7. Scalability
8. Data ownership
9. Code ownership
10. Migration difficulty
11. Vendor-lock-in risk
12. Community and ecosystem maturity
13. Documentation quality
14. Integration compatibility

Examples of technologies that require evaluation before adoption include:

- React
- Next.js
- Vue
- Svelte
- Astro
- Node.js frameworks
- CMS platforms
- Analytics systems
- Form services
- Authentication providers
- Third-party widgets
- AI integrations
- Payment systems

No technology is pre-approved merely because it appears in a future roadmap.

---

## 7. Repository Structure

The current website repository structure is:

```text
nexsomtech-website/
├── css/
│   └── style.css
├── docs/
│   ├── CHANGELOG.md
│   ├── DECISIONS.md
│   ├── DEVELOPMENT-STANDARDS.md
│   └── ROADMAP.md
├── images/
├── js/
│   └── script.js
├── .gitignore
├── index-v1.html
├── index.html
├── README.md
└── wrangler.jsonc