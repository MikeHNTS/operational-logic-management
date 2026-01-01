# Operational Logic Management (OLM)

**How to manage business-critical logic created outside IT systems**

Operational Logic Management (OLM) is an open reference framework for identifying, prioritising, migrating, and operating business-critical operational logic created outside formal IT systems — for example, in Excel VBA macros, local scripts, and other forms of End-User Computing (EUC).

OLM focuses on **management and lifecycle**, not on tools or platforms.

---

## Why this framework exists

In most organisations, part of operational logic is created by end users and does not reside in corporate IT systems.

It is implemented in:
- Excel files (VBA macros, data preparation operations using add-ins such as Power Query)
- Access databases (often containing a large number of data processing operations, input logic, validations, and report preparation)
- other local scripts and semi-automated procedures

These solutions often emerge for rational reasons: speed, accessibility, and proximity to business knowledge.  
Over time, however, they become:
- business-critical,
- widely used,
- difficult to migrate,
- difficult to maintain (often dependent on the original author),
- and at the same time largely unmanaged.

The problem is not Excel and not VBA.

The problem is the **absence of a management model for operational logic**.

OLM is designed to address exactly this gap.

---

## Core idea

OLM treats operational logic as a **digital asset** of the organisation:

- it creates business value,
- it carries operational risk,
- and therefore must have a lifecycle.

Instead of focusing on files and tools, OLM focuses on:
- visibility,
- prioritisation,
- deliberate management intervention,
- operational accountability,
- and measurable impact.

---

## The OLM lifecycle

OLM is built around a simple, closed management loop:

Register → Prioritise → Migrate → Operate → Measure


This is not a one-off transformation or migration project.  
It is a **continuously operating management system**.

Each stage answers a specific management question:

- **Register** — What operational logic exists?
- **Prioritise** — Where does management intervention matter most?
- **Migrate / Stabilise** — What actions should be taken?
- **Operate** — How do we ensure reliable operation without creating new shadow IT?
- **Measure** — What impact and risk reduction have been achieved?

---

## Key concepts

Some core concepts used in OLM:

- **Operational Logic**  
  Business rules, calculations, and data transformations required to perform operations, regardless of implementation method.

- **Operational Logic Asset**  
  A registered and uniquely identified unit of operational logic managed as part of a portfolio.

- **Canonical Registry**  
  A single source of truth created by transforming heterogeneous inputs into a standardised data model.

- **Decision Classes**  
  The outcomes of prioritisation (e.g. migrate, stabilise, retire), independent of technology choice.

- **Operational Contract**  
  A minimal and explicitly defined set of operational requirements that logic must satisfy to be considered production-ready.

---

## What OLM is — and what it is not

### OLM **is**
- a management framework,
- a lifecycle model for operational logic,
- a way to align business, IT, and risk management perspectives,
- a technology-neutral approach.

### OLM **is not**
- a low-code or automation platform,
- a pipeline orchestration system,
- a replacement for enterprise architecture,
- a prescriptive technology stack.

OLM intentionally remains **one level above implementation**.

---

## Intended use

OLM can be used as:
- a reference framework for internal migrations (for example, moving away from Excel / VBA),
- a management model for EUC and office automation,
- a foundation for process optimisation and operational excellence initiatives,
- a shared language for dialogue between business, IT, and risk functions.

The framework is suitable for enterprise and regulated environments.

---

## Repository structure

The repository is intentionally minimalist and documentation-driven.

It typically includes:
- conceptual materials,
- descriptions of lifecycle and governance principles,
- minimal examples used to validate operational contracts.

Example structure:

```
docs/
glossary.md
overview_5min.pdf
operate/
lifecycle_contract.md
ownership_model.md
sla_model.md
observability_baseline.md
examples/
demo_pipeline/
```

The repository is **not** a production-ready platform.

---

## Status

This repository reflects practical lessons learned from real migration and process improvement initiatives and is published as an **open reference**, not as a finished product.

The structure and content will evolve over time.

---

## License

This project is licensed under the **Apache License 2.0**.

You are free to use, modify, and apply this framework in commercial and internal enterprise scenarios.

---

## Author

Created and maintained by **Mikhail Vorobyev** as a public reference contribution.

Feedback, discussion, and practical usage cases are welcome.

