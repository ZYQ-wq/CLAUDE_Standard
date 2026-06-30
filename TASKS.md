# TASKS

> Track the current execution plan of the project.
>
> This document records the work that is planned, in progress, blocked, or completed.
>
> It connects long-term project knowledge with day-to-day engineering execution.
>
> It is a living document and should be updated frequently.

---

# Purpose

This document answers one question:

> **What should be done next?**

Unlike a roadmap, TASKS focuses only on actionable work.

Each task should be small enough to be completed independently.

---

# Writing Principles

A good task should be:

* Small
* Independent
* Verifiable
* Actionable

Avoid combining multiple unrelated objectives into one task.

---

# Task Template

Each task should follow the same structure.

---

## Task ID

Example:

Task-001

---

## Title

A short description of the work.

---

## Status

One of:

* Todo
* In Progress
* Blocked
* Done

---

## Priority

One of:

* P0
* P1
* P2

---

## Description

Describe exactly what needs to be completed.

Focus on outcomes rather than implementation details.

---

## Dependencies

List tasks or documents that must be completed first.

Examples:

* Task-002
* REQ-005
* Decision-003

---

## Related Knowledge

Reference related project knowledge whenever appropriate.

Examples:

Implements:

* REQ-001

Touches:

* Authentication Module

Related Decisions:

* Decision-004

---

## Definition of Done

Describe the conditions required before the task can be considered complete.

Examples:

* Feature implemented.
* Tests passing.
* Documentation updated.
* Existing behavior preserved.

---

# Task Granularity

A task should represent the smallest independently deliverable unit of work.

If a task cannot be completed without being split, divide it into smaller tasks.

---

# Never Write

Do not use TASKS for:

* Long-term planning
* Brainstorming
* Meeting notes
* Design discussions
* Engineering rationale
* Feature ideas without approval

Those belong in other documents.

---

# Relationship with Other Documents

PRD defines what should be built.

PROJECT_BLUEPRINT defines how the system is organized.

DECISIONS explain why major choices were made.

TASKS define the current execution plan.

Each task should trace back to project knowledge whenever possible.

---

# Long-Term Principle

A completed task should leave no ambiguity about what was delivered.

Every task should be understandable, actionable, and verifiable.

Execution should always remain connected to project knowledge rather than becoming an isolated checklist.
