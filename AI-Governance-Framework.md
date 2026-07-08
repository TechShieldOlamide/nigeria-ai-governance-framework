# Nigeria AI Governance Framework

**Reference:** NDPA 2023 | NDPC AI Review 2026 | EU AI Act | ISO 42001
**Prepared by:** TrustGrid Technology
**Last Updated:** 2026

---

## Overview

AI governance is not a separate discipline from data protection and cybersecurity. It sits inside your existing compliance program. The same principles that govern how you handle personal data govern how you build, deploy, and monitor AI systems.

This framework organises AI governance around six pillars. Each pillar maps to existing regulatory obligations under the NDPA 2023 and anticipates the stricter AI-specific rules the NDPC has signalled are coming.

---

## Pillar 1: Accountability

### What it means
Someone in your organisation must own AI governance. Not in theory. In practice. With documented responsibility, authority, and a reporting line to leadership.

### What the NDPA requires
The NDPA requires organisations to demonstrate accountability for how they process personal data. AI systems that process personal data are subject to this accountability obligation from the moment they are deployed.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| AI governance owner designated | A named individual or team is responsible for AI governance across the organisation | ☐ |
| AI inventory maintained | A register of all AI systems in use, their purpose, the data they process, and their risk level | ☐ |
| Board or leadership visibility | Senior leadership is informed about AI systems and their associated risks | ☐ |
| Third party AI assessed | AI tools procured from vendors are assessed before deployment, not just accepted | ☐ |
| Governance policy documented | A written AI governance policy exists and is reviewed annually | ☐ |

### Questions to ask
- Who in our organisation is responsible if an AI system causes harm?
- Do we know every AI tool our teams are using, including tools adopted informally?
- Has leadership approved our use of AI in high-stakes decisions?

---

## Pillar 2: Transparency

### What it means
People affected by AI systems have a right to know that AI is being used, what it is doing, and why. Transparency is not optional under the NDPA. It is a legal requirement.

### What the NDPA requires
Section 27 of the NDPA requires organisations to inform data subjects about automated decision making and profiling. This means your privacy notice must disclose when AI is making or influencing decisions about people.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| Privacy notice updated for AI | Privacy notice discloses all AI-driven processing including profiling and automated decisions | ☐ |
| Plain language explanation | AI systems are explained in language the average user can understand, not technical jargon | ☐ |
| Purpose disclosed | The purpose of each AI system is clearly documented and communicated | ☐ |
| Data sources disclosed | The data used to train or inform AI decisions is documented | ☐ |
| Opt-out mechanism available | Where possible, users can opt out of AI-driven decisions and request human review | ☐ |

### Questions to ask
- Does our privacy notice tell users when AI is making decisions about them?
- Can a user understand what our AI system does if they read our documentation?
- Do we know what data our AI vendor used to train the model we are using?

---

## Pillar 3: Fairness and Non-Discrimination

### What it means
AI systems can perpetuate, amplify, or introduce bias. A credit scoring model trained on biased historical data will produce biased outputs. A hiring tool trained on historical hiring decisions will replicate historical biases. Fairness requires active effort, not passive assumption.

### What the NDPA requires
The NDPA prohibits processing personal data in ways that discriminate unlawfully. AI systems that produce discriminatory outcomes based on protected characteristics violate this obligation regardless of whether the discrimination was intentional.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| Bias assessment conducted | AI systems are assessed for bias before deployment and after major updates | ☐ |
| Training data reviewed | The data used to train AI models is reviewed for historical bias and gaps | ☐ |
| Outcome monitoring in place | Outputs from AI systems are monitored for disparate impact across demographic groups | ☐ |
| Fairness metrics defined | Specific fairness metrics are defined and tracked for each high-risk AI system | ☐ |
| Remediation process exists | A process exists to identify and correct biased outputs | ☐ |

### Questions to ask
- Has our AI system been tested for bias before we deployed it?
- Are we monitoring whether our AI system produces different outcomes for different groups of users?
- What would we do if we discovered our AI system was producing discriminatory outputs?

---

## Pillar 4: Security and Data Protection

### What it means
AI systems introduce new attack surfaces. Prompt injection. Model poisoning. Training data extraction. Adversarial inputs. These are not theoretical risks. They are documented, real-world attack vectors that affect production AI systems today.

### What the NDPA requires
The NDPA requires appropriate technical and organisational measures to protect personal data. AI systems that process personal data must be secured to the same standard as any other system handling that data.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| DPIA completed | A Data Protection Impact Assessment has been completed for all high-risk AI processing | ☐ |
| Prompt injection controls | AI systems that accept user input are tested and protected against prompt injection attacks | ☐ |
| Training data protected | Data used to train AI models is classified, access-controlled, and audited | ☐ |
| Model access controlled | Access to AI models and their outputs is restricted to authorised users and systems | ☐ |
| AI vendor assessed | Third party AI vendors are assessed for security posture before integration | ☐ |
| Output monitoring active | AI outputs are monitored for anomalies, unexpected behaviour, and potential misuse | ☐ |
| Incident response covers AI | The organisation's incident response plan explicitly covers AI system failures and attacks | ☐ |

### Questions to ask
- Have we tested our AI system for prompt injection and adversarial inputs?
- What happens to our users' data when we send it to an AI API?
- Does our incident response plan cover what to do when an AI system behaves unexpectedly?

---

## Pillar 5: Human Oversight

### What it means
AI systems should not make consequential decisions without meaningful human involvement. Meaningful human oversight means a human who has the authority, information, and time to actually review and override an AI decision, not a rubber stamp on an automated output.

### What the NDPA requires
Section 37 of the NDPA grants individuals the right not to be subject to decisions based solely on automated processing when those decisions have legal or significant consequences. This means organisations must build human review into their AI workflows for high-stakes decisions.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| High-stakes decisions identified | All AI decisions with legal or significant consequences are identified and documented | ☐ |
| Human review process defined | A documented process exists for human review of high-stakes AI decisions | ☐ |
| Override mechanism exists | Humans can override AI decisions and the override is logged | ☐ |
| Review is meaningful | Human reviewers have sufficient information, time, and authority to actually challenge AI outputs | ☐ |
| Right to contest implemented | Individuals can request human review of AI decisions that affect them | ☐ |
| Escalation path documented | A clear escalation path exists when AI outputs are contested or unusual | ☐ |

### Questions to ask
- Which decisions in our business are being made by AI without meaningful human review?
- Do our human reviewers have enough context to actually challenge an AI decision, or are they just approving what the model says?
- Can a customer request a human review of an AI decision that affected them?

---

## Pillar 6: Continuous Monitoring and Improvement

### What it means
AI governance is not a one-time exercise. Models drift. Data changes. Regulations evolve. New attack vectors emerge. Governance requires ongoing monitoring, regular review, and a process for continuous improvement.

### What good looks like

| Practice | Description | Status |
|---|---|---|
| AI system register reviewed quarterly | The AI inventory is reviewed and updated at least every quarter | ☐ |
| Model performance monitored | AI model accuracy, fairness, and behaviour are monitored on an ongoing basis | ☐ |
| Regulatory updates tracked | Changes to NDPA, NDPC guidance, EU AI Act, and other relevant regulations are tracked and actioned | ☐ |
| Annual governance review | A formal AI governance review is conducted annually covering all six pillars | ☐ |
| Lessons learned documented | Incidents, near-misses, and audit findings are documented and fed back into governance improvements | ☐ |
| Staff training current | All staff who build, deploy, or use AI systems receive regular training on AI governance obligations | ☐ |

### Questions to ask
- When did we last review whether our AI systems are still behaving as intended?
- How would we know if a model we deployed six months ago has started producing worse or biased outputs?
- Are we tracking changes to AI regulation that could affect our compliance obligations?

---

## Governance Maturity Model

Use this model to assess where your organisation sits today and where you need to get to.

| Level | Description | What it looks like |
|---|---|---|
| Level 1: Unaware | No AI governance in place | AI tools adopted informally, no inventory, no policy, no accountability |
| Level 2: Aware | Basic awareness of AI governance obligations | AI inventory started, privacy notice partially updated, accountability informally assigned |
| Level 3: Developing | Active governance program in place | Policies documented, DPIAs conducted for high-risk systems, human oversight defined |
| Level 4: Managed | Governance is systematic and monitored | Regular reviews, bias monitoring active, incident response covers AI, staff trained |
| Level 5: Leading | Governance is embedded and continuously improving | Board visibility, external audit, contribution to industry standards, proactive regulatory engagement |

Most Nigerian businesses using AI today are at Level 1 or Level 2. The NDPC's announced AI review means Level 3 is the minimum defensible position going forward.

---

## Immediate Actions

If you are reading this and have not started your AI governance program, here are the three things to do first:

1. **Build your AI inventory.** List every AI system your organisation uses, builds, or procures. Include tools your teams have adopted informally. You cannot govern what you cannot see.

2. **Update your privacy notice.** Disclose all AI-driven processing including profiling and automated decision making. This is a current legal obligation under Section 27 of the NDPA, not a future one.

3. **Conduct a DPIA for your highest-risk AI system.** Identify the AI system in your organisation that poses the greatest risk to individuals and complete a Data Protection Impact Assessment before your next regulatory interaction.

---

*Built by TrustGrid Technology. Reference framework only. Not legal advice. AI regulation is evolving rapidly in Nigeria and globally. Verify current obligations with the NDPC and your legal counsel.*
