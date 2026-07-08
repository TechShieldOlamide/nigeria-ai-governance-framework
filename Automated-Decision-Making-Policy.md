# Automated Decision Making Policy

**Policy Title:** Automated Decision Making and AI Profiling Policy
**Reference:** NDPA 2023 Section 37 | EU AI Act Article 26 | GDPR Article 22
**Applies To:** All staff, products, and systems that use AI to make or influence decisions about individuals
**Review Frequency:** Annually or after any significant change to AI systems or applicable regulation

---

## Purpose

This policy governs how the organisation uses automated decision making and AI-driven profiling. It ensures that individuals affected by automated decisions are treated fairly, informed of their rights, and able to exercise meaningful human review where decisions significantly affect them.

Automated decision making is not inherently wrong. It is efficient, consistent, and scalable. But when it operates without oversight, transparency, or accountability it creates legal exposure and causes real harm to real people.

This policy draws the line between acceptable automation and unacceptable risk.

---

## Scope

This policy applies to:

- All AI systems that make decisions about individuals without human involvement
- All AI systems that inform or influence decisions made by humans about individuals
- All profiling activities that use personal data to evaluate, analyse, or predict aspects of individuals
- All third party AI tools procured by the organisation that make or influence decisions about our users or employees

---

## Definitions

**Automated Decision Making:** A decision made by an automated system without any meaningful human involvement where the decision produces legal effects or similarly significant effects on the individual.

**Profiling:** Any form of automated processing of personal data to evaluate personal aspects of an individual, including analysis of performance, economic situation, health, personal preferences, interests, reliability, behaviour, location, or movements.

**Significant Effect:** An effect that substantially impacts an individual's circumstances, opportunities, or rights. Examples include loan approval or rejection, job application screening, insurance pricing, fraud flags that restrict account access, and credit limit changes.

**Meaningful Human Oversight:** Review by a human who has the authority, information, time, and genuine independence to challenge and override an automated decision. Rubber-stamping is not meaningful oversight.

---

## Policy Rules

### 1. Inventory of Automated Decision Making Systems

The organisation must maintain a current inventory of all automated decision making systems. This inventory must include:

| Field | Description |
|---|---|
| System name | The name of the AI system or tool |
| Purpose | What decisions the system makes or influences |
| Data used | What personal data the system processes |
| Individuals affected | Who is subject to the system's decisions |
| Risk classification | High / Limited / Minimal under EU AI Act where applicable |
| Human oversight mechanism | How human review is implemented |
| Lawful basis | The NDPA lawful basis for this processing |
| Date last reviewed | When this entry was last verified |

The inventory must be reviewed quarterly and updated whenever a new automated decision making system is deployed or an existing system is materially changed.

### 2. Prohibited Automated Decisions

The following automated decisions are prohibited without explicit written approval from the Data Protection Officer and senior leadership:

- Decisions based solely on automated processing that produce legal effects on individuals without any human review mechanism
- Decisions that use special category data as a primary input without explicit consent and a documented lawful basis
- Decisions that apply different treatment to individuals based on protected characteristics without a documented, lawful justification
- Decisions made by AI systems that have not undergone a risk assessment and received deployment approval

### 3. Required Human Oversight for High-Stakes Decisions

The following categories of decision must have meaningful human oversight before the decision is finalised:

| Decision Category | Human Review Required | Review Standard |
|---|---|---|
| Loan or credit application approval or rejection | Yes, always | Reviewer must read the AI reasoning and have authority to override |
| Account restriction or closure due to fraud flags | Yes, always | Reviewer must assess the evidence independently |
| Job application screening or rejection | Yes, always | Human must review before candidate is rejected |
| Insurance premium setting above standard range | Yes, where AI is primary driver | Reviewer must assess the risk factors independently |
| Any decision affecting a vulnerable individual | Yes, always | Enhanced review with additional safeguards |
| Any decision a customer has contested | Yes, always | Fresh human review with full audit trail |

Human review is not satisfied by:
- A reviewer who approves all AI decisions without reading them
- A reviewer who has no authority to override the AI
- A reviewer who lacks the information needed to assess the decision
- A reviewer who is given insufficient time to conduct a genuine review

### 4. Transparency Requirements

Before any individual is subject to automated decision making or profiling, they must be informed of:

| Disclosure | How to Deliver |
|---|---|
| That automated decision making or profiling is taking place | Privacy notice and at point of data collection |
| The logic of the automated system in plain language | Privacy notice and product documentation |
| The significance and likely consequences of the processing | Privacy notice |
| The data sources used by the system | Privacy notice |
| Their right to request human review | Privacy notice and in any decision notification |
| Their right to contest a decision | Privacy notice and in any decision notification |
| Contact details for exercising rights | Privacy notice and in any decision notification |

### 5. Individual Rights

Every individual subject to automated decision making has the following rights which the organisation must be able to fulfil:

**Right to human review**
Any individual who has been subject to an automated decision with significant effects may request a human review of that decision. The request must be acknowledged within 5 business days and the human review completed within 30 days.

**Right to express their viewpoint**
Before a final decision is made following human review, the individual must be given the opportunity to provide additional information or context that may affect the outcome.

**Right to contest the decision**
The individual may formally contest the decision. The contestation must be reviewed by a human with authority to change the outcome. The outcome of the contestation must be communicated to the individual in writing.

**Right to explanation**
The individual may request a meaningful explanation of how the automated decision was reached. The explanation must be specific to their case, not a generic description of the system.

### 6. Bias Monitoring

All automated decision making systems must be monitored for bias on an ongoing basis.

| Monitoring Requirement | Frequency | Responsible Party |
|---|---|---|
| Review of decision outcomes by demographic group | Quarterly | AI Governance Owner |
| Comparison of approval and rejection rates across groups | Quarterly | AI Governance Owner |
| Review of customer complaints related to automated decisions | Monthly | Compliance Team |
| Full bias assessment of the AI model | Annually or after major model updates | Technical Lead and AI Governance Owner |

Where bias is detected the system must be taken offline or restricted until the bias is corrected. The detection and remediation must be documented.

### 7. Third Party AI Systems

When the organisation uses a third party AI system that makes or influences decisions about our users or employees:

- A vendor security and compliance assessment must be completed before deployment
- A Data Processing Agreement must be in place before any personal data is shared
- The vendor must provide sufficient information about the AI system to satisfy our transparency obligations to affected individuals
- The vendor's AI system must be included in our automated decision making inventory
- Our human oversight requirements apply regardless of whether the AI is built internally or procured externally

### 8. Special Protections for Vulnerable Individuals

Where automated decision making affects individuals who may be vulnerable including minors, elderly individuals, individuals with disabilities, or individuals in financial distress:

- Enhanced human oversight is required for all decisions
- Decisions must be reviewed by a senior member of the relevant team before being finalised
- Additional care must be taken to ensure the individual understands their rights and how to exercise them
- The organisation must consider whether automated decision making is appropriate at all for this population

---

## Governance

| Role | Responsibility |
|---|---|
| AI Governance Owner | Maintains the automated decision making inventory, oversees bias monitoring, approves new systems |
| Data Protection Officer | Reviews this policy annually, advises on NDPA and GDPR compliance, receives escalations |
| Technical Lead | Implements human oversight mechanisms, conducts bias assessments, manages model monitoring |
| Compliance Team | Reviews customer complaints, tracks regulatory developments, supports DPO |
| Senior Leadership | Approves high-risk automated decision making systems, receives governance reports |

---

## Escalation

The following situations must be escalated to the Data Protection Officer immediately:

- Discovery that a high-stakes automated decision has been made without human oversight
- Detection of significant bias in an AI system's outputs
- A customer complaint alleging discrimination by an automated system
- A regulatory inquiry related to automated decision making
- A security incident affecting an AI system that makes decisions about individuals
- Discovery that a third party AI vendor has experienced a breach involving our users' data

---

## Violations

Any staff member who:
- Deploys an automated decision making system without completing the required risk assessment
- Bypasses the human oversight requirement for high-stakes decisions
- Fails to respond to an individual's request for human review within the required timeframe
- Suppresses or ignores evidence of bias in an AI system

is subject to disciplinary action as outlined in the organisation's HR policy, up to and including termination.

---

## Review and Updates

This policy must be reviewed:
- Annually by the Data Protection Officer
- After any significant change to AI systems used by the organisation
- After any regulatory update affecting automated decision making obligations
- After any incident involving an automated decision making system
- Following the NDPC's finalisation of AI-specific guidance under its ongoing review

---

## Sign-Off

| Field | Details |
|---|---|
| Policy Owner | |
| Data Protection Officer | |
| Date Approved | |
| Next Review Date | |
| Version | 1.0 |

---

*Built by TrustGrid Technology. Reference template only. Not legal advice. Automated decision making obligations are evolving rapidly under Nigerian and international law. Verify current requirements with the NDPC and your legal counsel before finalising this policy.*
