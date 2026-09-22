# Nexsom Technology Website

Official website repository for **Nexsom Technology**.

**Website:** `nexsomtech.com`  
**Repository:** `nexsomtech-website`  
**Production Branch:** `main`  
**Development Branch:** `website-v2`  
**Website V2 Status:** In Progress / Unreleased  
**Owner:** Nexsom Technology  

---

## 1. Repository Purpose

This repository contains the source code, assets, configuration, and website-specific governance documentation for the Nexsom Technology public website.

The website is one product within the wider Nexsom Technology ecosystem.

Company-level governance, corporate brand authority, company strategy, and management-system documents are maintained separately in:

> `nexsom-company-governance`

This repository must not become the authoritative owner of company-wide governance or corporate identity.

---

## 2. Current Development Status

Website Version 2 is currently under development on:

> `website-v2`

The production website remains on:

> `main`

Website V2 is classified as:

> `[Unreleased]`

until it has been completed, reviewed, tested, approved, merged into `main`, and successfully deployed to production.

The original website has been preserved as:

> `index-v1.html`

for historical reference and recovery during Website V2 development.

---

## 3. Current Technology Stack

Website V2 currently uses:

- HTML5
- CSS3
- Vanilla JavaScript
- Git
- GitHub
- VS Code
- Cloudflare infrastructure
- Markdown documentation

The current architecture intentionally avoids unnecessary framework complexity.

Frameworks, libraries, plugins, paid platforms, and external services must not be introduced without a justified business and technical requirement.

---

## 4. Website Technology Principle

Nexsom Technology prioritizes:

> **Managed free services now → open standards throughout → independent backups → documented migration path → self-hosting or alternative infrastructure when commercially justified.**

The website must remain:

- Standards-based
- Portable
- Migration-ready
- Maintainable
- Secure
- Accessible
- Performance-conscious
- Fully controlled by Nexsom Technology

Cloudflare, GitHub, VS Code, or any other current provider is a tool, not a permanent architectural limitation.

---

## 5. Repository Structure

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