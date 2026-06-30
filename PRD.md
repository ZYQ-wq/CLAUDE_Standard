# PRD

> Define what the project or feature should achieve.
>
> This document describes the problem to solve, the desired outcomes, and the functional requirements.
>
> It intentionally avoids implementation details and architectural decisions.

---

# Purpose

This document answers one question:

> **What should be built?**

A good PRD defines the problem clearly enough that multiple valid implementations are possible.

It should guide design, not replace it.

---

# Problem Statement

Describe the problem that needs to be solved.

Focus on the user's needs or the business problem.

Avoid proposing solutions.

Good questions to answer:

* What problem exists today?
* Who is affected?
* Why is solving this problem valuable?

---

# Objectives

Define measurable outcomes.

Examples:

* Reduce average response time below 200ms.
* Allow users to complete registration without manual approval.
* Support 10,000 concurrent workflow executions.

Objectives should be specific and verifiable.

---

# Scope

Clearly define project boundaries.

## In Scope

List everything included.

## Out of Scope

Explicitly list what will **not** be implemented.

Defining exclusions prevents scope creep.

---

# Functional Requirements

Describe each requirement independently.

Use stable identifiers.

Example:

### REQ-001

The system shall allow users to authenticate using email and password.

### REQ-002

The system shall issue a JWT after successful authentication.

Requirements should describe expected behavior rather than implementation.

---

# Acceptance Criteria

Define how success will be verified.

Acceptance criteria should be objective and testable.

Examples:

* Valid credentials return HTTP 200.
* Invalid credentials return HTTP 401.
* Session expires after the configured timeout.
* Password reset email is delivered successfully.

---

# Constraints

Document limitations that must be respected.

Examples:

* Existing public APIs must remain compatible.
* No database schema changes.
* Plugin API v2 must continue to work.
* No additional infrastructure may be introduced.

Constraints define the solution space without prescribing the solution.

---

# Dependencies

List dependencies that affect this work.

Examples:

* PROJECT_BLUEPRINT
* Decision-005
* Existing authentication module
* External authentication provider

Only include dependencies that materially influence implementation.

---

# Open Questions

Record unresolved questions.

Do not guess.

Unknowns should be made explicit.

Each question should eventually become either:

* a requirement,
* a decision,
* or be removed.

---

# Relationship with Other Documents

VISION explains why the project exists.

PROJECT_BLUEPRINT explains how the system should be organized.

PRD explains what should be built.

TASKS explain how work will be executed.

Keep these responsibilities separate.

---

# Long-Term Principle

Describe the problem completely.

Leave implementation choices to design.

A successful PRD creates alignment without restricting good engineering judgment.
