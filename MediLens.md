# MediLens

**Every Recall. Every Company. Clearly.**  

---

## Overview

**MediLens** is an open-source, real-time global database that tracks pharmaceutical recalls for prescription drugs, biologics, and vaccines. It provides:  

- Detailed medication profiles  
- Official recall information with dates and severity  
- Pharmaceutical company safety assessments  

Our mission is to **promote transparency, public awareness, and accountability** in the pharmaceutical industry. MediLens is **public-facing**, designed for researchers, journalists, healthcare professionals, and anyone interested in drug safety.  

> **Disclaimer:** MediLens is not a substitute for professional medical advice. Always consult healthcare providers for personal medical decisions.  

---

## Features

### Core Database Features
- Track all medications globally (prescription drugs, biologics, vaccines)  
- Official recalls only (FDA, EMA, Health Canada, TGA, WHO, etc.)  
- Medication profiles with recall history and safety scores  
- Pharmaceutical company profiles with total products, total recalls, and safety ratios  
- Real-time updates from official regulatory sources  
- Public-facing dashboards and alerts  
- RSS feeds for recall notifications  
- Historical recall archive  
- Search by medication, company, type, country, or date range  

### Advanced Data & Analytics
- Recall severity heatmaps by country/region  
- Medication risk trends over time  
- Company risk rankings globally or regionally  
- Category-based analysis (biologics vs. vaccines vs. prescription drugs)  
- Regulatory comparison across countries  
- Severity-weighted scoring  
- Regulatory lag detection  
- Supply chain risk analysis  
- Recall clustering by cause  
- Global dosage comparisons  
- Recalls by therapeutic class  

### User Engagement & Public Features
- Custom user alerts (medication, company, country)  
- Alert filtering (severity, region, drug type)  
- Public comments / expert notes (moderated)  
- Customizable dashboards  
- Downloadable reports (CSV, Excel, PDF)  
- Interactive charts (line, pie, bar)  
- Public alert banner for ongoing/high-severity recalls  
- Historical trend graphs  
- Multi-language support  
- Mobile-optimized dashboard  
- Email / SMS notifications  

### Data Enrichment
- Aggregate adverse event summaries  
- Drug interactions and warnings  
- Batch/lot-specific recall tracking  
- Historical enforcement/warning letters  
- Recall impact scoring (patients affected)  

### Security & Compliance
- Data verification pipeline  
- Audit logs for all changes  
- GDPR / privacy compliance  
- Moderated public comments  

### Developer & Integration Tools
- Open API for researchers, journalists, and developers  
- Webhooks for real-time notifications  
- Embeddable widgets for websites  
- Machine-readable RSS feeds  
- APIs for bulk data access  

### AI / Predictive Features
- Recall probability prediction  
- Automated severity classification  
- Trend analytics for recall spikes  
- Natural language processing of recall notes  
- Anomaly detection  
- Predictive dashboards for high-risk categories, companies, or regions  

### Transparency & Accountability
- Company score history over time  
- Recalls vs. market size  
- Public leaderboards for highest/lowest safety ratios  
- Verified citizen reports (optional, separated from official data)  
- Expert annotations from healthcare professionals  
- Community-driven recall tagging  

### Research & Export Tools
- Custom data queries  
- Automated visual reports (PDF, charts)  
- Integration with news feeds  
- Integration with EHR / pharmacy systems  

---

## Installation

MediLens is open-source and can be run locally or deployed on a server.  

1. Clone the repository:  
```bash
git clone https://gitlab.com/Roxanne_Ardary/medilens.git
```
2. Install dependencies (Python / Node / database as required)
3. Configure database and API keys for official regulatory sources
4. Run the application:
```bash
# Example command
python run_server.py
```
5. Access the dashboard via http://localhost:8000 (or your deployed server URL)

## Usage

- Search medications, companies, or countries  
- Subscribe to alerts via dashboard or RSS feed  
- Export recall or safety data for analysis  
- Monitor company safety ratios and trends    

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
  - [https://roxanneardary.com/medilens/](https://roxanneardary.com/medilens/)

---

## License & Notice Requirements

MediLens is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- MediLens specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
---
**MediLens – Every Recall. Every Company. Clearly.**
