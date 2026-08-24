# Therovia
**Because the World Has More Treatment Options.**
- HTML Mirror:  [https://roxanneardary.com/therovia-specification/](https://roxanneardary.com/therovia-specification/)  

---

## Specification

Therovia is an AGPL-3.0+ open source specification for a global AI-powered treatment intelligence system designed to discover, organize, compare, verify, and continuously update information about treatments and potential cures for diseases worldwide.

Therovia is designed to search beyond the treatment options approved by a patient's local government or regulatory authority. It can identify approved treatments, off-label treatments, investigational therapies, clinical trials, compassionate-use programs, expanded-access pathways, Right to Try pathways, foreign-approved treatments, traditional medicines, experimental approaches, emerging therapies, and other documented treatment possibilities.

Therovia does not equate discovery with effectiveness, regulatory approval, safety, or availability. Every treatment is classified according to its evidence, regulatory status, safety profile, geographic availability, and applicable access pathway.

## Mission

Therovia exists to make the world's treatment knowledge discoverable.

A treatment should not disappear from consideration simply because it is:

- Developed in another country
- Not approved in the patient's country
- Approved for another indication
- Still under investigation
- Available only through a clinical trial
- Available through compassionate use
- Available through expanded access
- Potentially accessible through a Right to Try pathway
- Considered traditional or complementary medicine
- Newly discovered
- Poorly indexed
- Experimental
- Supported by preliminary evidence

Therovia shall present these possibilities with clear evidence and status classifications rather than treating them as equivalent medical options.

## Design Principles

Therovia shall follow these principles:

- Global treatment discovery
- Evidence transparency
- Source provenance
- Regulatory neutrality
- Patient-centered information access
- Jurisdiction-aware access information
- Human clinical oversight
- Continuous research
- Explicit uncertainty
- Transparent AI reasoning
- Modular architecture
- Open source interoperability
- Vendor neutrality
- Auditable data
- Privacy-conscious design
- No unsupported claims of cures
- No assumption that government approval equals medical effectiveness
- No assumption that lack of government approval equals ineffectiveness

## Core Modules

### Global Treatment Database

The Global Treatment Database maintains structured records for treatments and treatment approaches identified through authoritative, academic, clinical, historical, traditional, and other appropriately sourced information.

Treatment records may include:

- Treatment name
- Generic name
- Brand name
- Active ingredients
- Biological products
- Medical devices
- Procedures
- Surgical interventions
- Radiation treatments
- Cellular therapies
- Gene therapies
- Immunotherapies
- Vaccines
- Metabolic interventions
- Dietary interventions
- Traditional medicines
- Herbal medicines
- Complementary therapies
- Integrative therapies
- Experimental therapies
- Treatment combinations
- Treatment protocols
- Treatment sequences

Each record shall maintain its source, jurisdiction, evidence classification, regulatory status, availability, safety information, and verification history.

### Disease Knowledge Graph

The Disease Knowledge Graph connects diseases with their known characteristics and treatment relationships.

The module shall support:

- Diseases
- Disease subtypes
- Stages
- Severity
- Molecular characteristics
- Genetic characteristics
- Biomarkers
- Mutations
- Symptoms
- Comorbidities
- Treatment relationships
- Treatment responses
- Resistance patterns
- Disease progression
- Recurrence
- Remission
- Potentially curative approaches

The knowledge graph shall allow the AI to identify treatments relevant to specific disease characteristics rather than relying exclusively on broad disease names.

### Evidence Engine

The Evidence Engine evaluates and classifies the available evidence for each treatment.

Evidence classifications may include:

- Regulatory approval
- Clinical guideline recommendation
- Randomized controlled trial
- Prospective clinical study
- Retrospective clinical study
- Systematic review
- Meta-analysis
- Observational study
- Case series
- Case report
- Preclinical evidence
- Laboratory evidence
- Animal research
- Mechanistic evidence
- Historical evidence
- Traditional-use evidence
- Expert opinion
- Anecdotal evidence
- Unsupported claim

The system shall preserve conflicting evidence and shall not automatically interpret a positive result as proof of effectiveness.

### Source Provenance Engine

The Source Provenance Engine records where treatment information originated.

Records should include:

- Source
- Source type
- Author
- Organization
- Publication date
- Jurisdiction
- Publication identifier
- Source URL
- Evidence type
- Extraction date
- Verification date
- Source reliability
- Conflicting sources
- Retraction status
- AI interpretation
- Confidence level

Users shall be able to trace significant treatment claims back to their underlying sources.

### Regulatory Status Engine

The Regulatory Status Engine records treatment approval and regulatory status independently for each jurisdiction.

A treatment may simultaneously be:

- Approved in one country
- Investigational in another
- Unavailable in another
- Approved for another indication
- Available through a clinical trial
- Available through compassionate use
- Available through expanded access

The system shall never treat lack of approval in a particular jurisdiction as evidence that the treatment does not exist.

### Jurisdiction Engine

The Jurisdiction Engine maintains information about country-specific treatment regulations and access pathways.

It may track:

- Regulatory authorities
- Approval requirements
- Clinical trial access
- Compassionate-use rules
- Expanded-access rules
- Experimental treatment rules
- Special access programs
- Physician requirements
- Hospital requirements
- Manufacturer requirements
- Importation requirements
- Patient eligibility
- Documentation requirements
- Emergency access provisions

Jurisdictional information shall be time-stamped and continuously updated because laws and policies change.

### Treatment Matching Engine

The Treatment Matching Engine compares available treatment information against user-provided disease information.

Potential matching attributes include:

- Diagnosis
- Disease subtype
- Stage
- Biomarkers
- Mutations
- Prior treatments
- Treatment responses
- Treatment failures
- Medications
- Allergies
- Contraindications
- Patient characteristics
- Treatment goals
- Geographic location
- Applicable jurisdiction

The engine shall identify potentially relevant treatment information without representing the result as an autonomous medical prescription.

### Treatment Comparison Engine

The Treatment Comparison Engine allows users to compare treatment options using structured attributes.

Comparison factors may include:

- Mechanism
- Disease indication
- Disease subtype
- Evidence quality
- Clinical outcomes
- Response rates
- Remission data
- Survival data
- Adverse effects
- Contraindications
- Regulatory status
- Countries of approval
- Countries of availability
- Clinical trial availability
- Access pathways
- Treatment duration
- Treatment location
- Manufacturer
- Physician requirements
- Known access barriers
- Cost information where reliably available

The system shall display the underlying factors rather than reducing treatment decisions to an unexplained single score.

### Safety Engine

The Safety Engine identifies and classifies known and suspected treatment risks.

The system shall track:

- Adverse effects
- Serious adverse effects
- Contraindications
- Drug interactions
- Treatment interactions
- Organ-specific risks
- Pregnancy-related risks
- Age-related risks
- Genetic risks
- Biomarker-specific risks
- Dosing uncertainty
- Manufacturing concerns
- Contamination concerns
- Quality-control concerns
- Counterfeit-product risks
- Treatment withdrawals
- Safety warnings

Experimental, traditional, natural, or foreign-approved status shall never be interpreted as proof of safety.

### Clinical Trial Engine

The Clinical Trial Engine identifies clinical trials associated with diseases and treatments.

The module shall track:

- Trial title
- Trial identifier
- Sponsor
- Treatment
- Disease
- Eligibility requirements
- Trial phase
- Recruitment status
- Locations
- Contact information
- Study dates
- Primary outcomes
- Secondary outcomes
- Published results
- Trial history

The system shall distinguish between active recruitment, completed studies, terminated studies, suspended studies, and studies with unavailable recruitment information.

### Access Pathway Engine

The Access Pathway Engine identifies potential legal and clinical pathways through which a patient may obtain an investigational or otherwise restricted treatment.

Pathways may include:

- Right to Try
- Expanded access
- Compassionate use
- Named-patient access
- Individual patient access
- Emergency access
- Special access programs
- Clinical trials
- Physician-requested access
- Manufacturer access programs
- Hospital-based investigational protocols
- Jurisdiction-specific experimental treatment pathways

The system shall distinguish between:

- Existence of a pathway
- Potential eligibility
- Confirmed eligibility
- Application requirements
- Physician requirements
- Manufacturer participation
- Regulatory requirements
- Institutional requirements
- Actual treatment availability

The system shall never claim that a patient has a legal right to obtain a treatment unless that conclusion is supported by applicable law and current authoritative information.

### Right to Try Module

The Right to Try module shall identify applicable Right to Try laws and eligibility requirements where such laws exist.

The module shall:

- Identify the relevant jurisdiction
- Identify applicable eligibility criteria
- Identify qualifying investigational treatments
- Identify relevant treatment developers
- Identify required physician participation
- Identify required patient documentation
- Identify applicable regulatory requirements
- Identify known limitations
- Identify whether manufacturer participation is required
- Display the date on which the legal information was verified

Right to Try shall not be treated as a universal international access mechanism.

### Expanded Access Module

The Expanded Access Module shall identify expanded-access and compassionate-use mechanisms applicable to investigational treatments.

The module shall identify:

- Eligibility requirements
- Treatment eligibility
- Physician requirements
- Manufacturer participation
- Regulatory applications
- Institutional requirements
- Emergency procedures
- Documentation
- Jurisdiction
- Current status

### Cure Discovery Engine

The Cure Discovery Engine distinguishes between different meanings of treatment success.

Classifications may include:

- Documented cure
- Durable remission
- Long-term disease control
- Partial response
- Temporary response
- Symptom management
- Preventive intervention
- Potentially curative treatment
- Experimental curative approach
- Proposed cure
- Anecdotal cure claim
- Unsupported cure claim

The system shall not classify a treatment as a cure merely because a source or organization uses the word "cure."

### AI Research Agent

The AI Research Agent continuously searches for new information.

It shall identify:

- New treatments
- New clinical trials
- Trial results
- Regulatory approvals
- Regulatory withdrawals
- Safety warnings
- Expanded-access programs
- Compassionate-use programs
- New treatment guidelines
- New biomarkers
- New treatment combinations
- Emerging therapies
- New research
- New evidence concerning existing treatments

The system shall maintain historical changes rather than silently replacing previous records.

### Treatment Claim Verification Engine

The Treatment Claim Verification Engine evaluates claims made about treatments.

It shall identify potential:

- Unsupported cure claims
- Fraudulent treatment claims
- Fabricated studies
- Fabricated clinical trials
- Retracted studies
- Misleading marketing
- Conflicts of interest
- Duplicate publications
- Outdated treatment information
- Contradictory evidence
- Treatments withdrawn for safety reasons

The system shall distinguish between the existence of a claim and evidence supporting that claim.

### Global Access Map

The Global Access Map provides geographic information about treatment availability.

The map may display:

- Countries where treatment is approved
- Countries where treatment is investigational
- Clinical trial locations
- Compassionate-use programs
- Expanded-access programs
- Participating manufacturers
- Treatment centers
- Specialized physicians
- Access requirements
- Geographic restrictions

### Patient Autonomy Engine

The Patient Autonomy Engine provides users with information needed to investigate treatment possibilities and discuss them with qualified healthcare professionals.

The system shall allow users to:

- Search treatments
- Compare treatments
- Review evidence
- Review safety information
- Explore international treatment options
- Explore clinical trials
- Explore access pathways
- Identify questions to discuss with clinicians
- Track treatments under consideration
- Review changes in evidence

The system shall not replace professional diagnosis, prescribing, or clinical judgment.

### Human Verification Engine

The Human Verification Engine provides workflows for review of high-risk or disputed treatment information.

Potential reviewers include:

- Physicians
- Pharmacists
- Clinical researchers
- Regulatory specialists
- Medical librarians
- Medical subject-matter experts

Human review shall be auditable and shall preserve the distinction between AI-generated analysis and human verification.

### Data Freshness Engine

The Data Freshness Engine monitors the age and reliability of time-sensitive information.

Priority rechecks shall include:

- Regulatory status
- Clinical trial recruitment
- Treatment availability
- Safety warnings
- Manufacturer access programs
- Compassionate-use programs
- Expanded-access programs
- Treatment guidelines
- Legal access requirements

Each record shall maintain a last-verified date.

### Audit and Verification Engine

The Audit and Verification Engine maintains a complete history of important changes.

The system shall track:

- Record creation
- Record modification
- Source changes
- Evidence changes
- Regulatory changes
- Safety changes
- Treatment classification changes
- Human reviews
- AI-generated assessments
- Corrections
- Retractions
- Conflicting evidence

Users shall be able to determine how and why an important treatment record changed.

## Optional Plugin Modules

Therovia shall support optional plugins that extend the core treatment intelligence system without requiring every deployment to install every specialized capability.

### Cancer Intelligence Plugin

Provides specialized treatment discovery for:

- Solid tumors
- Hematological cancers
- Rare cancers
- Molecular cancer subtypes
- Stage-specific treatment
- Biomarker-specific treatment
- Experimental oncology
- Cancer clinical trials
- Cancer treatment combinations

### Rare Disease Intelligence Plugin

Provides specialized discovery for rare diseases, orphan treatments, rare disease clinical trials, specialty treatment centers, and international treatment programs.

### Genetic Disease Intelligence Plugin

Provides treatment discovery based on genetic mutations, inherited diseases, gene-specific interventions, gene therapies, and precision medicine.

### Precision Medicine Plugin

Provides biomarker-driven treatment matching and molecular treatment discovery.

### Drug Repurposing Plugin

Identifies existing drugs being investigated or used for diseases beyond their original indications.

The plugin shall clearly distinguish approved indications from off-label and investigational uses.

### Traditional Medicine Plugin

Provides structured information about traditional, complementary, and integrative medicine.

Traditional use shall remain distinct from clinical evidence.

### Indigenous Knowledge Plugin

Provides support for appropriately sourced indigenous treatment knowledge while respecting cultural attribution, intellectual property, community rights, access restrictions, and applicable ethical requirements.

### Medical Travel Plugin

Identifies international treatment centers, specialty hospitals, physicians, treatment programs, and jurisdiction-specific access information.

The plugin shall not represent geographic availability as a recommendation of treatment.

### Treatment Cost Intelligence Plugin

Tracks publicly available treatment cost information, including:

- Medication costs
- Treatment costs
- Clinical trial costs
- Travel-related treatment costs
- Access program costs
- Insurance information where available

Cost information shall include its source and date.

### Pharmaceutical Pipeline Plugin

Tracks investigational treatments and development pipelines maintained by pharmaceutical and biotechnology organizations.

### Gene Therapy Plugin

Provides specialized discovery for gene replacement, gene editing, gene silencing, and other gene-based therapies.

### Cell Therapy Plugin

Provides specialized discovery for cellular therapies, stem-cell-based interventions, immune-cell therapies, and related investigational approaches.

### Medical Device Plugin

Provides treatment intelligence for medical devices, diagnostic technologies, implantable technologies, therapeutic devices, and investigational devices.

### Infectious Disease Plugin

Provides specialized treatment discovery for infectious diseases, antimicrobial therapies, antiviral therapies, antifungal therapies, antiparasitic therapies, vaccines, and emerging infectious diseases.

### Neurological Disease Plugin

Provides specialized treatment discovery for neurological and neurodegenerative diseases.

### Cardiovascular Disease Plugin

Provides specialized treatment discovery for cardiovascular diseases and cardiovascular interventions.

### Autoimmune Disease Plugin

Provides specialized treatment discovery for autoimmune and inflammatory diseases.

### Pediatric Treatment Plugin

Provides specialized treatment intelligence for pediatric diseases while applying age-specific safety and regulatory requirements.

### Veterinary Medicine Plugin

Provides a separate treatment intelligence layer for veterinary diseases and animal medicine.

## Global Source Integration

Therovia should integrate information from a broad range of sources, including:

- Government regulatory agencies
- National health authorities
- International health organizations
- Clinical trial registries
- Academic publications
- Medical journals
- Universities
- Hospitals
- Research institutions
- Pharmaceutical companies
- Biotechnology companies
- Medical device companies
- Treatment guidelines
- Systematic reviews
- Meta-analyses
- Case reports
- Historical medical literature
- Traditional medicine sources
- Pharmacopoeias
- Patents
- Preprints
- Conference publications
- Publicly documented experimental programs

Sources shall be classified by type and reliability.

## Global Regulatory Independence

Therovia shall not restrict treatment discovery to a single regulatory authority.

The system shall maintain independent regulatory records for different jurisdictions.

Regulatory approval shall be treated as one attribute of a treatment rather than the sole determinant of whether the treatment is included.

## Evidence and Regulatory Separation

Therovia shall maintain separate classifications for:

- Evidence
- Safety
- Regulatory approval
- Availability
- Legal access
- Clinical recommendation
- Patient compatibility

A treatment may have substantial evidence without local approval.

A treatment may have regulatory approval without being appropriate for a particular disease subtype.

A treatment may be legally accessible without having strong evidence.

The system shall preserve these distinctions.

## Safety and Medical Responsibility

Therovia is an information and treatment discovery system and shall not function as an autonomous prescribing authority.

The system shall not:

- Fabricate treatments
- Fabricate clinical trials
- Fabricate regulatory approvals
- Fabricate physicians
- Fabricate treatment centers
- Fabricate access programs
- Present experimental treatments as proven cures
- Hide known safety concerns
- Present anecdotes as clinical evidence
- Present foreign approval as proof of local legality
- Present Right to Try as universally applicable
- Provide false certainty about treatment outcomes

High-risk treatment information shall be clearly identified and supported by source provenance.

## Privacy

Patient-specific treatment matching shall follow privacy-conscious principles.

The system should minimize collection of personally identifiable information and should support local processing where technically feasible.

Patient information shall not be used for unrelated purposes without appropriate authorization.

## Interoperability

Therovia shall support interoperable data exchange with:

- Medical databases
- Clinical trial registries
- Regulatory databases
- Research repositories
- Treatment centers
- Pharmaceutical databases
- Patient applications
- Physician applications
- Health information systems

The architecture shall avoid dependency on a single vendor, database provider, government, pharmaceutical company, or AI provider.

## API

Therovia should provide APIs for:

- Disease discovery
- Treatment discovery
- Evidence retrieval
- Regulatory status
- Treatment comparison
- Clinical trials
- Access pathways
- Jurisdiction information
- Source provenance
- Treatment safety
- Geographic availability
- AI research results

API responses should preserve provenance and treatment classifications.

## AI Transparency

AI-generated information shall be distinguishable from source information.

The system should expose:

- Sources consulted
- Evidence supporting conclusions
- Confidence
- Conflicting evidence
- Data freshness
- Regulatory status
- AI-generated interpretation
- Human verification status

The AI shall not conceal uncertainty when evidence is incomplete or contradictory.

## Treatment Opportunity Analysis

Therovia may calculate treatment opportunity profiles using separately displayed factors including:

- Evidence
- Potential benefit
- Safety
- Treatment compatibility
- Availability
- Regulatory status
- Access pathway
- Geographic accessibility
- Clinical trial availability
- Treatment urgency

No single composite score shall replace the underlying information.

## International Treatment Discovery

Therovia shall allow users to discover treatment options from outside their home country.

International discovery may include:

- Foreign-approved treatments
- Clinical trials
- Investigational therapies
- Specialty treatment centers
- Compassionate-use programs
- Expanded-access programs
- Named-patient programs
- Special access programs
- Experimental treatment programs

International availability shall not be interpreted as legal permission to import or receive a treatment in another jurisdiction.

## Terminal and Life-Threatening Disease Mode

Therovia shall provide a specialized mode for serious, life-threatening, terminal, rapidly progressive, or treatment-resistant disease.

This mode may broaden treatment discovery to include:

- Investigational therapies
- Clinical trials
- Expanded access
- Compassionate use
- Foreign-approved therapies
- Off-label therapies
- Experimental therapies
- Emerging therapies
- Treatment combinations
- Precision medicine
- Rare disease programs
- Potentially curative approaches

The system shall clearly identify evidence limitations and access requirements.

## Cure Classification

Therovia shall use strict definitions when describing cures.

A documented cure shall require appropriate supporting evidence.

The system shall distinguish cure from:

- Remission
- Long-term disease control
- Symptom reduction
- Temporary response
- Disease stabilization
- Preventive intervention
- Experimental potential
- Anecdotal claims

No treatment shall be labeled a cure solely because an organization, manufacturer, practitioner, publication, or user describes it as one.

## Community Contributions

The system may support community contributions to treatment records, sources, corrections, translations, and jurisdictional information.

Community-submitted information shall be identified as such and shall pass appropriate validation processes before being classified as verified information.

## Governance

Therovia governance shall define processes for:

- Source inclusion
- Source evaluation
- Evidence classification
- Treatment classification
- Safety classification
- Regulatory classification
- Conflict resolution
- Corrections
- Retractions
- Human review
- AI-generated information
- Community contributions
- Data quality
- Legal access information

All significant classification changes should remain auditable.

## Mission Statement

**Therovia: Because the World Has More Treatment Options.**

Therovia is designed to expand treatment discovery beyond geographic, regulatory, and information boundaries while preserving the distinctions necessary for responsible medical information.

Its fundamental principle is:

**Discover everything. Distinguish everything. Verify everything.**

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
  - [https://roxanneardary.com/therovia/](https://roxanneardary.com/therovia/)  

---

## License & Notice Requirements

Therovia is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to any Open Arsenal project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.
- Therovia specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
