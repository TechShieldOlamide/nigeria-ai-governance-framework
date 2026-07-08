# How the NDPA 2023 Already Applies to AI Systems

**Reference:** Nigeria Data Protection Act 2023 | NDPC AI Review June 2026
**Prepared by:** TrustGrid Technology

---

## Overview

A common misconception among Nigerian businesses is that AI regulation does not yet exist in Nigeria and that they can wait for specific AI legislation before thinking about compliance.

This is wrong.

The NDPA 2023 already applies to AI systems through existing provisions on automated decision making, profiling, data minimisation, purpose limitation, and security. The NDPC confirmed this in June 2026 when it announced its AI review, stating that AI is already subject to Nigerian data protection law and that the review is intended to make those obligations more specific and targeted, not to create them from scratch.

This document maps the specific NDPA provisions that apply to AI systems today.

---

## Section 25: Lawful Basis for Processing

### The provision
Every processing activity must have a valid lawful basis. The six lawful bases under the NDPA are consent, contract, legal obligation, vital interests, public task, and legitimate interests.

### How it applies to AI
Every AI system that processes personal data must have a documented lawful basis for that processing. This includes:

- AI models trained on personal data
- AI systems that analyse customer behaviour
- AI tools that process employee data
- AI APIs that receive personal data as inputs
- AI systems that generate outputs about identifiable individuals

### What this means in practice

| AI Use Case | Most Likely Lawful Basis | What You Need |
|---|---|---|
| Credit scoring using customer financial data | Contract or legitimate interests | Documented balancing test if using legitimate interests |
| Fraud detection monitoring transaction patterns | Legitimate interests | Documented balancing test showing fraud prevention overrides privacy intrusion |
| Customer profiling for marketing | Consent | Freely given, specific, informed consent before profiling begins |
| HR screening tools processing employee data | Contract or legal obligation | Clear contractual or statutory basis documented |
| AI chatbot processing user queries | Contract or consent | Disclosed in terms of service or privacy notice |
| Biometric authentication | Explicit consent | Explicit consent required as biometric data is special category |

### Common mistake
Assuming that because an AI vendor processes the data, your organisation has no lawful basis obligation. You do. As the data controller you are responsible for establishing and documenting the lawful basis regardless of who processes the data on your behalf.

---

## Section 27: Transparency About Automated Decision Making

### The provision
Organisations must inform data subjects when their personal data is being used for automated decision making or profiling. This information must be provided in a clear and accessible way.

### How it applies to AI
If your organisation uses AI to make or influence decisions about individuals, those individuals must be told. This is a current legal obligation, not a future one.

### What must be disclosed

| Disclosure Requirement | Example |
|---|---|
| That automated decision making or profiling is taking place | "We use automated systems to assess your creditworthiness" |
| The logic involved in the automated decision | "Our system analyses your transaction history, income patterns, and repayment behaviour" |
| The significance and consequences of the processing | "This assessment influences whether your loan application is approved and at what interest rate" |
| The data sources used | "We use data you provide directly and data from credit bureaus" |

### What this means in practice
Your privacy notice must be updated to include all of this information for every AI system that makes or influences decisions about your users. Generic statements like "we may use your data to improve our services" are not sufficient.

### Common mistake
Burying AI disclosure in dense legal language that the average user cannot understand. The NDPA requires disclosure that is clear and accessible. If a typical user of your product cannot understand what your AI is doing from reading your privacy notice, your disclosure does not meet the standard.

---

## Section 37: Right Not to Be Subject to Solely Automated Decisions

### The provision
Individuals have the right not to be subject to decisions based solely on automated processing when those decisions produce legal effects or similarly significant effects on them.

Exceptions apply where:
- The individual has given explicit consent
- The decision is necessary for entering into or performing a contract
- The decision is authorised by law

Even where an exception applies, individuals retain the right to request human intervention, express their viewpoint, and contest the decision.

### How it applies to AI

| Decision Type | Solely Automated? | Section 37 Applies? |
|---|---|---|
| Loan application rejected by AI with no human review | Yes | Yes |
| Insurance premium set entirely by algorithm | Yes | Yes |
| Job application screened out by AI before any human sees it | Yes | Yes |
| Credit limit reduced by AI fraud detection system | Yes | Yes |
| AI recommendation that a human then reviews and approves | No | No, but human review must be meaningful |
| AI-generated content with no decision about an individual | No | No |

### What meaningful human oversight looks like
Section 37 is satisfied by human involvement only if that involvement is meaningful. A human who approves every AI decision without actually reviewing them does not satisfy the requirement. Meaningful oversight requires:

- The human reviewer has access to the information the AI used
- The human reviewer has sufficient time to review the decision
- The human reviewer has the authority to override the AI
- The human reviewer actually exercises independent judgment

### Common mistake
Building a human review step that is purely cosmetic. If your human reviewer approves 500 AI credit decisions per hour without reading any of them, that is not meaningful human oversight. It is a liability that creates the appearance of compliance without the substance.

---

## Data Protection Impact Assessment Requirement

### The provision
A DPIA is required before undertaking processing that is likely to result in high risk to individuals. The NDPA and GAID identify specific triggers for mandatory DPIAs.

### AI-specific DPIA triggers

| Trigger | Example |
|---|---|
| Large scale processing of special category data | AI health diagnosis tool processing medical records |
| Systematic monitoring of individuals | AI surveillance system monitoring employee behaviour |
| Automated decision making with significant effects | AI credit scoring, AI hiring tool, AI fraud detection |
| Processing of data relating to vulnerable individuals | AI system used in schools, healthcare, or social services |
| Use of new technologies | Any novel AI deployment where the risks are not yet fully understood |
| Processing that prevents individuals from exercising rights | AI content moderation that removes user content |

### What a DPIA for an AI system covers

1. **Description of the processing:** What the AI system does, what data it uses, who it affects
2. **Necessity and proportionality:** Why AI is needed, whether a less privacy-invasive approach would work
3. **Risk assessment:** What could go wrong, how likely it is, how severe the impact would be
4. **Mitigation measures:** What controls are in place to reduce identified risks
5. **Residual risk:** What risk remains after mitigation and whether it is acceptable
6. **Consultation:** Whether affected individuals or groups have been consulted

### Common mistake
Treating the DPIA as a one-time exercise completed before deployment and never revisited. DPIAs must be reviewed when the AI system changes materially, when new risks emerge, or when the regulatory landscape shifts. The NDPC's June 2026 AI review announcement is itself a trigger to review existing DPIAs for AI systems.

---

## Data Minimisation and Purpose Limitation

### The provisions
Personal data must be adequate, relevant, and limited to what is necessary for the specified purpose. Personal data collected for one purpose must not be used for a different, incompatible purpose without a new lawful basis.

### How they apply to AI

**Data minimisation violations in AI:**
- Training an AI model on a full customer database when only a subset of data is needed
- Feeding entire customer profiles into an AI API when only specific fields are relevant
- Retaining training data indefinitely when it is no longer needed for the specified purpose

**Purpose limitation violations in AI:**
- Collecting customer data for service delivery and then using it to train an AI model without disclosure
- Using data collected for fraud detection to build a customer profiling system for marketing
- Sharing customer data with an AI vendor whose model training falls outside the original collection purpose

### What this means in practice
Before you feed personal data into any AI system, ask:
- Is this the minimum data needed for this AI task?
- Is using this data for AI processing compatible with the purpose for which it was collected?
- Have we disclosed this use to the individuals whose data it is?

---

## Penalties for Non-Compliance

AI systems that violate NDPA provisions are subject to the same penalties as
