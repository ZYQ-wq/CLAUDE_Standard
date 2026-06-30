# DECISIONS

> Record important engineering decisions that shape the long-term evolution of the project.
>
> This document explains **why** significant decisions were made, what alternatives were considered, and what consequences those decisions introduce.
>
> It is not a changelog.
>
> It is not meeting notes.
>
> It is not implementation documentation.

---

# Purpose

This document answers one question:

> **Why is the project the way it is today?**

Whenever a major technical, architectural, or engineering decision is made, it should be recorded here.

Future contributors should understand not only **what** was decided, but **why**.

---

# When to Record a Decision

Record decisions that significantly influence the future evolution of the project.

Examples:

* Architectural changes
* Technology selection
* Database migration
* Public API changes
* Plugin interface changes
* Major workflow redesign
* Security strategy changes
* Important engineering trade-offs

Do **not** record:

* Bug fixes
* Minor refactoring
* Formatting changes
* Small optimizations
* Temporary experiments

---

# Decision Template

Each decision should follow the same structure.

---

## Decision ID

Example:

Decision-001

---

## Title

A concise summary of the decision.

---

## Status

One of:

* Proposed
* Accepted
* Active
* Deprecated
* Superseded

---

## Date

When the decision was accepted.

---

## Context

Describe the situation that required a decision.

What problem needed to be solved?

---

## Alternatives Considered

List the realistic alternatives that were evaluated.

Explain why they were not chosen.

---

## Decision

Describe the chosen approach.

Focus on the decision itself rather than implementation details.

---

## Rationale

Explain why this option was selected.

Discuss trade-offs whenever possible.

---

## Consequences

Describe the long-term effects.

Include both advantages and disadvantages.

---

## Related Documents

Reference relevant documents when appropriate.

Examples:

* VISION
* PROJECT_BLUEPRINT
* PROJECT_CONTEXT
* PRD

---

# Writing Principles

Every decision should be:

* Clear
* Concise
* Objective
* Evidence-based

Avoid emotional language.

Avoid implementation details.

Avoid describing temporary situations.

---

# Never Write

Do not use this document for:

* TODO lists
* Meeting notes
* Daily development logs
* Feature requests
* Bug tracking
* Personal opinions without evidence

This document exists to preserve engineering knowledge.

---

# Relationship with Other Documents

PROJECT_BLUEPRINT describes the intended long-term design.

PROJECT_CONTEXT describes the current state.

DECISIONS explains why the current state evolved the way it did.

Together, these documents provide both the present state and the reasoning behind it.

---

# Long-Term Principle

A good engineering decision should remain understandable years after the original implementation has changed.

Future contributors should be able to answer:

> "Would we make the same decision again today?"

If the answer is "yes", the decision has likely been documented well.
