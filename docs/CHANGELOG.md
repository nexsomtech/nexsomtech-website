# Nexsom Technology Website
# Website Changelog

**Document ID:** NT-WEB-CHG-001  
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

This changelog records significant changes to the Nexsom Technology website, including:

- Website architecture
- Source-code structure
- Website documentation
- Design implementation
- Hosting and deployment
- Branch management
- Website governance
- Version releases

Company-level governance, corporate identity, company strategy, and management-system changes are recorded separately in:

> `nexsom-company-governance/docs/CHANGELOG.md`

---

## 2. Versioning Policy

The website follows Semantic Versioning:

> `MAJOR.MINOR.PATCH`

### Major version

Used for a major production release, substantial redesign, architectural replacement, or significant compatibility change.

### Minor version

Used for new website functionality, substantial content additions, design-system implementation, or major non-breaking improvements.

### Patch version

Used for corrections, minor improvements, security fixes, accessibility fixes, content corrections, and non-structural updates.

Website versions are independent from company-governance and other Nexsom product versions.

---

## 3. Development and Release Policy

Changes under:

> `[Unreleased]`

are still under development and are not considered production releases.

Website Version 2 must remain under `[Unreleased]` until it has been:

- Completed
- Reviewed
- Tested
- Approved
- Merged into `main`
- Deployed to production

Only then may it be released as:

> `2.0.0`

---

# [Unreleased]

## Website Version 2

Website Version 2 is currently being developed on:

> `website-v2`

The production website remains protected on:

> `main`

---

## Added

### Website Governance

- Created the authoritative Website Decisions Register:

  > `docs/DECISIONS.md`

- Assigned the Website Decisions Register document identifier:

  > `NT-WEB-DEC-001`

- Established separate company and website decision ownership.
- Established website decision statuses:

  - Active
  - Superseded
  - Retired
  - Planned

- Added the website governance precedence structure:

  1. Approved Nexsom company governance
  2. Corporate Brand System
  3. Website Technology Strategy
  4. Website Architecture
  5. Website Development Standards
  6. Website Decisions Register
  7. Website Roadmap
  8. Implementation tasks

### Website Technology Strategy

- Adopted a website technology strategy prioritizing:

  - Free or open-source solutions
  - Standards-based technologies
  - Portable source formats
  - Full Nexsom ownership
  - Migration readiness
  - Independent backups
  - Documented migration paths
  - Minimal vendor lock-in

- Established the approved infrastructure approach:

  > **Managed free services now → open standards throughout → independent backups → documented migration path → self-hosting or alternative infrastructure when commercially justified.**

- Established that current service providers and tools must not become permanent architectural dependencies.

- Established evaluation criteria for major website technologies, including:

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

### Current Website Working Stack

- Confirmed the current approved stack:

  - VS Code
  - Git
  - GitHub
  - Cloudflare Pages
  - HTML
  - CSS
  - JavaScript
  - Markdown
  - Penpot or exportable Figma assets
  - SVG
  - PNG
  - PDF
  - CSS variables
  - Design tokens

### Website Ownership and Portability

- Established Nexsom ownership of:

  - Website source code
  - Documentation
  - Configuration
  - Deployment instructions
  - Design assets
  - Content structures
  - Technical records

- Established preferred portable formats:

  - HTML
  - CSS
  - JavaScript
  - Markdown
  - SVG
  - PNG
  - JSON
  - Web-standard fonts
  - CSS variables
  - Design tokens
  - Git repositories

- Established an independent backup requirement.
- Established a website migration-documentation requirement.
- Established periodic website technology lifecycle reviews.

### Website Brand Implementation

- Added the approved corporate colour palette for Website V2:

  - Primary Navy: `#00245C`
  - Dark Navy: `#001F54`
  - Primary Orange: `#FF6A00`
  - White: `#FFFFFF`
  - Soft Background: `#F8FAFC`
  - Body Text Gray: `#64748B`
  - Border Gray: `#E2E8F0`

- Added the official public tagline:

  > **Smart Solutions. Stronger Businesses.**

- Established that the website must implement the Corporate Brand System maintained in:

  > `nexsom-company-governance/docs/BRAND-SYSTEM.md`

### Future Compatibility

- Established that the website architecture should support future integration with:

  - POS systems
  - Inventory platforms
  - ERP systems
  - Customer portals
  - Partner portals
  - APIs
  - AI services
  - Business applications
  - Authentication services
  - Support systems
  - Approved payment or commerce services

### Development Workflow

- Adopted the controlled website-development rule:

  > **One completed step at a time.**

- Established that major dependent implementation should follow approved standards and architecture.
- Established verification, commit, and push checkpoints during controlled development.

---

## Changed

### Documentation Ownership

- Separated company-level governance from website product documentation.
- Removed the Corporate Brand System from:

  > `nexsomtech-website/docs/BRAND-SYSTEM.md`

- Established the authoritative Corporate Brand System location as:

  > `nexsom-company-governance/docs/BRAND-SYSTEM.md`

- Retained only website-specific governance and implementation documentation in the website repository.

### Decisions Register

- Replaced the former mixed Decisions Log with a website-specific Decisions Register.
- Removed company-level decisions from the website register.
- Preserved relevant historical website decisions through legacy references.
- Added the approved website technology, ownership, migration, portability, and provider-independence decisions.

### Development Environment

- Changed from a single-folder VS Code project to a saved multi-repository workspace:

  > `Nexsom-Technology.code-workspace`

- Maintained the website as an independent repository within the workspace.

### Website Architecture Direction

- Confirmed standard HTML, CSS, and JavaScript as the initial Website V2 architecture.
- Clarified that frameworks must not be introduced without a justified requirement.
- Clarified that scalability does not require premature technical complexity.

---

## Corrected

- Corrected character-encoding errors such as:

  > `â€”`

  to:

  > `—`

- Corrected the former slogan status.
- Corrected the website tagline to:

  > **Smart Solutions. Stronger Businesses.**

- Corrected the mixed classification of company and website records.
- Corrected the assumption that the Corporate Brand System belongs permanently inside the website repository.
- Corrected website versioning so that Website V2 remains under `[Unreleased]` until production release.
- Corrected the earlier use of `2.0.0` as a current development version.

---

## Removed

- Removed the duplicate Corporate Brand System from the website repository after its official company copy was safely committed and pushed.
- Removed an accidental untracked image from the `docs` folder before committing website documentation changes.
- Removed company-level decisions from the Website Decisions Register.

---

## Security

- Established that passwords, API keys, tokens, certificates, credentials, and other operational secrets must not be committed to the website repository.
- Established independent backup requirements for website source code, assets, configuration, deployment instructions, and DNS records.
- Established that external integrations must be evaluated for security and migration risk.

---

# [1.1.0] — Historical Website Restructuring

## Added

- Added the `docs` directory.
- Added dedicated folders for:

  - CSS
  - JavaScript
  - Images
  - Documentation

- Added website governance files:

  - `CHANGELOG.md`
  - `DECISIONS.md`
  - `DEVELOPMENT-STANDARDS.md`
  - `ROADMAP.md`

- Preserved the original homepage as:

  > `index-v1.html`

- Created the `website-v2` development branch.

## Changed

- Separated website source code and documentation into clearer folders.
- Established a branch strategy separating development from production.
- Began Website V2 development while preserving the live website.

---

# [1.0.0] — Initial Website Foundation

## Added

- Created the initial Nexsom Technology website.
- Created the initial `index.html`.
- Added the initial website branding.
- Created the GitHub website repository.
- Established Git version control.
- Connected the website to Cloudflare deployment.
- Added Cloudflare configuration.
- Established VS Code as the initial website development environment.
- Added Live Server support for local website preview.
- Established `main` as the production branch.

## Infrastructure

- Registered and configured:

  > `nexsomtech.com`

- Established Cloudflare as the current DNS, SSL, security, and website-delivery provider.
- Established GitHub as the current website repository and deployment-history provider.

---

# Source-of-Truth Statement

This Markdown file is the authoritative editable Website Changelog.

Published Word or PDF versions may be generated for formal use, but they must remain synchronized with this source document.