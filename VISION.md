# Writing Guide — VISION.md

## Purpose

VISION.md defines the long-term identity of a project.

Unlike a PRD or technical design document, it does **not** explain what the system does or how it is built.

Instead, it answers a deeper question:

> **Why should this project exist?**

A good vision remains meaningful long after technologies, frameworks, and implementation details have changed.

---

# What VISION Is

A Vision is:

* A long-term statement of purpose.
* A description of the future the project hopes to create.
* A collection of enduring beliefs.
* A guide for future decision making.

If two implementation options are equally valid, the Vision should help determine which one better aligns with the project's long-term direction.

---

# What VISION Is Not

VISION.md is **not**:

* A feature list.
* A roadmap.
* A technical specification.
* A system architecture.
* A marketing page.
* A project introduction.

Those belong in other documents.

---

# Writing Principles

A good Vision should be:

### Stable

It should remain meaningful for many years.

Avoid references to specific technologies or temporary trends.

---

### Inspirational

Describe the future you hope to create, not today's implementation.

---

### Concise

Every sentence should introduce a new idea.

Avoid repetition.

Prefer clarity over length.

---

### Technology Independent

Do not mention:

* Programming languages
* Frameworks
* Databases
* APIs
* Infrastructure

Those decisions belong elsewhere.

---

# The Five Sections

## 1. Why We Exist

Explain why the project deserves to exist.

Focus on the problem rather than the solution.

---

## 2. The Future We Believe In

Describe the future your project hopes to create.

Think in terms of years, not releases.

---

## 3. Our Core Beliefs

Document the principles that should survive every refactor, rewrite, and redesign.

If these beliefs change, the project itself has fundamentally changed.

---

## 4. What We Will Never Become

Boundaries are part of identity.

Explicitly stating what the project refuses to become helps prevent long-term scope drift.

---

## 5. Our North Star

End with one concise statement describing the direction that guides every major decision.

A good North Star answers:

> "If we are unsure what to do next, what should guide us?"

---

# Ten-Year Test

Before finalizing your Vision, ask:

* Will this still be true in ten years?
* Does this remain meaningful if today's technology disappears?
* Does it describe beliefs instead of implementation?
* Would future contributors understand the purpose of the project?

If the answer is "yes", the Vision is likely stable enough.

---

# Recommended Length

500–1200 words.

Long enough to communicate beliefs.

Short enough to be read in under five minutes.

---

# Relationship to Other Documents

VISION answers:

> Why should this project exist?

PRD answers:

> What should the project do?

PROJECT_BLUEPRINT answers:

> How should the system be organized?

AGENTS answers:

> How should humans and AI collaborate while building it?

Each document has one responsibility.

Avoid duplicating knowledge across documents.
