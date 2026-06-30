# PROJECT_BLUEPRINT

> Define the long-term design of the project.
>
> This document describes how the system should be organized rather than how it is currently implemented.
>
> It exists to ensure architectural consistency as the project evolves.
>
> It should remain relatively stable throughout the lifetime of the project.

---

# Purpose

This document answers one question:

> **How should this project be organized?**

Unlike a PRD, it does not describe features.

Unlike implementation, it does not describe code.

Instead, it defines the long-term design principles that guide future development.

---

# Design Philosophy

Describe the fundamental design philosophy of the project.

These principles should guide every architectural decision.

Examples:

* Simplicity over complexity.
* Explicit boundaries over hidden coupling.
* Reuse before reinvention.
* Evolution over rewriting.
* Consistency over novelty.

---

# System Overview

Describe the major responsibilities within the system.

Focus on responsibilities rather than technologies.

Example:

* Authentication
* User Management
* Workflow Engine
* Plugin Runtime
* Storage
* API Layer

Each responsibility should have one clear purpose.

---

# Core Principles

Define the architectural rules that should always remain true.

Examples:

* Every module owns one primary responsibility.
* Modules communicate only through defined interfaces.
* Business logic must remain independent of infrastructure.
* Dependencies should point inward.
* Cross-module knowledge should be minimized.

---

# Module Contracts

For each major module, describe:

## Purpose

What responsibility does this module own?

## Owns

What knowledge or behavior belongs exclusively to this module?

## Does Not Own

What responsibilities explicitly belong elsewhere?

## Public Interface

How should other modules interact with this module?

Avoid implementation details.

Focus on responsibilities and boundaries.

---

# Dependency Rules

Describe allowed dependencies.

Examples:

Allowed:

* UI → Application
* Application → Domain
* Infrastructure → External Services

Avoid:

* Circular dependencies
* Cross-layer access
* Direct database access from presentation code
* Business logic inside infrastructure

Dependency direction should remain predictable.

---

# Directory Philosophy

Explain why the repository is organized the way it is.

Do not simply list folders.

Instead, explain the responsibility of each top-level directory.

The structure should communicate architecture.

---

# Data Ownership

Clearly define ownership of important data.

Each piece of data should have one authoritative owner.

Avoid duplicated ownership.

Examples:

* User identity belongs to Authentication.
* User profile belongs to User Management.
* Workflow state belongs to Workflow Engine.

Ownership should remain explicit.

---

# Extension Points

Describe where future functionality should be added.

Examples:

* Plugin system
* Event system
* Workflow nodes
* API endpoints
* Background jobs

New functionality should extend existing mechanisms before introducing new ones.

---

# Evolution Rules

Describe how the architecture is allowed to evolve.

Examples:

New modules should only be introduced when:

* Existing responsibilities become too large.
* Boundaries become unclear.
* Separation significantly improves maintainability.

Avoid architectural redesign without strong justification.

Prefer incremental evolution.

---

# Anti-Patterns

List architectural patterns that should never appear.

Examples:

* God Objects
* Circular Dependencies
* Shared Mutable State
* Hidden Side Effects
* Duplicate Business Logic
* Tight Coupling
* Leaking Internal Implementation

Explicitly defining anti-patterns is as important as defining good practices.

---

# Relationship with Other Documents

VISION defines:

> Why this project exists.

PRD defines:

> What the system should do.

PROJECT_BLUEPRINT defines:

> How the system should be organized.

AGENTS defines:

> How humans and AI should collaborate while building it.

Each document owns one responsibility.

Avoid duplicating knowledge across documents.

---

# Long-Term Principle

A good architecture should be understandable before it becomes impressive.

When multiple designs are possible, prefer the one that future contributors can understand with the least effort.
