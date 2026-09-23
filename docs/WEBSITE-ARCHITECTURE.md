# Nexsom Technology Website
# Website V2 Architecture

**Document ID:** NT-WEB-ARC-001  
**Version:** 1.0.0  
**Status:** Active  
**Effective Date:** 23 September 2026  
**Product:** Nexsom Technology Website  
**Owner:** Nexsom Technology  
**Classification:** Product Architecture  
**Repository:** `nexsomtech-website`  
**Development Branch:** `website-v2`  
**Production Branch:** `main`  
**Source Format:** Markdown  

---

## 1. Purpose

This document defines the approved architecture for Nexsom Technology Website Version 2.

It establishes the structural, technical, content, language, deployment, integration, quality, and governance boundaries required to develop and maintain the website consistently.

The architecture applies specifically to the public Nexsom Technology website.

Company-level governance, corporate identity, strategic direction, and company-wide service definitions remain under the authority of:

> `nexsom-company-governance`

---

## 2. Website Role

Website V2 is the primary public corporate website of Nexsom Technology.

Its role is to:

- Present Nexsom Technology professionally
- Explain the company's services and solutions
- Support customer discovery
- Build trust and credibility
- Support sales and business development
- Provide clear contact channels
- Represent the approved Nexsom brand
- Support English and Somali audiences
- Provide a scalable foundation for future digital growth

The website is not the company itself.

It is one digital product within the wider Nexsom Technology ecosystem.

---

## 3. Architectural Principles

Website V2 shall remain:

- Standards-based
- Portable
- Maintainable
- Accessible
- Responsive
- Secure
- Performance-conscious
- Search-friendly
- Migration-ready
- Fully controlled by Nexsom Technology

Current service providers and tools must not become unnecessary permanent architectural dependencies.

The website architecture should favor simplicity where simplicity meets the business requirement.

Complexity shall be introduced only where a clear customer, business, technical, security, or operational requirement justifies it.

---

## 4. Governing Authorities

Website implementation must follow the approved Nexsom governance hierarchy.

### 4.1 Company-Level Authority

```text
nexsom-company-governance/docs/
├── BRAND-SYSTEM.md
├── CHANGELOG.md
├── DECISIONS.md
└── ROADMAP.md
```

These documents govern:

- Corporate identity
- Company purpose
- Positioning
- Official tagline
- Company service portfolio
- Company strategy
- Governance principles
- Long-term direction

### 4.2 Website-Level Authority

```text
nexsomtech-website/docs/
├── CHANGELOG.md
├── DECISIONS.md
├── DEVELOPMENT-STANDARDS.md
├── ROADMAP.md
└── WEBSITE-ARCHITECTURE.md
```

These documents govern:

- Website implementation
- Website technology
- Website delivery
- Website architecture
- Website release history
- Website-specific decisions

Website documentation must implement company-level authority rather than redefine it.

---

## 5. Technology Architecture

Website V2 shall use the following primary front-end technologies:

- HTML5
- CSS3
- Vanilla JavaScript

No mandatory JavaScript framework is required for Website V2.

The current architecture does not require:

- React
- Next.js
- Vue
- Angular
- WordPress
- Laravel
- Node-based build systems
- Proprietary website builders

These technologies may be considered later only when a documented requirement justifies their adoption.

---

## 6. Build Architecture

Website V2 shall not require a mandatory build process.

The website should be capable of running directly from standard web files.

Primary source assets include:

```text
HTML
CSS
JavaScript
Images
SVG
Markdown documentation
```

This approach supports:

- Simplicity
- Low operational cost
- Fast deployment
- Portability
- Easy backup
- Easy migration
- Direct source-code ownership

---

## 7. Public Information Architecture

The approved top-level public website structure is:

```text
Home
About
Services
Solutions
Industries
Why Nexsom
Contact
Language
```

This defines the primary information architecture.

It does not require every item to become a separate page immediately.

The website may initially use a multi-section structure while preserving a clear path toward dedicated pages where justified.

---

## 8. Home Architecture

The homepage should provide a concise overview of Nexsom Technology.

Recommended homepage sections include:

```text
Header / Navigation
Hero
Company Introduction
Services Overview
Solutions Overview
Industries
Why Nexsom
Primary Call to Action
Contact
Footer
```

The homepage should help a visitor quickly understand:

- What Nexsom Technology is
- What Nexsom provides
- Who Nexsom serves
- Why Nexsom is relevant
- How Nexsom can help
- How to contact Nexsom

---

## 9. About Architecture

The About area should communicate company identity without duplicating the full company-governance documents.

Content may include:

- Company overview
- Company purpose
- Positioning
- Customer promise
- Nexsom DNA
- Local market relevance
- Long-term technology direction

Company-level statements must remain aligned with the authoritative governance repository.

---

## 10. Services Architecture

Website V2 shall use the approved Nexsom Technology company service architecture.

The official top-level service categories are:

```text
Services
├── Business Software & POS Solutions
├── Website & Application Development
├── Network Infrastructure Services
├── CCTV & Surveillance Solutions
├── Hardware Solutions
├── IT Consulting & Digital Solutions
└── Professional & Creative Services
```

The website may summarize these services on the homepage and provide additional detail where content and commercial need justify it.

The website must not independently create a conflicting top-level service hierarchy.

---

## 11. Business Software & POS Solutions

This service family may include:

- POS solutions
- Inventory systems
- Business software deployment
- Software configuration
- Localization
- Installation
- Staff training
- Implementation support
- Ongoing support
- Future Nexsom-owned business software

The website may highlight specific products, platforms, or packages where commercially appropriate.

Third-party platforms must not be presented as Nexsom-owned products.

---

## 12. Website & Application Development

Website and application development shall be presented as one combined top-level service family.

This service family may include:

- Corporate websites
- Business websites
- Institutional websites
- NGO websites
- Landing pages
- Web applications
- Mobile applications
- Customer portals
- Dashboards
- Business applications
- Custom digital platforms
- Website maintenance
- Application maintenance
- Website upgrades
- Application upgrades

This service family must not be split into separate top-level website-development and application-development categories unless a future approved company decision changes the service architecture.

---

## 13. Network Infrastructure Services

This service family may include:

- Network assessment
- Network planning
- Network design
- Network installation
- Network configuration
- Wireless network implementation
- Network troubleshooting
- Network maintenance
- Network optimization
- Related infrastructure support

Website content should explain networking in practical customer terms such as reliability, connectivity, security, coverage, performance, and maintainability.

---

## 14. CCTV & Surveillance Solutions

This service family may include:

- CCTV assessment
- CCTV system planning
- CCTV system design
- CCTV installation
- CCTV configuration
- CCTV troubleshooting
- CCTV maintenance
- Camera-system optimization
- Related surveillance-system support

Website content should clearly distinguish CCTV services from general networking services while showing their infrastructure relationship where appropriate.

---

## 15. Hardware Solutions

This service family may include:

- Business technology hardware
- POS hardware
- Networking hardware
- CCTV-related hardware
- Computers and peripherals where approved
- Hardware sourcing
- Hardware supply
- Installation support
- Compatible accessories
- Replacement support
- Maintenance support

Hardware content may later support packaged solutions or catalog-style presentation where commercially justified.

---

## 16. IT Consulting & Digital Solutions

This service family may include:

- Technology advisory
- Technology assessments
- Digital-solution planning
- Systems planning
- Digital-transformation support
- Technical advisory services
- Technology implementation guidance
- Solution evaluation
- Technology-selection support
- Other approved consulting services

The website should describe consulting using practical customer outcomes rather than abstract technical language.

---

## 17. Professional & Creative Services

Professional & Creative Services is an approved parent service category.

It contains the following approved subgroups:

### 17.1 Proposal Development & Technical Documentation

Services may include:

- Proposal writing
- Technical documentation
- Business documentation
- Project documentation
- Professional reports
- Concept notes
- Related approved documentation services

### 17.2 Editorial & Publishing Services

Services may include:

- Book editing
- Book proofreading
- Book writing
- Ebook writing
- Publishing-support services where appropriate

### 17.3 Design & Illustration Services

Services may include:

- Book cover design
- Book design and layout
- Children's book illustration
- Book illustration
- Comic book creation
- Related publishing and illustration work

These services should remain grouped under Professional & Creative Services so that the public website preserves Nexsom Technology's primary technology-company positioning.

---

## 18. Solutions Architecture

The Solutions area is distinct from the Services area.

### Services

Services explain capabilities Nexsom can perform for customers.

### Solutions

Solutions present more packaged, repeatable, or commercially focused offerings.

Initial solution areas may include:

```text
Solutions
├── POS Solutions
├── Inventory Solutions
├── POS Hardware Packages
├── Network Solutions
├── CCTV Solutions
└── Custom Business Solutions
```

Future solutions may include:

- Nexsom POS
- Nexsom Inventory
- ERP modules
- Customer Portal
- Business dashboards
- Mobile applications
- AI-enabled business tools

A future solution must not be presented as an existing Nexsom-owned product unless it has actually been approved and developed.

---

## 19. Industries Architecture

The Industries area should explain how Nexsom services and solutions apply to customer segments.

Potential target segments include:

- Retail businesses
- Clothing shops
- Cosmetics businesses
- Pharmacies
- Mini-markets
- Restaurants
- Hotels
- Small and medium enterprises
- NGOs
- Institutions
- Professional-service organizations
- Other suitable businesses and organizations

Industry content must reflect actual Nexsom capabilities.

---

## 20. Why Nexsom Architecture

The Why Nexsom area should communicate practical differentiation.

Potential themes include:

- Local understanding
- Integrated software and hardware
- Practical implementation
- Customer support
- Training
- Simplicity
- Reliability
- Scalable solutions
- Professional service
- Continuous improvement
- Long-term customer relationships

Claims must remain accurate, supportable, and aligned with company governance.

---

## 21. Contact Architecture

The website must provide simple and clear contact methods.

Approved business contact channels may include:

- Corporate email
- Phone
- WhatsApp
- Contact form where approved
- Approved social channels

Current corporate email:

> `info@nexsomtech.com`

Current official call and WhatsApp number:

> `+252633214654`

Future contact forms or integrations must follow security and privacy requirements before implementation.

---

## 22. Page Strategy

Website V2 shall use a hybrid page architecture.

### Initial Website V2

Primary language entry files are planned as:

```text
index.html
so.html
```

The main website may begin as a structured multi-section corporate website.

### Future Expansion

Dedicated pages may later be introduced where sufficient content, SEO value, usability, or commercial need exists.

Potential examples include:

```text
services/
solutions/
industries/
about/
contact/
```

Dedicated pages must not be created merely to make the website appear larger.

Every page must have a clear user, content, SEO, operational, or business purpose.

---

## 23. English and Somali Language Architecture

The approved language priority is:

1. English — primary
2. Somali — secondary

The planned initial structure is:

```text
index.html
so.html
```

Both language versions should preserve:

- Navigation logic
- Service architecture
- Major content structure
- Company positioning
- Calls to action
- Brand identity
- Accessibility
- Metadata quality

The Somali version must not become an outdated or incomplete secondary copy.

---

## 24. Navigation Architecture

The primary navigation should remain concise.

Recommended initial navigation:

```text
Home
About
Services
Solutions
Industries
Why Nexsom
Contact
Language
```

On mobile devices, navigation may collapse into an accessible mobile menu.

Navigation must support:

- Keyboard use
- Visible focus
- Touch interaction
- Clear labels
- Logical order
- Responsive behavior

---

## 25. Front-End File Architecture

The current core website structure is:

```text
nexsomtech-website/
├── css/
│   └── style.css
├── docs/
│   ├── CHANGELOG.md
│   ├── DECISIONS.md
│   ├── DEVELOPMENT-STANDARDS.md
│   ├── ROADMAP.md
│   └── WEBSITE-ARCHITECTURE.md
├── images/
├── js/
│   └── script.js
├── .gitignore
├── index-v1.html
├── index.html
├── README.md
└── wrangler.jsonc
```

Future files or folders should be introduced only when justified by implementation, maintainability, content, localization, testing, or scalability requirements.

---

## 26. HTML Architecture

HTML shall be:

- Semantic
- Accessible
- Standards-compliant
- Content-focused
- Maintainable

Preferred structural elements include:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

Heading hierarchy must remain logical.

HTML should not depend on JavaScript for access to essential public content.

---

## 27. CSS Architecture

CSS shall manage:

- Corporate design tokens
- Typography
- Spacing
- Layout
- Responsive behavior
- Components
- Interactive states
- Accessibility states

CSS custom properties should be used for approved reusable values.

Recommended architectural categories include:

```text
Design tokens
Base styles
Typography
Layout
Components
Sections
Utilities
Responsive rules
Accessibility states
```

Additional CSS files may be introduced if `style.css` becomes difficult to maintain.

Any split must preserve clear ownership and avoid unnecessary fragmentation.

---

## 28. JavaScript Architecture

JavaScript shall be used only where interaction or enhancement requires it.

Likely responsibilities include:

- Mobile navigation
- Navigation states
- Lightweight user interactions
- Form behavior
- Progressive enhancement
- Language-interface enhancements where required

JavaScript should remain modular in responsibility even when initially stored in one file.

Unnecessary dependencies should be avoided.

---

## 29. Progressive Enhancement

Core website content and navigation should remain usable without advanced JavaScript execution wherever practical.

JavaScript should enhance the experience rather than unnecessarily control basic page access.

This supports:

- Reliability
- Accessibility
- Performance
- Compatibility
- Maintainability
- Search visibility

---

## 30. Application Boundary

The public corporate website must remain logically separate from operational Nexsom applications.

Examples include:

- Nexsom POS
- Customer Portal
- ERP systems
- Dashboards
- Authentication systems
- Customer accounts
- Internal business systems
- Future SaaS applications

These systems may later connect to the public website through:

- Links
- Subdomains
- APIs
- Authentication gateways
- Integration services

Operational applications should normally maintain separate:

- Repositories
- Architecture
- Security controls
- Deployment lifecycles
- Release processes
- Product governance

---

## 31. Future Subdomain Architecture

Future Nexsom systems may use suitable subdomains where justified.

Potential examples include:

```text
app.nexsomtech.com
portal.nexsomtech.com
support.nexsomtech.com
docs.nexsomtech.com
```

These examples do not constitute automatic approval to create those systems or subdomains.

Each requires appropriate future approval and architecture.

---

## 32. Deployment Architecture

Cloudflare is the current website infrastructure and deployment provider.

Current deployment-related configuration includes:

```text
wrangler.jsonc
```

The deployment architecture must remain:

- Documented
- Reproducible
- Version-controlled where appropriate
- Migration-ready
- Recoverable

Production deployment must not depend on undocumented manual configuration.

---

## 33. Migration Architecture

Website V2 must remain capable of moving to another suitable standards-compatible hosting provider without requiring a complete rebuild.

Migration readiness depends on:

- Nexsom-owned source code
- Git history
- Standard HTML
- Standard CSS
- Standard JavaScript
- Portable images
- Portable SVG assets
- Documented configuration
- DNS knowledge
- Backup copies
- Replaceable third-party services

Cloudflare, GitHub, VS Code, or another current provider must not become an unavoidable architectural requirement.

---

## 34. Backup Architecture

Website source code is protected through Git version control and remote repository storage.

Additional practical backups should be maintained for critical assets and configuration.

Backup planning should cover:

- Source code
- Design assets
- Logo assets
- Images
- Documentation
- Deployment configuration
- DNS information
- Future data-bearing integrations

GitHub alone should not be treated as the only possible long-term backup mechanism.

---

## 35. Accessibility Architecture

Accessibility is an architectural requirement.

Website V2 should target WCAG 2.2 AA practices where reasonably applicable.

Key requirements include:

- Semantic HTML
- Keyboard navigation
- Visible focus states
- Sufficient color contrast
- Alternative text
- Form labels
- Meaningful links
- Accessible buttons
- Touch target sizing
- Reduced-motion consideration
- Correct language attributes
- Logical heading structure

Accessibility must be considered throughout design and development rather than added only at the end.

---

## 36. Responsive Architecture

Website V2 shall use a mobile-first responsive approach.

Layouts should adapt based on content needs rather than relying solely on fixed device categories.

Reference breakpoints may be used where helpful, but design decisions should remain content-driven.

The website should support practical use across:

- Small mobile devices
- Mobile devices
- Tablets
- Laptops
- Desktop computers
- Larger displays

---

## 37. Performance Architecture

Performance must remain a continuous architectural concern.

Website V2 should prioritize:

- Lightweight HTML
- Efficient CSS
- Minimal JavaScript
- Optimized images
- Limited third-party scripts
- Appropriate font loading
- Fast initial rendering
- Efficient asset delivery
- Reduced unnecessary animation

Reference Lighthouse targets may be used as quality indicators rather than absolute guarantees.

---

## 38. SEO Architecture

SEO must be built into the page structure.

Website pages should support:

- Unique page titles
- Meta descriptions
- Semantic headings
- Canonical URLs where appropriate
- Open Graph metadata
- Social-sharing metadata
- Structured data where useful
- Descriptive links
- Image alternative text
- Language metadata
- Search-engine-readable content

SEO content must remain accurate and must not use misleading claims.

---

## 39. Security Architecture

The public website should minimize attack surface.

Website source code must not contain:

- Passwords
- API keys
- Access tokens
- Private certificates
- Customer credentials
- Production secrets
- Private authentication information

Third-party scripts should be limited and reviewed.

Future features involving:

- Forms
- APIs
- Authentication
- Customer accounts
- Payments
- Analytics
- CRM systems
- AI services
- Databases

must undergo additional security and privacy review.

---

## 40. Privacy Architecture

Website V2 should collect the minimum amount of personal data necessary.

Any future data collection must define:

- What data is collected
- Why it is collected
- Where it is sent
- How it is protected
- How long it is retained
- Which external provider receives it
- How users are informed where applicable

Unnecessary tracking should be avoided.

---

## 41. External Service Architecture

External services may be used only where they provide clear value.

Examples may include:

- Hosting
- Email
- Analytics
- Forms
- Maps
- Messaging
- CRM systems
- Customer support systems
- Monitoring services

Each external service should be evaluated for:

- Business value
- Cost
- Reliability
- Security
- Privacy
- Vendor lock-in
- Export capability
- Migration path
- Operational ownership

---

## 42. Design System Boundary

Website V2 may maintain implementation-level design tokens and UI components.

These may include:

- Buttons
- Cards
- Containers
- Typography
- Spacing
- Navigation
- Form controls
- Alerts
- Footer patterns
- Responsive behavior
- Interactive states

The website design system implements the Corporate Brand System.

It does not replace or redefine it.

---

## 43. Corporate Brand Authority

The authoritative Nexsom Technology Corporate Brand System is maintained in:

> `nexsom-company-governance/docs/BRAND-SYSTEM.md`

Website implementation must follow approved corporate rules for:

- Logo
- Colors
- Typography
- Tagline
- Positioning
- Visual language
- Communication style
- Future brand standards

---

## 44. Current Brand Reference

The current approved public tagline is:

> **Smart Solutions. Stronger Businesses.**

The current approved corporate palette is:

```text
Primary Navy:        #00245C
Dark Navy:           #001F54
Primary Orange:      #FF6A00
White:               #FFFFFF
Soft Background:     #F8FAFC
Body Text Gray:      #64748B
Border Gray:         #E2E8F0
```

If the Corporate Brand System changes these values, website implementation must follow the updated authoritative source.

---

## 45. Cross-Browser Architecture

Website V2 should use broadly supported web standards.

Testing should cover current major standards-compliant browsers where practical.

Architecture should avoid browser-specific dependencies unless unavoidable and documented.

---

## 46. Failure and Resilience Principles

The website should degrade gracefully.

Where an optional external service fails:

- Core company information should remain available
- Navigation should remain usable
- Contact alternatives should remain visible where possible
- Essential content should remain accessible

A third-party failure should not unnecessarily make the entire website unusable.

---

## 47. Content Ownership

Website content belongs to Nexsom Technology.

Content changes must remain aligned with:

- Company governance
- Corporate brand authority
- Approved service architecture
- Website decisions
- Website roadmap
- Website architecture

Website copy must not create new company commitments, products, guarantees, partnerships, or service claims without appropriate approval.

---

## 48. Architecture Change Control

Material architecture changes require review before implementation.

Examples include:

- Adopting a major framework
- Introducing a CMS
- Adding authentication
- Adding customer accounts
- Adding payments
- Introducing a database
- Adding major APIs
- Adding a backend runtime
- Moving hosting providers
- Introducing significant external SaaS dependencies
- Changing language architecture
- Restructuring major navigation
- Changing application boundaries

Where required, the decision must be recorded in the Website Decisions Register.

---

## 49. Architecture Relationship to Other Website Documents

This document defines:

> **How the website is structured.**

The Website V2 Roadmap defines:

> **The order in which the website is developed.**

The Website Development Standards define:

> **How implementation work must be performed.**

The Website Decisions Register records:

> **Approved website-specific decisions.**

The Website Changelog records:

> **Material implementation and release history.**

These documents must remain consistent.

---

## 50. Architecture Completion Criteria

The Website Architecture phase is considered complete when:

- This architecture document is approved and version-controlled
- The primary website structure is understood
- Service and solution boundaries are clear
- Language architecture is clear
- Technology stack is clear
- Public website and application boundaries are clear
- Deployment principles are clear
- Migration principles are clear
- Backup principles are established
- Accessibility requirements are established
- SEO requirements are established
- Performance requirements are established
- Security and privacy requirements are established
- The next Information Architecture phase can proceed without major structural ambiguity

---

## 51. Source-of-Truth Statement

This Markdown file is the authoritative editable Website V2 Architecture document.

Published Word or PDF versions may be generated for formal use, but they must remain synchronized with this source document.