# AI Governance Glossary

**Reference:** NDPA 2023 | EU AI Act | ISO 42001 | NDPC AI Review 2026
**Prepared by:** TrustGrid Technology

---

## How to Use This Glossary

This glossary defines key terms used in AI governance, the NDPA 2023, and the EU AI Act in plain language. Where a term has a specific legal definition under one or both frameworks, that definition is provided. Where the frameworks use different terminology for the same concept, both are noted.

---

## A

**Accountability**
The principle that organisations are responsible for how they use AI and personal data and must be able to demonstrate that responsibility. Under the NDPA, accountability requires organisations to implement appropriate policies, technical measures, and governance structures and to be able to show regulators that these are working.

**Adversarial Input**
An input deliberately crafted to manipulate an AI system into producing incorrect, harmful, or unintended outputs. Common in attacks against machine learning models and large language models. Also called adversarial examples or adversarial attacks.

**AI Governance**
The set of policies, processes, controls, and accountability structures that ensure AI systems are developed, deployed, and monitored in a responsible, transparent, and compliant manner.

**AI Incident**
Any event involving an AI system that causes or has the potential to cause harm to individuals, regulatory exposure to the organisation, or significant disruption to operations.

**AI Inventory**
A register of all AI systems an organisation uses, builds, or procures. An AI inventory documents the purpose, data, risk level, and oversight mechanisms for each system. Maintaining an AI inventory is a foundational AI governance practice.

**AI Literacy**
The ability to understand what AI systems do, how they work at a conceptual level, and what their limitations and risks are. AI literacy does not require technical expertise but does require sufficient understanding to ask the right questions and make informed decisions about AI use.

**AI System**
Under the EU AI Act, a machine-based system designed to operate with varying levels of autonomy that may exhibit adaptiveness after deployment and that, for explicit or implicit objectives, infers from the input it receives how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments.

**Algorithmic Bias**
Systematic and unfair discrimination in AI outputs resulting from flawed assumptions in the model design, unrepresentative training data, or historical inequalities encoded in the data. Algorithmic bias can affect protected characteristics including race, gender, age, and disability even when those characteristics are not explicitly included as inputs.

**Algorithmic Transparency**
The ability to understand and explain how an AI system reaches its outputs. Full algorithmic transparency is not always technically achievable for complex models but organisations must be able to explain AI decisions in meaningful terms to affected individuals and regulators.

**Automated Decision Making**
A decision made by an automated system without any meaningful human involvement. Under Section 37 of the NDPA and Article 22 of the GDPR, individuals have the right not to be subject to decisions based solely on automated processing when those decisions produce legal or similarly significant effects.

---

## B

**Bias Assessment**
A structured evaluation of an AI system to identify whether it produces systematically unfair or discriminatory outputs for specific groups of individuals. Bias assessments should be conducted before deployment and repeated after significant model updates or when new evidence of bias emerges.

**Black Box AI**
An AI system whose internal decision-making process is not transparent or interpretable even to its developers. Black box AI creates challenges for accountability, explainability, and regulatory compliance particularly in high-stakes decisions.

**Business Associate Agreement (BAA)**
A contract between a data controller and a data processor governing how the processor handles personal data. Required before any vendor including AI vendors can process personal data on behalf of the controller.

---

## C

**Conformity Assessment**
An evaluation of whether a high-risk AI system meets the requirements of the EU AI Act before it is placed on the market or put into service. Some high-risk systems require third party conformity assessment. Others allow self-assessment.

**Consequential Decision**
A decision that significantly affects an individual's circumstances, opportunities, or rights. Examples include loan approval, job application outcomes, insurance pricing, and access to essential services. Consequential decisions made by AI systems require enhanced oversight and transparency obligations.

**Context Window**
In large language models, the amount of text the model can process at one time. Relevant to AI governance because sensitive personal data included in a context window may be processed by the model in ways that create data protection obligations.

---

## D

**Data Drift**
A change in the statistical properties of the data an AI model receives in production compared to the data it was trained on. Data drift can cause model performance to degrade over time and may introduce or amplify bias. Monitoring for data drift is part of ongoing AI governance.

**Data Poisoning**
A type of attack on AI systems where malicious data is introduced into the training dataset to corrupt the model's behaviour. Data poisoning can cause a model to produce incorrect outputs, exhibit bias, or create backdoors that attackers can exploit.

**Data Protection Impact Assessment (DPIA)**
A process to identify and minimise data protection risks before undertaking processing that is likely to result in high risk to individuals. Required under the NDPA and GDPR for high-risk AI processing. The DPIA must be completed before deployment not after.

**Deepfake**
AI-generated synthetic media, typically video or audio, that depicts a real person doing or saying something they did not do or say. Deepfakes raise significant concerns around consent, identity, misinformation, and harm. The EU AI Act requires deepfakes to be labelled as AI-generated.

---

## E

**EU AI Act**
The EU Artificial Intelligence Act (Regulation 2024/1689), which entered into force on 1 August 2024. The world's first comprehensive legal framework specifically regulating artificial intelligence. Applies to AI systems deployed in the EU or affecting EU residents regardless of where the developer is located.

**EU AI Office**
The body established by the European Commission to oversee implementation of the EU AI Act, particularly for general purpose AI models. Coordinates with national market surveillance authorities across EU member states.

**Explainability**
The ability to describe in understandable terms how an AI system reached a particular output or decision. Explainability is distinct from transparency: a system can be transparent about its inputs and processes while still being difficult to explain in human terms. Both are required for meaningful accountability.

---

## F

**Fairness**
In AI governance, the principle that AI systems should not produce systematically different or worse outcomes for individuals based on protected characteristics or membership in specific groups. Fairness is not a single metric but a set of properties that must be defined in the context of each specific use case.

**False Positive**
An incorrect positive output from an AI system. For example, a fraud detection system that flags a legitimate transaction as fraudulent produces a false positive. At scale, false positives in AI systems can cause significant harm to affected individuals.

**Foundation Model**
A large AI model trained on broad data that can be adapted to a wide range of tasks. Also called a General Purpose AI model under the EU AI Act. Examples include GPT-4, Claude, and Gemini. Foundation models are subject to specific transparency and documentation obligations under the EU AI Act.

---

## G

**General Purpose AI (GPAI) Model**
Under the EU AI Act, an AI model trained with a large amount of data using self-supervision at scale that displays significant generality and is capable of performing a wide range of tasks. GPAI models are subject to specific obligations under the EU AI Act including transparency documentation and copyright compliance.

**Governance Framework**
A structured set of policies, processes, roles, and controls that together ensure an organisation manages AI responsibly. A governance framework is not a single document but a system of interconnected elements that work together.

---

## H

**Hallucination**
A phenomenon where an AI system generates outputs that are factually incorrect, fabricated, or nonsensical but presented with apparent confidence. Hallucinations are a known limitation of large language models and create significant risks when AI outputs are relied upon for consequential decisions without human verification.

**High-Risk AI System**
Under the EU AI Act, an AI system that poses significant risks to health, safety, or fundamental rights due to its intended purpose. High-risk systems are listed in Annex III of the EU AI Act and include AI used in credit scoring, employment, education, law enforcement, and critical infrastructure. High-risk systems are subject to the strictest requirements under the Act.

**Human Oversight**
The ability of a human to understand, monitor, and where necessary intervene in or override the operation of an AI system. Under both the NDPA and the EU AI Act, meaningful human oversight is required for automated decisions with significant effects on individuals. Oversight is only meaningful if the human has the authority, information, and time to genuinely challenge AI outputs.

---

## I

**ISO 42001**
The international standard for AI Management Systems published by the International Organization for Standardization. Provides a framework for organisations to establish, implement, maintain, and continually improve responsible AI management. Certification to ISO 42001 is voluntary but demonstrates commitment to AI governance best practice.

---

## L

**Large Language Model (LLM)**
A type of AI model trained on large amounts of text data that can generate, summarise, translate, and reason about text. Examples include GPT-4, Claude, Llama, and Gemini. LLMs are the foundation of many AI products and raise specific governance challenges including hallucination, prompt injection, and data leakage.

**Legitimate Interests**
A lawful basis for processing personal data under the NDPA and GDPR where the organisation has a genuine and proportionate interest in the processing that is not overridden by the rights of the data subject. Using legitimate interests as a lawful basis for AI processing requires a documented balancing test.

---

## M

**Model Drift**
A gradual degradation in AI model performance over time as the real-world data the model encounters in production diverges from its training data. Model drift can cause a previously accurate model to produce incorrect or biased outputs. Regular monitoring is required to detect and address model drift.

**Model Explainability**
See Explainability.

**Model Governance**
The policies and processes that govern how AI models are developed, tested, deployed, monitored, updated, and retired. Model governance is a subset of AI governance focused specifically on the technical lifecycle of AI models.

---

## N

**NDPA 2023**
The Nigeria Data Protection Act 2023. The primary data protection law of Nigeria, signed into law on 12 June 2023. Already applies to AI systems through provisions on automated decision making, profiling, transparency, and data security. The NDPC announced in June 2026 that it is reviewing the Act to address AI more specifically.

**NDPC**
The Nigeria Data Protection Commission. The independent regulatory authority established by the NDPA to enforce data protection law in Nigeria. Announced in June 2026 that it is reviewing the NDPA to incorporate AI-specific provisions.

---

## O

**OWASP Top 10 for LLMs**
A list of the ten most critical security risks for applications built on large language models, published by the Open Web Application Security Project. Includes prompt injection, insecure output handling, training data poisoning, model denial of service, and sensitive information disclosure. A standard reference for AI security assessments.

---

## P

**Privacy by Design**
The principle that data protection and privacy should be built into AI systems
