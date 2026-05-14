# IDDA Unified Boundary Console

> LLM predicts. IDDA admits.

Public-safe PoC demonstrating admissibility-first execution governance for probabilistic and multi-agent AI systems.

This repository presents a conceptual implementation of the IDDA (Intelligent Deterministic Decision Architecture) approach for controlling whether AI-generated candidate actions are admissible for execution under current uncertainty, context, entropy, and cross-layer correlation conditions.

---

## Overview

Modern AI systems can:
- generate plans,
- call tools,
- orchestrate agents,
- modify state,
- and autonomously execute workflows.

However, most architectures still assume that plausible output is automatically executable output.

IDDA introduces an additional governance boundary between:
- probabilistic generation,
- and execution authority.

The demonstrator shows how candidate actions may be:
- evaluated,
- constrained,
- degraded,
- held,
- or blocked

before entering execution.

---

## Core Principle

> Generation may remain probabilistic.  
> Execution authority must remain admissible.

The demonstrator models:
- layered uncertainty,
- admissibility scoring,
- cross-layer instability,
- entropy-aware governance,
- auditability,
- hallucination suppression,
- and execution boundary enforcement.

---

## Demonstrated Concepts

### Admissibility Before Execution
Execution is not granted automatically because an LLM or agent produced an output.

### Layered Reasoning Model
The demonstrator evaluates candidate states across:

- λ0 Data
- λ1 Context
- λ2 Uncertainty
- λ3 Candidate Decision
- λ4 Integration / Cross-layer relation

### Execution Governance
The system may:
- EXECUTE
- EXECUTE WITH CAUTION
- HOLD
- BLOCK EXECUTION

depending on admissibility conditions.

### Multi-Agent Coordination
The PoC includes a simplified orchestration model for:
- Planner agents,
- Tool agents,
- Financial agents,
- Security agents.

### Hallucination Suppression
Candidate claims are compared against observable execution traces before trust is granted.

### Human-Readable Auditability
The demonstrator generates readable execution-boundary audit records instead of raw machine-only traces.

### Public / Protected Runtime Boundary
This repository intentionally separates:
- public-safe demonstrator logic,
from:
- protected runtime mechanics,
- tuning procedures,
- thresholds,
- weighting logic,
- and recovery policies.

---

## What This Repository IS

This repository is:
- a public-safe governance demonstrator,
- a conceptual execution-boundary artifact,
- a readable auditability showcase,
- an admissibility-first orchestration PoC,
- and a semantic reference implementation for IDDA concepts.

---

## What This Repository IS NOT

This repository is NOT:
- a certified safety controller,
- a production runtime,
- a complete IDDA implementation,
- a formal verification environment,
- or a disclosure of protected runtime mechanics.

The following remain intentionally undisclosed:
- production thresholds,
- private scoring logic,
- weighting procedures,
- calibrated recovery models,
- runtime heuristics,
- deployment policies,
- and domain-specific tuning artifacts.

---

## Example Governance Flow

```text
Candidate action generated
        ↓
Layer classification
        ↓
Entropy / uncertainty estimation
        ↓
Cross-layer admissibility evaluation
        ↓
Execution boundary decision
        ↓
Readable audit record
```

---

## Example Outcomes

| State | Meaning |
|---|---|
| NORMAL | Execution admissible |
| CAUTION | Reduced authority / constrained execution |
| HOLD | Preserve stable state pending additional evidence |
| CRITICAL | Block execution and enter deterministic fallback |

---

## Public-Safe Design

This demonstrator intentionally exposes:
- audit structure,
- admissibility semantics,
- governance concepts,
- orchestration flow,
- and execution reasoning visibility.

It intentionally does NOT expose:
- protected coefficients,
- proprietary runtime logic,
- recovery internals,
- production thresholds,
- or certification-grade mechanics.

---

## Suggested Use Cases

The concepts demonstrated here may be relevant to:
- multi-agent orchestration,
- AI governance research,
- execution oversight,
- safety-aware AI pipelines,
- industrial automation,
- autonomous workflows,
- bounded autonomy,
- enterprise audit systems,
- and admissibility-first AI architectures.

---

## Author

Piotr Pietruszewski

Conceptual architecture and admissibility-first governance model.

---

## License

Licensed under the Apache License 2.0.

This repository contains a public-safe demonstrator only and must not be interpreted as disclosure of protected runtime internals or production governance mechanics.
