# AI Risk Assessment Template

**Reference:** NDPA 2023 | EU AI Act | ISO 42001
**Prepared by:** TrustGrid Technology
**Version:** 1.0

---

## How to Use This Template

Complete this template before deploying any new AI system or making significant changes to an existing one. The assessment should be completed by the AI governance owner in collaboration with the product, engineering, legal, and compliance teams.

A completed version of this document serves as your primary evidence of due diligence in the event of a regulatory inquiry.

---

## Part 1: System Information

| Field | Details |
|---|---|
| AI System Name | |
| System Description | |
| Business Purpose | |
| System Owner | |
| Technical Contact | |
| Assessment Date | |
| Next Review Date | |
| Assessment Completed By | |
| Version / Release | |
| Deployment Status | Development / Testing / Production |

---

## Part 2: Scope and Data Inventory

### 2.1 What does this AI system do?

Describe in plain language what the AI system does, what decisions it makes or influences, and who is affected by those decisions.

| Question | Answer |
|---|---|
| What is the primary function of this AI system? | |
| What decisions does it make or influence? | |
| Who are the individuals affected by this system? | |
| How many individuals are affected or likely to be affected? | |
| In which countries or jurisdictions does this system operate? | |
| Does this system affect EU residents? | Yes / No |
| Does this system affect Nigerian residents? | Yes / No |

### 2.2 Data Inventory

List all personal data processed by this AI system.

| # | Data Type | Source | Volume | Special Category? | Retention Period |
|---|---|---|---|---|---|
| 1 | | | | Yes / No | |
| 2 | | | | Yes / No | |
| 3 | | | | Yes / No | |
| 4 | | | | Yes / No | |
| 5 | | | | Yes / No | |

### 2.3 Third Party AI Components

| # | Vendor / Tool | Purpose | Data Shared | BAA / DPA in Place? | Security Assessment Done? |
|---|---|---|---|---|---|
| 1 | | | | Yes / No | Yes / No |
| 2 | | | | Yes / No | Yes / No |
| 3 | | | | Yes / No | Yes / No |

---

## Part 3: Regulatory Classification

### 3.1 NDPA Classification

| Question | Answer |
|---|---|
| Does this system process personal data of Nigerian residents? | Yes / No |
| Does this system make automated decisions with legal or significant effects on individuals? | Yes / No |
| Does this system involve profiling of individuals? | Yes / No |
| Is a DPIA required for this system? | Yes / No / Under Review |
| What is the lawful basis for processing under the NDPA? | |
| Has the lawful basis been documented? | Yes / No |

### 3.2 EU AI Act Classification

Complete this section if the system affects EU residents.

| Question | Answer |
|---|---|
| Does this system affect EU residents? | Yes / No |
| Does this system fall into a prohibited category? | Yes / No |
| What risk category does this system fall into? | Unacceptable / High / Limited / Minimal |
| If high risk, which Annex III category applies? | |
| Has a conformity assessment been completed? | Yes / No / Not Required |
| Is registration in the EU AI database required? | Yes / No |

### 3.3 Other Applicable Regulations

| Regulation | Applies? | Notes |
|---|---|---|
| GDPR | Yes / No | |
| CBN AI/fintech guidelines | Yes / No | |
| Sector-specific regulations | Yes / No | Specify: |
| ISO 42001 | Voluntary / Mandatory | |

---

## Part 4: Risk Identification

### 4.1 Risk Rating Scale

| Likelihood | Description |
|---|---|
| High | Likely to occur without controls |
| Medium | Could occur, some controls exist |
| Low | Unlikely given existing environment |

| Impact | Description |
|---|---|
| Critical | Severe harm to individuals, major regulatory penalty, or significant operational disruption |
| High | Significant harm, material regulatory exposure, or serious reputational damage |
| Medium | Moderate harm, manageable regulatory exposure, or moderate reputational impact |
| Low | Minor harm, limited regulatory exposure, or minimal reputational impact |

| Likelihood | Critical Impact | High Impact | Medium Impact | Low Impact |
|---|---|---|---|---|
| High | Critical | High | Medium | Low |
| Medium | High | High | Medium | Low |
| Low | Medium | Medium | Low | Low |

### 4.2 Risk Register

| # | Risk Category | Risk Description | Likelihood | Impact | Risk Level | Existing Controls | Residual Risk |
|---|---|---|---|---|---|---|---|
| 1 | Bias and discrimination | AI system produces discriminatory outputs for certain demographic groups | | | | | |
| 2 | Automated decision making | High-stakes decisions made without meaningful human oversight | | | | | |
| 3 | Data quality | Training data is incomplete, unrepresentative, or historically biased | | | | | |
| 4 | Transparency | Users are not informed that AI is making decisions about them | | | | | |
| 5 | Security | AI system vulnerable to prompt injection or adversarial inputs | | | | | |
| 6 | Data breach | Personal data processed by AI system is exposed or exfiltrated | | | | | |
| 7 | Model drift | AI system accuracy or fairness degrades over time without detection | | | | | |
| 8 | Vendor risk | Third party AI vendor experiences a breach or discontinues service | | | | | |
| 9 | Regulatory non-compliance | System violates NDPA, EU AI Act, or other applicable regulation | | | | | |
| 10 | Hallucination | AI system generates false or misleading outputs that affect individuals | | | | | |
| 11 | | | | | | | |
| 12 | | | | | | | |

---

## Part 5: Security Assessment

### 5.1 Technical Security Controls

| Control | In Place? | Notes |
|---|---|---|
| Access controls restrict who can query or modify the AI system | Yes / No / Partial | |
| API keys and model credentials are stored securely server-side | Yes / No / Partial | |
| Inputs to the AI system are validated and sanitised | Yes / No / Partial | |
| Prompt injection protections are implemented | Yes / No / Partial | |
| AI outputs are monitored for anomalies and unexpected behaviour | Yes / No / Partial | |
| Training data is access-controlled and audited | Yes / No / Partial | |
| Model versioning and rollback capability exists | Yes / No / Partial | |
| AI system is included in penetration testing scope | Yes / No / Partial | |
| Audit logging is enabled for AI system interactions | Yes / No / Partial | |
| Data minimisation applied to AI inputs | Yes / No / Partial | |

### 5.2 OWASP Top 10 for LLMs Assessment

For AI systems using large language models complete this section.

| Risk | Description | Mitigated? | Notes |
|---|---|---|---|
| LLM01 | Prompt injection | Yes / No / Partial | |
| LLM02 | Insecure output handling | Yes / No / Partial | |
| LLM03 | Training data poisoning | Yes / No / Partial | |
| LLM04 | Model denial of service | Yes / No / Partial | |
| LLM05 | Supply chain vulnerabilities | Yes / No / Partial | |
| LLM06 | Sensitive information disclosure | Yes / No / Partial | |
| LLM07 | Insecure plugin design | Yes / No / Partial | |
| LLM08 | Excessive agency | Yes / No / Partial | |
| LLM09 | Overreliance | Yes / No / Partial | |
| LLM10 | Model theft | Yes / No / Partial | |

---

## Part 6: Fairness and Bias Assessment

| Question | Answer | Evidence |
|---|---|---|
| Has the training data been reviewed for historical bias? | Yes / No | |
| Has the system been tested for disparate impact across demographic groups? | Yes / No | |
| Are fairness metrics defined and tracked for this system? | Yes / No | |
| Has the system been tested with adversarial inputs designed to expose bias? | Yes / No | |
| Is there a process to identify and correct biased outputs in production? | Yes / No | |
| Have affected communities or groups been consulted about this system? | Yes / No | |

### Fairness Metrics

Define the specific fairness metrics that will be tracked for this system.

| Metric | Definition | Target | Current Value | Monitoring Frequency |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

---

## Part 7: Human Oversight Assessment

| Question | Answer | Notes |
|---|---|---|
| Does this system make decisions with legal or significant effects on individuals? | Yes / No | |
| Is meaningful human oversight built into the decision workflow? | Yes / No | |
| Do human reviewers have sufficient information to challenge AI decisions? | Yes / No | |
| Do human reviewers have authority to override AI decisions? | Yes / No | |
| Is the human override logged and auditable? | Yes / No | |
| Can individuals request human review of AI decisions that affect them? | Yes / No | |
| Is there an escalation path for contested AI decisions? | Yes / No | |

---

## Part 8: Remediation Plan

For every risk rated Medium or above and every control gap identified, document the remediation action.

| # | Finding | Risk Level | Remediation Action | Owner | Target Date | Status |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |

---

## Part 9: Overall Risk Determination

| Field | Details |
|---|---|
| Overall Risk Rating | Critical / High / Medium / Low |
| Deployment Recommendation | Approved / Approved with conditions / Not approved |
| Conditions for deployment (if applicable) | |
| Residual risks accepted | |
| Risk acceptance authority | |

---

## Part 10: Sign-Off

| Role | Name | Signature | Date |
|---|---|---|---|
| AI Governance Owner | | | |
| Data Protection Officer | | | |
| Technical Lead | | | |
| Legal / Compliance | | | |
| Senior Leadership Sign-off | | | |

---

## Review Log

| Version | Date | Changes | Reviewed By |
|---|---|---|---|
| 1.0 | | Initial assessment | |
| | | | |
| | | | |

---

*Built by TrustGrid Technology. Reference template only. Not legal advice. AI risk assessment requirements vary by jurisdiction, sector, and system type. Engage qualified legal and technical counsel before deploying AI systems in regulated environments.*
