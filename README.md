# SCL-specification
Structured-Cognition-Layer specification
*A new architectural primitive for governing LLM identity, reasoning, and ethical behavior.*

### Cognitive Artifacts
This specification is accompanied by a growing set of **cognitive-artifacts** in `/cognitive-artifacts/` that demonstrate emergent governed behaviors (e.g., jurisdiction‑aware civic reasoning). These are illustrative outputs, not product features.

---

## Overview

The **Structured Cognition Layer (SCL)** is a governance architecture that operates **within the model’s reasoning process**, shaping how a language model interprets its identity, applies rules, adheres to ethical constraints, and generates structured cognitive artifacts.

SCL provides a unified framework for **predictable, auditable, and aligned** model behavior — without exposing or depending on any specific implementation details.

This repository defines the **concept**, **terminology**, and **governance domains** of the Structured Cognition Layer.

---
## Understanding SCL Through a Cognitive Analogy

Modern AI systems can be understood as operating across three distinct layers:

1. **Training → Cognitive Capacity**  
   Training gives a model its general reasoning ability, linguistic competence, and pattern-recognition skills.  
   This is similar to a person’s cognitive capacity: powerful, but not inherently structured or ethical.

2. **Safety Rules → Learned Behaviours**  
   System prompts, policies, and refusal guidelines shape how the model behaves.  
   These function like learned social norms: they influence behaviour but do not provide a structured reasoning process.

3. **Structured Cognition Layer (SCL) → Executive Function**  
   SCL introduces explicit cognitive structure.  
   It defines *how* the model must think—how it reasons, evaluates, justifies, and refuses.  
   This is similar to executive function in humans: deliberate, organized, auditable cognition.

SCL does not modify the model’s training or internal weights.  
Instead, it provides a principled, schema-driven cognitive framework that governs how the model reaches its conclusions.

---
## Why SCL?

Modern LLMs lack a coherent structure for governing:

- who they are  
- how they reason  
- what boundaries they must respect  
- how their decisions can be audited  

Existing approaches rely on ad‑hoc prompts, heuristics, or safety wrappers.  
SCL introduces a **system‑level governance layer** that governs both **behavior** and **cognition**.

---

## Governance Domains

The Structured Cognition Layer consists of three primary governance domains.  
These domains describe *what* is governed — not *how* it is implemented.

### **1. Identity Governance**
Defines and stabilizes the model’s identity, role, and operational boundaries.

Identity Governance ensures:

- consistent role interpretation  
- stable persona and behavior  
- adherence to defined rules  
- respect for operational limitations  

---

### **2. Cognitive Trace Governance**
Structures how the model expresses its internal reasoning.

Cognitive Trace Governance governs:

- decision‑point traces  
- structured reasoning steps  
- internal logic records  
- cognitive artifacts used for auditability  

This domain focuses on the **visibility and structure** of reasoning, not the reasoning mechanism itself.

---

### **3. Ethical Governance**
Enforces ethical constraints and principled refusal behavior.

Ethical Governance ensures:

- adherence to ethical boundaries  
- safety‑aligned decision‑making  
- consistent refusal logic  
- value‑aligned outputs  

---

## What SCL Is Not

SCL is **not**:

- prompt engineering  
- intent engineering  
- interpretability tooling  
- a safety wrapper  
- a system prompt trick  

SCL is a **governance architecture** — a conceptual layer that shapes how the model reasons, decides, and adheres to constraints.

---

## High‑Level Properties

- **Operates within the model’s reasoning process**  
  (without revealing or depending on implementation details)

- **Enforced, not suggested**  
  Governance domains impose structured constraints rather than heuristic nudges.

- **Modular and composable**  
  Each governance domain is conceptually independent yet mutually reinforcing.

- **Model‑agnostic**  
  Applicable to any LLM capable of following structured governance instructions.

- **Implementation‑agnostic**  
  This specification defines the architecture, not the mechanism.

---

## One‑Sentence Definition

> **The Structured Cognition Layer (SCL) is a governance architecture that operates within the model’s reasoning process, enforcing identity, rules, ethical constraints, and structured cognitive trace generation to produce predictable, auditable, and aligned LLM behavior.**

---

## Current Status

This repository defines the **conceptual specification** of the Structured Cognition Layer.  
Implementation details are intentionally omitted.

Future updates may include:

- expanded conceptual diagrams  
- governance domain refinements  
- terminology clarifications  
- architectural notes  

---

## License and Usage Rights
The Structured Cognition Layer (SCL) Specification is licensed under the Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International License (CC BY‑NC‑ND 4.0).
This license allows:
• 	Reading and referencing the specification
• 	Citing the concepts, terminology, and architectural framing
• 	Academic or research discussion of the ideas
This license does not allow:
• 	Commercial use of the specification
• 	Derivative works, modified versions, or re‑implementations of the specification
• 	Redistribution of altered or adapted versions
• 	Use of SCL, Jiminy, Actor Scaffold, or Cognition Logger names in derivative frameworks or products
All implementations of SCL—including Jiminy, Actor Scaffold, Cognition Logger, and any future modules—remain proprietary and are not covered by this license.
For full legal text, see the LICENSE file in this repository.
