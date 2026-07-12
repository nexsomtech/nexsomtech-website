# Nexsom Technology Website
# Website Decisions Register

**Document ID:** NT-WEB-DEC-001  
**Version:** 1.0.0  
**Status:** Active  
**Effective Date:** 12 July 2026  
**Product:** Nexsom Technology Website  
**Owner:** Nexsom Technology  
**Classification:** Product Governance  
**Repository:** `nexsomtech-website`  
**Source Format:** Markdown  

---

## 1. Purpose

This register records the approved decisions that govern the design, architecture, development, deployment, maintenance, and future expansion of the Nexsom Technology website.

It contains only website-specific decisions.

Company-level decisions, including corporate identity, company purpose, brand governance, management-system rules, and enterprise technology direction, are maintained separately in:

> `nexsom-company-governance/docs/DECISIONS.md`

The website must comply with approved company governance and corporate standards.

---

## 2. Decision Status Definitions

- **Active:** The decision is currently approved and applicable.
- **Superseded:** The decision has been replaced by a later approved decision.
- **Retired:** The decision is no longer applicable but remains recorded for traceability.
- **Planned:** The decision is approved in principle but has not yet been fully implemented.

Approved decisions must not be deleted solely because they have been replaced. Superseded and retired decisions must remain recorded with the relevant replacement reference.

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

## Decision WD-004 — Initial Website Architecture

**Legacy Reference:** Decision 010  
**Status:** Active  

**Decision:**  
Website V2 shall initially be developed using standard:

- HTML
- CSS
- JavaScript

A framework such as React, Vue, Svelte, Astro, Next.js, or another technology shall not be introduced unless a clear functional, operational, or commercial requirement justifies it.

**Reason:**  
The current website does not require unnecessary framework complexity.

**Expected Benefit:**  
Provides fast performance, low operating cost, full code ownership, simple maintenance, and high portability.

---

## Decision WD-005 — Website Project Structure

**Legacy Reference:** Decision 011  
**Status:** Active  

**Decision:**  
The website repository shall maintain a clear file structure.

The current approved structure includes:

```text
nexsomtech-website/
├── css/
├── docs/
├── images/
├── js/
├── .gitignore
├── index-v1.html
├── index.html
├── README.md
└── wrangler.jsonc