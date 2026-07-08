# AI Incident Response Plan

**Policy Title:** AI System Incident Response Plan
**Reference:** NDPA 2023 | EU AI Act Article 73 | ISO 42001
**Applies To:** All AI systems deployed by the organisation
**Review Frequency:** Annually or after any AI incident

---

## Purpose

AI systems fail in ways that traditional software does not. A misconfigured database has predictable failure modes. An AI system can produce harmful outputs, exhibit unexpected behaviour, be manipulated through adversarial inputs, or gradually drift from its intended purpose in ways that are difficult to detect until real harm has occurred.

This plan ensures the organisation can identify, contain, assess, and recover from AI incidents quickly and in a way that protects affected individuals, satisfies regulatory obligations, and prevents recurrence.

---

## What Counts as an AI Incident

An AI incident is any event involving an AI system that causes or has the potential to cause harm to individuals, regulatory exposure to the organisation, or significant disruption to operations.

### Incident Categories

**Category 1: Critical**
Immediate harm to individuals or severe regulatory exposure.

| Example | Why Critical |
|---|---|
| AI credit scoring system applies discriminatory criteria affecting thousands of users | Mass discrimination, regulatory breach |
| AI fraud detection system wrongly flags and freezes accounts of legitimate customers at scale | Harm to individuals, potential regulatory action |
| Personal data exfiltrated through prompt injection attack on AI system | Data breach, NDPA notification required |
| AI system makes medical or safety-critical decisions without human oversight | Direct physical harm risk |
| AI system manipulated to produce outputs that harm specific individuals | Targeted harm |

**Category 2: High**
Significant harm to individuals or material regulatory exposure.

| Example | Why High |
|---|---|
| AI system produces biased outputs affecting a subset of users | Discrimination, fairness violation |
| AI vendor experiences a breach involving our users' data | Data breach, third party risk |
| AI system consistently produces factually incorrect outputs that users rely on | Harm through misinformation |
| Human oversight mechanism fails and high-stakes decisions are made without review | Process failure, regulatory risk |
| AI system behaves unexpectedly following an update | Unpredictable outputs, potential harm |

**Category 3: Medium**
Limited harm or moderate regulatory exposure.

| Example | Why Medium |
|---|---|
| AI system produces offensive or inappropriate outputs in isolated cases | Reputational risk, user harm |
| AI system experiences performance degradation affecting user experience | Operational impact |
| Individual user successfully manipulates AI system to bypass intended restrictions | Security concern, limited scope |
| AI system processes data outside its intended scope in isolated cases | Data protection concern |

**Category 4: Low**
Minimal harm or low regulatory exposure.

| Example | Why Low |
|---|---|
| AI system produces unexpected outputs in edge cases with no harm to users | Quality issue |
| AI system documentation is found to be inaccurate | Compliance gap |
| Minor bias detected in AI outputs with no evidence of user harm | Governance gap |

---

## Incident Response Team

| Role | Responsibility | Contact |
|---|---|---|
| AI Incident Commander | Leads the response, makes key decisions, communicates with leadership | |
| Data Protection Officer | Assesses regulatory obligations, manages notification requirements | |
| Technical Lead | Investigates root cause, implements containment and remediation | |
| Legal Counsel | Advises on liability, regulatory exposure, and external communications | |
| Communications Lead | Manages internal and external communications | |
| AI Governance Owner | Coordinates with AI vendors, updates AI inventory, leads post-incident review | |

---

## Response Process

### Phase 1: Detect and Report

**Objective:** Identify that an incident has occurred and report it to the right people immediately.

**Detection sources:**
- User complaints or reports
- Internal monitoring and alerting systems
- Regulatory inquiry or external notification
- Staff observation
- AI vendor notification
- Media or social media reports
- Automated anomaly detection

**Reporting obligation:**
Any staff member who discovers or suspects an AI incident must report it to the AI Governance Owner and Data Protection Officer immediately, the same day.

Do not attempt to investigate or fix the issue alone. Do not delete, alter, or modify AI system logs or outputs without instruction from the Incident Commander.

**Initial report must include:**
- What happened or what is suspected to have happened
- Which AI system is involved
- When the incident was first noticed
- Who has been affected or may be affected
- What immediate steps if any have already been taken

---

### Phase 2: Assess and Classify

**Objective:** Determine the severity of the incident and activate the appropriate response level.

**Assessment questions:**

| Question | Answer |
|---|---|
| Which AI system is involved? | |
| What is the nature of the incident? | |
| When did the incident start? | |
| How many individuals are affected or potentially affected? | |
| What is the nature of the harm or potential harm? | |
| Is the incident ongoing or contained? | |
| Is personal data involved? | |
| Is special category data involved? | |
| Does the incident trigger NDPA breach notification obligations? | |
| Does the incident trigger EU AI Act serious incident reporting? | |
| What is the incident category? | Critical / High / Medium / Low |

**Response activation by category:**

| Category | Response Level | Incident Commander Notified | Leadership Notified | External Notification Considered |
|---|---|---|---|---|
| Critical | Full incident response team activated | Immediately | Within 1 hour | Within 24 hours |
| High | Core team activated | Within 2 hours | Within 4 hours | Within 48 hours |
| Medium | AI Governance Owner and Technical Lead | Within 4 hours | Within 24 hours | As required |
| Low | AI Governance Owner | Within 24 hours | Not required | Not required |

---

### Phase 3: Contain

**Objective:** Stop the incident from causing further harm.

**Containment actions by incident type:**

| Incident Type | Containment Action |
|---|---|
| AI system producing harmful outputs | Suspend the AI system or restrict access until root cause is identified |
| Data breach through AI system | Revoke API keys, block compromised access paths, isolate affected systems |
| Biased or discriminatory outputs | Suspend the AI system, halt all affected decisions, flag cases for human review |
| Prompt injection attack | Block the attack vector, review all recent interactions for compromise |
| AI vendor breach | Revoke vendor access, assess data exposure, contact vendor for incident details |
| Wrongful automated decisions at scale | Suspend the AI system, identify all affected individuals, flag for human review |
| Model drift producing inaccurate outputs | Roll back to previous model version or suspend pending investigation |

**Documentation during containment:**
Every containment action must be logged with the time it was taken, who took it, and what the effect was. This log forms part of the incident record and may be required by regulators.

---

### Phase 4: Investigate

**Objective:** Understand what happened, why it happened, and how far it spread.

**Investigation questions:**

| Question | Answer |
|---|---|
| What was the root cause of the incident? | |
| When did the incident start? | |
| How long did it continue before detection? | |
| What data was involved? | |
| How many individuals were affected? | |
| What harm has been caused? | |
| What systems were affected? | |
| Was the incident caused by internal failure, external attack, or vendor failure? | |
| Were there warning signs that were missed? | |
| What controls failed or were absent? | |

**Evidence preservation:**
Preserve all AI system logs, model outputs, input data, configuration files, and communication records related to the incident. Do not delete or modify any evidence. Evidence may be required for regulatory investigation.

---

### Phase 5: Notify

**Objective:** Meet all regulatory notification obligations and inform affected individuals.

### NDPA Notification Requirements

| Trigger | Who to Notify | Timeframe |
|---|---|---|
| AI incident involves a personal data breach | NDPC | Within 72 hours of becoming aware |
| Affected individuals face high risk from the breach | Affected individuals | Without undue delay |

**NDPC notification must include:**
- Description of the nature of the breach including categories and approximate number of individuals affected
- Contact details of the Data Protection Officer
- Description of the likely consequences of the breach
- Description of the measures taken or proposed to address the breach

### EU AI Act Notification Requirements

For organisations deploying high-risk AI systems that affect EU residents:

| Trigger | Who to Notify | Timeframe |
|---|---|---|
| Serious incident involving a high-risk AI system | Relevant EU market surveillance authority | Immediately upon becoming aware |

A serious incident under the EU AI Act includes any incident resulting in death, serious injury, serious damage to property, or serious disruption of critical infrastructure.

### Individual Notification

Affected individuals must be notified when:
- A personal data breach creates high risk to their rights and freedoms
- An automated decision was made about them based on incorrect or biased AI outputs
- Their data was processed by the AI system in a way that exceeded the disclosed purpose

**Individual notification must include:**
- A plain language description of what happened
- What data was involved
- What the potential consequences are
- What the organisation is doing about it
- How the individual can exercise their rights
- Contact details for further information

---

### Phase 6: Remediate

**Objective:** Fix the root cause and restore normal operations safely.

**Remediation steps:**

| Step | Description | Owner | Status |
|---|---|---|---|
| Root cause addressed | The underlying cause of the incident has been fixed | | |
| Affected individuals remedied | Wrongful decisions reversed, harms addressed where possible | | |
| Controls strengthened | New or improved controls implemented to prevent recurrence | | |
| AI system tested | AI system tested before being returned to production | | |
| Documentation updated | AI inventory, risk assessment, and policies updated to reflect lessons learned | | |
| Staff briefed | Relevant staff briefed on what happened and what has changed | | |

**Return to production checklist:**
- Root cause has been identified and fixed
- All containment measures have been reviewed and adjusted as needed
- AI system has been tested in a non-production environment
- Data Protection Officer has approved return to production
- Monitoring has been enhanced to detect recurrence
- Incident Commander has signed off on return to production

---

### Phase 7: Post-Incident Review

**Objective:** Learn from the incident and prevent recurrence.

A post-incident review must be completed within 14 days of incident closure for Category 1 and 2 incidents and within 30 days for Category 3 incidents.

**Post-incident review must cover:**

| Topic | Questions |
|---|---|
| Timeline | When did the incident start? When was it detected? How long did each response phase take? |
| Root cause | What was the underlying cause? Was it technical, process, or people? |
| Detection | How was the incident detected? Could it have been detected earlier? |
| Response | Was the response effective? What worked well? What did not work? |
| Impact | How many individuals were affected? What harm was caused? What was the regulatory impact? |
| Prevention | What changes would prevent this incident from recurring? |
| Lessons learned | What broader lessons can be applied to other AI systems? |

**Post-incident review output:**
A written post-incident review report must be produced, reviewed by the Data Protection Officer, and presented to senior leadership. The report must include a prioritised list of remediation actions with owners and deadlines.

---

## Incident Log

Every AI incident regardless of category must be logged and retained for a minimum of 6 years.

| Field | Details |
|---|---|
| Incident ID | |
| Date Discovered | |
| Reported By | |
| AI System Involved | |
| Incident Category | Critical / High / Medium / Low |
| Description | |
| Individuals Affected | |
| Data Involved | |
| Containment Actions Taken | |
| Root Cause | |
| NDPA Notification Required | Yes / No |
| NDPA Notification Sent | Date: |
| Individual Notification Required | Yes / No |
| Individual Notification Sent | Date: |
| Remediation Actions | |
| Post-Incident Review Completed | Date: |
| Incident Closed | Date: |
| Closed By | |

---

## Training and Testing

- All members of the AI Incident Response Team must be trained on this plan annually
- A tabletop exercise simulating an AI incident must be conducted at least once per year
- The plan must be reviewed and updated following every Category 1 or 2 incident
- New AI systems must be reviewed against this plan before deployment to ensure incident response coverage is in place

---

## Sign-Off

| Field | Details |
|---|---|
| Plan Owner | |
| Data Protection Officer | |
| Date Approved | |
| Next Review Date | |
| Version | 1.0 |

---

*Built by TrustGrid Technology. Reference plan only. Not legal advice. AI incident response obligations are evolving under Nigerian and international law. Verify current notification requirements with the NDPC, relevant EU authorities, and your legal counsel.*
