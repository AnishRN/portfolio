# 14 - Blackbox AI Development Workflow

---

# Purpose

This document defines how Blackbox AI should be used throughout the project.

Blackbox is treated as a software engineer contributing to an existing codebase.

The AI should follow the project documentation instead of inventing its own architecture.

The documentation inside the docs/ folder is the source of truth.

---

# Development Philosophy

Development should be incremental.

Only one milestone should be implemented at a time.

Every milestone must be completed, tested, and reviewed before moving forward.

The AI should extend the existing project instead of rewriting it.

---

# Startup Prompt

Whenever starting a new session, instruct Blackbox to:

- Read the relevant project documentation.
- Understand the existing codebase.
- Summarize its understanding.
- Identify the current milestone.
- Explain the implementation plan before writing code.

Only then should code generation begin.

---

# Required Reading

Before implementing any feature, Blackbox should read only the documentation relevant to that feature.

Examples

Movement

Read

05_Camera_System.md

09_Technical_Architecture.md

12_Coding_Standards.md

---

Projects

Read

06_Object_Interactions.md

07_UI_Design_System.md

11_Data_Model.md

---

Lighting

Read

03_World_Layout.md

08_Animation_and_Ambience.md

09_Technical_Architecture.md

---

Do not load unnecessary documents.

---

# Implementation Rules

Before writing code

Understand requirements.

Review existing implementation.

Identify reusable systems.

Explain planned approach.

Only then generate code.

---

# Modification Rules

Prefer extending existing files.

Avoid replacing working systems.

Avoid deleting existing functionality.

Avoid introducing breaking changes.

---

# Dependency Rules

Before adding a dependency

Verify whether the feature can be implemented using the current stack.

If a new dependency is proposed

Explain

Why it is needed.

Why existing libraries are insufficient.

What trade-offs it introduces.

Do not install new packages without approval.

---

# Code Generation Rules

Generate production-quality code.

Avoid placeholder implementations unless requested.

Write strongly typed TypeScript.

Avoid duplication.

Follow existing naming conventions.

Keep functions focused.

---

# Project Awareness

Before creating a file

Check whether a similar file already exists.

Reuse existing systems whenever possible.

Avoid creating parallel implementations.

---

# Error Resolution

If compilation fails

Identify the root cause.

Fix the smallest possible area.

Avoid rewriting unrelated systems.

Preserve existing functionality.

---

# Refactoring Rules

Refactor only when

The current architecture prevents future development.

The change significantly improves maintainability.

Approval has been given.

Do not refactor simply because a different solution exists.

---

# Milestone Workflow

Every milestone follows

Read documentation

↓

Inspect project

↓

Create implementation plan

↓

Generate code

↓

Compile

↓

Resolve errors

↓

Verify functionality

↓

Summarize completed work

↓

Suggest next milestone

---

# Documentation Updates

Whenever architecture changes

Update the relevant documentation.

Do not allow implementation and documentation to diverge.

---

# Communication Style

Before coding

Summarize understanding.

After coding

Summarize changes.

List modified files.

Explain architectural decisions.

Mention assumptions.

Identify remaining tasks.

---

# Pull Request Style Summary

After each completed milestone

Provide

Overview

Files created

Files modified

Features added

Testing performed

Known limitations

Future recommendations

---

# Forbidden Behaviors

Do not

Rewrite unrelated files.

Rename large portions of the project.

Replace existing architecture.

Introduce random libraries.

Delete functionality.

Ignore project documentation.

Generate duplicate systems.

Implement multiple milestones simultaneously.

---

# Success Criteria

The project should evolve through small, reliable improvements.

Every session should leave the project in a stable, compilable, and documented state.
