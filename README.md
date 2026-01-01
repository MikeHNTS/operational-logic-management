# Operational Logic Management (OLM)

**Managing business-critical logic that lives outside IT systems**

Operational Logic Management (OLM) is an open reference framework for identifying, prioritising, migrating, and operating business-critical logic that exists outside formal IT systems — typically in spreadsheets, macros, local scripts, and other forms of End-User Computing (EUC).

OLM focuses on **management and lifecycle**, not on tools or platforms.

> ⚠️ Status: early public reference (v0.x)
> This repository is intentionally minimal and evolving.

---

## Why this framework exists

In most organisations, a significant part of operational logic does not live in enterprise systems.

It lives in:
- Excel spreadsheets and VBA macros  
- Access databases  
- local scripts and semi-automated procedures  

These solutions often emerge for good reasons: speed, accessibility, and proximity to business knowledge.  
Over time, however, they become:
- business-critical,
- widely used,
- difficult to migrate,
- and largely unmanaged.

The problem is not Excel or VBA.

The problem is the **absence of a management model for operational logic**.

OLM addresses this gap.

---

## Core idea

OLM treats operational logic as a **digital asset**:

- it creates business value,
- it carries operational risk,
- and therefore must have a lifecycle.

Instead of focusing on files or tools, OLM focuses on:
- visibility,
- prioritisation,
- deliberate intervention,
- operational accountability,
- and measurable impact.

---

## The OLM lifecycle

OLM is built around a simple, continuous management loop:

Register → Prioritise → Migrate → Operate → Measure


This is not a one-off transformation project.  
It is a **permanent management capability**.

Each stage answers a different management question:

- **Register** — What operational logic exists?
- **Prioritise** — Where does intervention matter most?
- **Migrate / Stabilise** — What action should be taken?
- **Operate** — How do we ensure reliable execution without new shadow IT?
- **Measure** — What value and risk reduction did we achieve?

---

## Key concepts

Some of the central concepts used in OLM:

- **Operational Logic**  
  Business rules, calculations, and transformations required to run operations, regardless of implementation.

- **Operational Logic Asset**  
  A registered, uniquely identified unit of operational logic managed as part of a portfolio.

- **Canonical Registry**  
  A single source of truth created by transforming heterogeneous inputs into a standardised data model.

- **Decision Classes**  
  High-level outcomes of prioritisation (e.g. migrate, stabilise, retire), independent of technology choice.

- **Operational Contract**  
  A minimal, explicit set of operational expectations that logic must satisfy to be considered production-ready.

---

## What OLM is — and what it is not

### OLM **is**
- a management framework,
- a lifecycle for operational logic,
- a way to align business, IT, and risk perspectives,
- technology-agnostic by design.

### OLM **is not**
- a low-code or automation platform,
- a pipeline orchestration tool,
- a replacement for enterprise architecture,
- a prescriptive technology stack.

OLM intentionally stays **one level above implementation**.

---

## Intended use

OLM can be used as:
- a reference framework for internal migrations (e.g. away from Excel / VBA),
- a management model for EUC and office automation,
- a foundation for process optimisation and operational excellence initiatives,
- a discussion framework between business, IT, and risk functions.

It is suitable for regulated and enterprise environments.

---

## Repository structure

This repository is intentionally lightweight and documentation-driven.

It typically contains:
- conceptual documentation,
- lifecycle and governance descriptions,
- minimal runnable examples used to validate operational contracts.

Example structure:

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


The repository does **not** provide a production platform.

---

## Status

This repository reflects lessons learned from real migration and process improvement work and is published as an **open reference**, not as a finished product.

The structure and content will evolve over time.

---

## License

This project is licensed under the **Apache License 2.0**.

You are free to use, modify, and apply this framework in commercial and internal environments.

---

## Author

Created and maintained by Mikhail Vorobyev as a public reference contribution.

Feedback, discussion, and practical experience reports are welcome.
