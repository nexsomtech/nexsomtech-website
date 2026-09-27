# Nexsom Technology Website
# Website Changelog

**Document ID:** NT-WEB-CHG-001  
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

This changelog records significant changes to the Nexsom Technology website, including:

- Website architecture
- Source-code structure
- Website documentation
- Design implementation
- Hosting and deployment
- Branch management
- Website governance
- Version releases

Company-level governance, corporate identity, company strategy, service architecture, and management-system changes are recorded separately in:

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

### Website V2 Architecture

- Created the authoritative Website V2 Architecture document:

  > `docs/WEBSITE-ARCHITECTURE.md`

- Assigned the architecture document identifier:

  > `NT-WEB-ARC-001`

- Established architecture version:

  > `1.0.0`

- Established Website V2 as a standards-based static website using:

  - HTML5
  - CSS3
  - Vanilla JavaScript

- Established that Website V2 does not require a mandatory JavaScript framework or mandatory build system.

- Established that future adoption of frameworks, CMS platforms, backend runtimes, databases, authentication systems, or other major architectural dependencies requires documented justification and review.

### Public Information Architecture

- Approved the primary public website structure:

  1. Home
  2. About
  3. Services
  4. Solutions
  5. Industries
  6. Why Nexsom
  7. Contact
  8. Language

- Established that this structure defines information architecture without requiring every navigation item to become a separate page immediately.

### Homepage Architecture

- Established the recommended homepage structure:

  - Header / Navigation
  - Hero
  - Company Introduction
  - Services Overview
  - Solutions Overview
  - Industries
  - Why Nexsom
  - Primary Call to Action
  - Contact
  - Footer

### Website Service Architecture

- Synchronized Website V2 with the approved company service portfolio.

The website shall use the following top-level service structure:

1. **Business Software & POS Solutions**
2. **Website & Application Development**
3. **Network Infrastructure Services**
4. **CCTV & Surveillance Solutions**
5. **Hardware Solutions**
6. **IT Consulting & Digital Solutions**
7. **Professional & Creative Services**

- Established **Website & Application Development** as one combined service family.

- Established **Professional & Creative Services** as the parent category for:

  - Proposal Development & Technical Documentation
  - Editorial & Publishing Services
  - Design & Illustration Services

### Solutions Architecture

- Established the distinction between **Services** and **Solutions**.

- Services describe Nexsom capabilities.

- Solutions describe packaged, repeatable, or commercially focused offerings.

Initial solution areas may include:

- POS Solutions
- Inventory Solutions
- POS Hardware Packages
- Network Solutions
- CCTV Solutions
- Custom Business Solutions

- Established that future products must not be presented as existing Nexsom-owned products unless they have actually been approved and developed.

### Hybrid Page Strategy

- Adopted a hybrid Website V2 page architecture.

Initial language entry files are planned as:

- `index.html`
- `so.html`

- Established that dedicated pages may later be introduced where justified by:

  - Content depth
  - User experience
  - SEO
  - Commercial need
  - Maintainability
  - Scalability

### Language Architecture

- Confirmed the website language priority:

  1. English — primary
  2. Somali — secondary

- Established that both language versions must remain aligned in:

  - Navigation
  - Service architecture
  - Company positioning
  - Major content structure
  - Calls to action
  - Brand implementation
  - Accessibility
  - Metadata quality

### Application Boundary

- Established that the public corporate website remains logically separate from operational applications.

Examples include:

- Nexsom POS
- ERP systems
- Customer Portal
- Dashboards
- Authentication systems
- Customer accounts
- Future SaaS applications

- Established that operational applications should normally maintain separate:

  - Repositories
  - Architecture
  - Security controls
  - Deployment lifecycles
  - Release processes
  - Product governance

### Deployment and Migration Architecture

- Confirmed Cloudflare as the current website deployment provider.

- Established that Website V2 must remain portable to another suitable standards-compatible hosting environment.

- Established migration readiness through:

  - Nexsom-owned source code
  - Git history
  - Standard HTML
  - Standard CSS
  - Standard JavaScript
  - Portable assets
  - Documented configuration
  - DNS knowledge
  - Backup copies
  - Replaceable third-party services

### Quality Architecture

- Established the following as architectural requirements rather than end-stage additions:

  - Accessibility
  - Mobile-first responsive behavior
  - SEO
  - Performance
  - Security
  - Privacy
  - Maintainability
  - Cross-browser compatibility
  - Migration readiness
  - Backup readiness

### Accessibility Architecture

- Established accessibility as a continuous development requirement.

- Established WCAG 2.2 AA practices as the target where reasonably applicable.

Key requirements include:

- Semantic HTML
- Keyboard navigation
- Visible focus states
- Color contrast
- Alternative text
- Form labels
- Meaningful links
- Accessible buttons
- Touch target sizing
- Reduced-motion consideration
- Correct language attributes
- Logical heading structure

### Security and Privacy Architecture

- Established that website source code must not contain:

  - Passwords
  - API keys
  - Access tokens
  - Private certificates
  - Customer credentials
  - Production secrets
  - Private authentication information

- Established that future features involving forms, APIs, authentication, payments, analytics, CRM systems, AI services, or databases require additional security and privacy review.

- Established a minimum-data-collection principle for future website integrations.

### Website Architecture Change Control

- Established that material architectural changes require review before implementation.

Examples include:

- Adopting a major framework
- Introducing a CMS
- Adding authentication
- Adding customer accounts
- Adding payments
- Introducing a database
- Adding major APIs
- Adding a backend runtime
- Changing hosting providers
- Introducing significant SaaS dependencies
- Changing language architecture
- Restructuring major navigation
- Changing application boundaries

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

  > **Managed services now → open standards throughout → independent backups → documented migration path → alternative infrastructure or self-hosting when commercially justified.**

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

- Confirmed the current approved working stack:

  - VS Code
  - Git
  - GitHub
  - Cloudflare
  - HTML5
  - CSS3
  - Vanilla JavaScript
  - Markdown
  - SVG
  - PNG
  - PDF
  - CSS custom properties
  - Design tokens

- Established that design tools may be used where source or exportable assets remain under Nexsom control.

### Website Ownership and Portability

- Established Nexsom ownership of:

  - Website source code
  - Documentation
  - Configuration
  - Deployment instructions
  - Design assets
  - Content structures
  - Technical records

- Established preferred portable formats including:

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

### Website Decisions Register

- Regenerated the authoritative Website Decisions Register.

- Updated the register version to:

  > `1.1.0`

- Expanded the register from the incomplete 162-line version to a complete website-specific governance record.

- Added:

  > **Decision WD-009 — Website V2 Architecture Baseline**

- Updated Website Project Structure to include:

  > `docs/WEBSITE-ARCHITECTURE.md`

- Clarified that the website repository owns product-specific architecture while company governance remains authoritative for corporate identity, service architecture, and company strategy.

### Documentation Ownership

- Separated company-level governance from website product documentation.

- Removed the Corporate Brand System from:

  > `nexsomtech-website/docs/BRAND-SYSTEM.md`

- Established the authoritative Corporate Brand System location as:

  > `nexsom-company-governance/docs/BRAND-SYSTEM.md`

- Retained only website-specific governance and implementation documentation in the website repository.

### Decisions Register Separation

- Replaced the former mixed Decisions Log with a website-specific Decisions Register.

- Removed company-level decisions from the website register.

- Preserved relevant historical website decisions through legacy references.

### Development Environment

- Changed from a single-folder VS Code project to a saved multi-repository workspace:

  > `Nexsom-Technology.code-workspace`

- Maintained the website as an independent repository within the workspace.

### Website Architecture Direction

- Expanded the original HTML/CSS/JavaScript decision into a complete Website V2 Architecture baseline.

- Confirmed standard HTML5, CSS3, and Vanilla JavaScript as the current Website V2 technology architecture.

- Confirmed that frameworks must not be introduced without a justified requirement.

- Established that scalability does not require premature technical complexity.

- Established clear boundaries between:

  - Public corporate website
  - Future operational applications
  - Company governance
  - Website product governance

---

## Corrected

### Website Decisions Register Recovery

- Identified that commit:

  > `29ad0ef`

  contained a truncated Website Decisions Register of only 162 lines.

- Confirmed through Git history that the earlier mixed register in commit:

  > `4ecef04`

  retained website-specific historical decisions that had been lost during the later regeneration.

- Recovered and restored:

  - Legacy Decision 012 — Language Strategy
  - Legacy Decision 014 — Documentation First
  - Legacy Decision 015 — Version 1 Backup

- Incorporated these recovered decisions into the website-specific register as:

  - WD-006 — Language Strategy
  - WD-007 — Documentation First
  - WD-008 — Version 1 Backup

- Preserved company-level legacy decisions under the separate company-governance repository rather than restoring the former mixed structure.

### Character Encoding

- Corrected corrupted character encoding in website governance documentation.

Examples included corrupted representations of:

- Em dashes
- Arrows
- Apostrophes
- Tree-structure characters

- Restored readable Unicode characters where appropriate.

### Website Versioning

- Corrected website versioning so that Website V2 remains under:

  > `[Unreleased]`

  until production release.

- Confirmed that development on `website-v2` does not itself constitute a production `2.0.0` release.

### Brand Ownership

- Corrected the assumption that the Corporate Brand System belongs permanently inside the website repository.

- Confirmed that corporate brand authority belongs to:

  > `nexsom-company-governance/docs/BRAND-SYSTEM.md`

### Service Architecture

- Corrected website service presentation to use the approved company-level service architecture.

- Replaced separate website-development and application-development categories with:

  > **Website & Application Development**

- Grouped proposal, editorial, publishing, design, and illustration services under:

  > **Professional & Creative Services**

---

## Removed

- Removed the duplicate Corporate Brand System from the website repository after its official company copy was safely committed and pushed.

- Removed an accidental untracked image from the `docs` folder before committing website documentation changes.

- Removed company-level decisions from the Website Decisions Register.

- Removed the incomplete Website Decisions Register structure by fully regenerating the authoritative product-governance source.

---

## Security

- Established that passwords, API keys, tokens, certificates, credentials, and other operational secrets must not be committed to the website repository.

- Established independent backup requirements for website source code, assets, configuration, deployment instructions, and DNS records.

- Established that external integrations must be evaluated for:

  - Security
  - Privacy
  - Reliability
  - Migration risk
  - Vendor lock-in
  - Operational ownership

---

## Governance

- Established `WEBSITE-ARCHITECTURE.md` as the authoritative Website V2 architecture document.

- Established `DECISIONS.md` as the authoritative Website Decisions Register.

- Established `ROADMAP.md` as the authoritative Website V2 delivery roadmap.

- Established `DEVELOPMENT-STANDARDS.md` as the authoritative website implementation standard.

- Established `CHANGELOG.md` as the authoritative history of material website changes.

- Established that these documents must remain synchronized.

- Established that company-level service architecture and brand authority must be referenced from company governance rather than independently redefined by website product governance.

- Established that material architectural changes require review and decision recording before implementation where appropriate.

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