# The EU AI Act: What African Companies Need to Know

**Reference:** EU Artificial Intelligence Act (Regulation 2024/1689) | NDPA 2023
**Prepared by:** TrustGrid Technology

---

## Overview

The EU AI Act entered into force on 1 August 2024. It is the world's first comprehensive legal framework specifically regulating artificial intelligence. For African companies building AI products or serving European markets, it is not optional and it is not a future consideration. It is a current legal obligation for many businesses operating today.

This guide explains what the EU AI Act means specifically for African founders, Nigerian fintechs, and compliance professionals advising clients with EU exposure.

---

## Does the EU AI Act Apply to You?

The EU AI Act has extraterritorial reach. It applies to you if:

| Scenario | EU AI Act Applies? |
|---|---|
| Your AI system is deployed in the EU | ✅ Yes |
| Your AI product is used by EU residents | ✅ Yes |
| You provide AI services to EU businesses | ✅ Yes |
| Your AI system affects people located in the EU | ✅ Yes |
| You are based in Africa with no EU users or clients | ❌ No |
| You build AI tools used only within Nigeria | ❌ No |

### Practical examples for African businesses

**Example 1:** A Lagos-based fintech uses an AI credit scoring model that assesses applications from Nigerian users only. The EU AI Act does not apply.

**Example 2:** The same fintech expands to serve users in the UK and Germany. The EU AI Act now applies to how that AI credit scoring model operates for those EU users.

**Example 3:** A Nigerian SaaS company builds an AI-powered HR screening tool and sells it to companies in France and the Netherlands. The EU AI Act applies to that tool regardless of where the Nigerian company is incorporated.

**Example 4:** An African AI startup builds a foundation model and makes it available via API to developers globally including EU developers. The EU AI Act applies.

---

## The Risk-Based Framework

The EU AI Act classifies AI systems into four risk categories. Your obligations depend entirely on which category your AI system falls into.

### Unacceptable Risk — Banned

These AI applications are prohibited entirely under the EU AI Act. No exceptions for African companies.

| Prohibited Application | Why Banned |
|---|---|
| Social scoring systems by governments | Fundamental rights violation |
| Real-time biometric surveillance in public spaces by law enforcement | Privacy and dignity violation |
| AI that exploits vulnerabilities of specific groups | Manipulation and harm |
| AI that subliminally influences behaviour causing harm | Manipulation |
| Predictive policing based solely on profiling | Discrimination and presumption of innocence |

### High Risk — Strictly Regulated

High-risk AI systems are permitted but subject to the strictest requirements. This is the category most relevant to Nigerian fintechs and African businesses.

**High-risk AI categories:**

| Category | Examples Relevant to African Businesses |
|---|---|
| Credit and financial services | AI credit scoring, AI loan decisioning, AI fraud detection used for account restrictions |
| Employment and HR | AI CV screening, AI interview assessment, AI performance monitoring |
| Education | AI that determines access to educational institutions or evaluates students |
| Essential services | AI used in water, gas, electricity, or internet infrastructure |
| Law enforcement | AI used for risk assessment or evidence evaluation |
| Migration and border control | AI used in visa or asylum processing |
| Administration of justice | AI used in court proceedings |
| Critical infrastructure | AI managing critical systems |

**Requirements for high-risk AI systems:**

| Requirement | What It Means |
|---|---|
| Risk management system | Document and mitigate risks throughout the AI lifecycle |
| Data governance | Training data must be relevant, representative, and free from errors |
| Technical documentation | Detailed documentation of the system before it goes to market |
| Record keeping | Automatic logging of events for traceability |
| Transparency | Clear information for users about what the system does |
| Human oversight | Technical design must enable meaningful human monitoring and override |
| Accuracy and robustness | System must be accurate, robust, and cybersecure |
| Conformity assessment | Must pass assessment before deployment, either self-assessment or third party |
| EU database registration | Must be registered in the EU database for high-risk AI systems |

### Limited Risk — Transparency Obligations

AI systems that interact with humans or generate content must disclose that they are AI.

| System Type | Obligation |
|---|---|
| Chatbots and conversational AI | Must disclose they are AI to users |
| AI-generated images, audio, video | Must be labelled as AI-generated |
| Emotion recognition systems | Must inform individuals being assessed |
| Biometric categorisation | Must inform individuals |

### Minimal Risk — No Mandatory Requirements

Most AI applications fall here. Spam filters, AI in video games, basic recommendation systems. No mandatory requirements but voluntary codes of practice are encouraged.

---

## General Purpose AI Models

The EU AI Act introduced specific rules for General Purpose AI (GPAI) models. These are foundation models that can be used for multiple purposes, like GPT-4, Claude, Gemini, and similar large language models.

### What this means for African businesses

**If you use a GPAI model via API:** Your obligations depend on how you deploy it and what risk category your application falls into. Using Claude or GPT-4 to power a customer service chatbot is likely limited risk. Using it to make credit decisions is high risk.

**If you build on top of a GPAI model:** You are responsible for ensuring your application meets the requirements for its risk category. The GPAI provider's compliance does not automatically satisfy your obligations.

**If you develop a GPAI model:** Significant transparency and documentation obligations apply. If your model has systemic risk due to scale or capability, additional requirements including adversarial testing and incident reporting apply.

---

## Implementation Timeline

| Date | Milestone |
|---|---|
| 1 August 2024 | EU AI Act entered into force |
| 2 February 2025 | Prohibited AI practices banned |
| 2 August 2025 | GPAI model rules apply |
| 2 August 2026 | High-risk AI system rules fully apply |
| 2 August 2027 | Some high-risk systems in regulated sectors get additional time |

**What this means:** If your business deploys high-risk AI systems used by EU residents, the full compliance deadline is August 2026. That is now. If you have not started your compliance assessment, you are already late.

---

## EU AI Act vs NDPA: Where They Overlap

Both frameworks apply simultaneously if your AI system processes personal data of Nigerian and EU residents.

| Topic | NDPA 2023 | EU AI Act | Both Apply? |
|---|---|---|---|
| Automated decision making rights | Section 37 | Article 26 (high-risk systems) | ✅ Yes |
| Transparency about AI | Section 27 | Articles 13, 50 | ✅ Yes |
| Human oversight | Section 37 | Article 14 | ✅ Yes |
| Data quality for AI | Data minimisation principle | Article 10 (training data) | ✅ Yes |
| Risk assessment | DPIA requirement | Risk management system (Article 9) | ✅ Yes |
| Incident reporting | Breach notification | Serious incident reporting (Article 73) | ✅ Yes |

Where both frameworks apply, you must satisfy both. In most cases the EU AI Act is more prescriptive and detailed. Building to EU AI Act standards for high-risk systems will generally satisfy NDPA obligations for the same systems.

---

## Penalties

| Violation | Maximum Fine |
|---|---|
| Prohibited AI practices | €35 million or 7% of global annual turnover |
| High-risk system non-compliance | €15 million or 3% of global annual turnover |
| Providing incorrect information to authorities | €7.5 million or 1.5% of global annual turnover |

For SMEs and startups, fines are calculated as the lower of the fixed amount or the percentage of turnover.

---

## Practical Steps for African Businesses

### Step 1: Determine if the EU AI Act applies to you
Map your AI systems against your user base. If any AI system affects EU residents, the Act applies to those systems.

### Step 2: Classify your AI systems by risk
For each AI system that falls under the Act, determine its risk category. High-risk classification triggers the most significant obligations.

### Step 3: Assess your high-risk systems
For each high-risk system, conduct a gap assessment against the requirements in Articles 9-15 of the EU AI Act. Document findings and build a remediation roadmap.

### Step 4: Update your transparency obligations
Ensure all AI systems that interact with users disclose that they are AI. Update privacy notices and terms of service to reflect AI processing.

### Step 5: Implement human oversight
For high-risk systems, ensure meaningful human oversight is built into your workflows. Document the human review process.

### Step 6: Register in the EU database if required
High-risk AI systems must be registered in the EU AI database before deployment to EU users.

### Step 7: Monitor for updates
The EU AI Act is being implemented through delegated acts and guidance that continues to develop. Assign someone to monitor updates from the EU AI Office.

---

## Resources

- EU AI Act full text: eur-lex.europa.eu
- EU AI Office: digital-strategy.ec.europa.eu/en/policies/european-approach-artificial-intelligence
- NDPC guidance on AI: ndpc.gov.ng
- ISO 42001 AI Management System Standard: iso.org

---

*Built by TrustGrid Technology. Reference guide only. Not legal advice. The EU AI Act implementation is ongoing and guidance continues to evolve. Verify current obligations with legal counsel familiar with both EU and Nigerian law.*
