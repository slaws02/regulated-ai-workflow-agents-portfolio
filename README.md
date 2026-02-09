# Regulated AI Workflow Agents — Portfolio

## Overview

This portfolio demonstrates a structured suite of guardrailed AI workflow agents designed for regulated and process-heavy environments such as healthcare insurance, benefits administration, and compliance-driven operations.

Each agent is knowledge-grounded and designed with safety, structure, and auditability in mind — emphasizing citation, refusal logic, dependency mapping, and QA validation rather than free-form generation.

All examples use synthetic or public demo data only. No proprietary employer or carrier information is included.

---

# Agent Suite

## Agent 1 — Healthcare Benefits Support Navigator
**Purpose:** Rep decision-support agent for complex benefit questions.

**Demonstrates:**
- Knowledge-grounded answering
- Policy citation enforcement
- Missing-information detection
- Escalation safeguards
- Structured response schema
- Rep coaching mode

**Value Pattern:** AI-assisted frontline support with guardrails.

Folder: `/agent-1-benefits`

---

## Agent 2 — Texas State Mandates Navigator
**Purpose:** Regulatory retrieval agent for state healthcare mandate updates.

**Demonstrates:**
- Public regulatory knowledge retrieval
- Scope guardrails
- Effective-date extraction
- Mandate vs operational distinction
- Refusal when unsupported

**Value Pattern:** AI regulatory lookup with compliance controls.

Folder: `/agent-2-texas-mandates`

---

## Agent 3 — AI Workflow Output Auditor
**Purpose:** QA oversight agent that audits AI outputs for safety and correctness.

**Demonstrates:**
- Hallucination risk detection
- Format compliance checks
- Confidence alignment scoring
- Missing-element detection
- Safer rewrite generation
- Structured audit reports

**Value Pattern:** AI governance and reliability layer.

Folder: `/agent-3-qa-auditor`

---

## Agent 4 — Health Plan Implementation Process Navigator
**Purpose:** Implementation workflow agent that generates step-by-step plan configuration and coding procedures.

**Demonstrates:**
- Process decomposition
- Phase-based workflow mapping
- Dependency identification
- Validation checkpoints
- QA test scenario generation
- Operational guardrails

**Value Pattern:** AI-assisted implementation workflow design.

Folder: `/agent-4-plan-implementation`

---

## Agent 5 — Self-Insured Paperwork Navigator
**Purpose:** Paperwork dependency and signatory mapping agent for self-insured (ASO) implementations.

**Demonstrates:**
- Document requirement logic
- Conditional paperwork detection
- Signer role mapping
- Sequencing and dependency modeling
- Missing-input clarification
- Compliance-safe refusal behavior

**Value Pattern:** AI-assisted implementation paperwork navigation.

Folder: `/agent-5-paperwork-navigator`

---

# Shared Knowledge Bases

Portfolio-safe synthetic frameworks used to ground agent behavior:

- Demo Health Policy Guide
- Texas Mandates Demo Framework
- Plan Implementation Process Framework
- Self-Insured Paperwork Framework

Folder: `/knowledge-base`

---

# Evaluation & QA Assets

Includes structured evaluation templates used to test and score agent outputs for:

- Accuracy
- Citation presence
- Hallucination risk
- Format compliance
- Escalation correctness

Folder: `/evaluation`

---

# Design Principles Demonstrated

Across all agents:

- Knowledge grounding over free generation
- Structured output schemas
- Guardrail prompting
- Refusal when unsupported
- Dependency awareness
- Missing-information detection
- QA and audit readiness
- Regulated-environment safety patterns

---

# Target Use Cases

These agent patterns are transferable beyond healthcare to:

- Insurance operations
- Benefits administration
- Compliance workflows
- Implementation projects
- Regulated customer support
- Document-heavy onboarding
- Process-driven service environments

---

# Author Note

This portfolio was built to demonstrate practical AI workflow agent design — not just prompt writing — including guardrails, evaluation logic, and operational structure suitable for enterprise and regulated settings.
