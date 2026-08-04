# SmartSmile Specification

**Together for fair dental care**

---

## Overview

**SmartSmile** is an open-source specification for building transparent, privacy-first dental pricing and practice intelligence platforms.

The specification defines a modular architecture that enables organizations, developers, researchers, advocacy groups, and communities to build interoperable systems for dental pricing transparency, advertised special verification, fraud detection, patient shopping, and AI-assisted analysis.

SmartSmile is designed using a modular, plugin-based architecture, allowing implementations to deploy only the functionality they require while maintaining compatibility with the overall ecosystem.

The specification is designed for deployment throughout the United States and emphasizes patient privacy, encrypted data storage, transparency, interoperability, and community participation.

---

# Design Goals

- Modular architecture
- Privacy-first design
- Anonymous participation
- End-to-end encryption
- AI-assisted analysis
- Open interoperability
- Vendor neutrality
- Community-driven transparency
- Scalable deployments
- Extensible through plugins

---

# Core Modules

## Patient Management

- Anonymous accounts
- Encrypted identities
- Secure authentication
- User preferences
- Notification management

---

## Receipt Management

- Receipt uploads
- OCR extraction
- Payment verification
- Procedure extraction
- Cost extraction
- Receipt validation
- Duplicate detection

---

## Advertising Verification

- Advertisement screenshot uploads
- Flyer uploads
- Website advertisement capture
- Social media advertisement capture
- OCR extraction
- Advertisement archive
- Advertisement vs invoice comparison

---

## Dental Office Registry

- Dental office profiles
- Office locations
- Office ownership
- Corporate affiliations
- Practice history
- Office transparency metrics

---

## Dentist Registry

- Dentist profiles
- Credentials
- Licenses
- Specialties
- Office associations
- Practice history
- Transparency scores

---

## Relationship Mapping

- Dentist-to-office relationships
- Multi-office practices
- Corporate ownership
- Practice groups
- Network visualization

---

## Pricing Intelligence

- Procedure pricing
- Historical pricing
- Regional averages
- Price benchmarking
- Price trend analysis
- Price fluctuation detection

---

## Product Pricing

- Office product pricing
- Retail product pricing
- Online pricing
- Price comparisons
- Markup calculations
- Bargain identification

---

## Advertisement Verification Engine

- Promised services
- Delivered services
- Pricing comparisons
- Promotion verification
- Offer fulfillment tracking

---

## Fraud Detection

- Billing anomaly detection
- Upsell detection
- Pattern analysis
- Repeated complaint analysis
- Trust scoring
- Risk indicators

---

## Diagnostic AI

Supports AI-assisted analysis of:

- Dental X-rays
- Intraoral photographs
- 3D scans
- CBCT imaging

Capabilities include:

- Caries detection
- Crown detection
- Implant detection
- Filling detection
- Missing teeth
- Bone loss
- Periodontal indicators
- Treatment comparison

---

## Patient Shopping Navigator

- Procedure comparison
- Office comparison
- Cost estimation
- Nearby providers
- Transparency rankings
- Trust score rankings
- Bargain identification
- Price alerts

---

## Search Engine

Search by:

- Dentist
- Office
- Procedure
- Product
- City
- ZIP Code
- State
- Specialty
- Price
- Transparency score

---

## Analytics

- Regional pricing
- Historical trends
- Heat maps
- Market analysis
- Procedure statistics
- Transparency statistics
- Community reports

---

## Security

- AES-256 encrypted storage
- TLS encryption
- Encrypted object storage
- Secure key management
- Audit logging
- Access control
- HIPAA-aware architecture
- Anonymous identifiers

---

## API

- REST API
- GraphQL (optional)
- Authentication
- Search endpoints
- Reporting endpoints
- Import/export
- Public datasets
- Plugin API

---

# Optional Plugin Modules

## Insurance Comparison

- Coverage estimation
- Out-of-pocket estimates
- Benefit comparisons
- Claim analysis

---

## Retail Marketplace

- Retail product links
- Alternative suppliers
- Price monitoring
- Shopping recommendations

---

## Mobile Applications

- iOS
- Android
- Push notifications
- Offline submissions
- Camera uploads

---

## Advertisement Crawler

Automatically discovers advertisements from:

- Dental websites
- Facebook
- Instagram
- Google Business Profiles
- Promotional landing pages

---

## AI Language Analysis

- Marketing claim detection
- Misleading language detection
- Offer analysis
- Fine-print extraction
- Consumer readability scoring

---

## Advanced OCR

- Handwritten receipts
- Printed receipts
- Flyers
- Business cards
- Brochures
- Insurance paperwork

---

## Image Recognition

- Product recognition
- Brand recognition
- Logo recognition
- Advertisement classification

---

## Community

- Anonymous discussions
- Office reviews
- Dentist reviews
- Voting
- Reputation scoring

---

## Reporting

Generate reports for:

- Researchers
- Journalists
- Consumer organizations
- Advocacy groups
- Regulatory agencies

---

## Public API

- Third-party integrations
- Data exports
- Research access
- Analytics access

---

## Accessibility

- Screen readers
- Keyboard navigation
- High contrast
- Mobile accessibility
- WCAG compliance

---

## Notification Services

- Price alerts
- New specials
- Fraud alerts
- Office updates
- Product pricing alerts

---

## Data Import

Import data from:

- CSV
- JSON
- XML
- APIs
- Public datasets

---

## Data Export

Export as:

- CSV
- JSON
- XML
- PDF reports

---

# Architecture

SmartSmile follows a modular architecture where each module communicates through standardized APIs and event-driven messaging.

Implementations may deploy only the required modules while remaining compatible with future extensions.

---

# Security

The SmartSmile specification requires:

- Encryption at rest
- Encryption in transit
- Anonymous identifiers
- Secure authentication
- Encrypted file storage
- Audit logging
- Role-based authorization
- Privacy-first architecture

---

**SmartSmile — Together for fair dental care**

---

## Specification Branding License (SBL)
### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/smartsmile/](https://roxanneardary.com/smartsmile/)

---

## License & Notice Requirements

SmartSmile is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- SmartSmile specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
