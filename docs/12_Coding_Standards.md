# 12 - Coding Standards

---

# Purpose

This document defines the coding standards for the project.

Every file, component, function, and system should follow these conventions.

Consistency is more important than personal preference.

The project should remain maintainable, readable, and scalable.

---

# General Principles

Code should be

- Simple
- Modular
- Readable
- Reusable
- Predictable
- Type-safe

Avoid unnecessary complexity.

---

# Language

Use

TypeScript

Do not use JavaScript unless absolutely necessary.

Enable strict type checking.

---

# Framework

React

Vite

React Three Fiber

Three.js

Tailwind CSS

Do not introduce additional frameworks unless approved.

---

# Component Design

Each component should have a single responsibility.

Large components should be broken into smaller reusable components.

Avoid monolithic files.

---

# Component Naming

Use PascalCase.

Examples

Projector.tsx

Bookshelf.tsx

Phone.tsx

InteractionPrompt.tsx

CameraController.tsx

Avoid abbreviations.

---

# File Naming

Components

PascalCase

Hooks

camelCase beginning with "use"

Examples

useCamera.ts

useInteraction.ts

useAudio.ts

Utilities

camelCase

Examples

calculateDistance.ts

formatDate.ts

lerpVector.ts

---

# Folder Naming

Use lowercase.

Examples

components

systems

hooks

managers

layouts

utils

---

# Function Naming

Functions should describe actions.

Examples

openProject()

closePhone()

playAnimation()

startInteraction()

stopInteraction()

Avoid vague names.

Examples

handle()

process()

run()

test()

---

# Variable Naming

Variables should clearly describe purpose.

Examples

cameraTarget

playerPosition

interactionRadius

selectedProject

Avoid

data

temp

value

object

---

# Constants

Use UPPER_CASE.

Examples

PLAYER_SPEED

INTERACTION_DISTANCE

DEFAULT_FOV

MAX_PITCH

---

# TypeScript Interfaces

Use PascalCase.

Examples

Project

Skill

Language

PlayerState

CameraState

InteractionState

---

# Enums

Use PascalCase.

Examples

SceneType

InteractionType

ObjectState

CameraMode

---

# Comments

Use comments only when necessary.

Explain

Why

Not

What

Good

// Prevent camera clipping through walls.

Avoid

// Increment i

---

# React Rules

Prefer functional components.

Do not use class components.

Use hooks.

Keep components pure whenever possible.

---

# State Management

Keep state local whenever possible.

Lift state only when required.

Avoid unnecessary global state.

Use managers for cross-system coordination.

---

# Props

Props should be typed.

Avoid excessive prop drilling.

Pass only what is required.

---

# Styling

Use Tailwind CSS.

Avoid inline styles unless dynamic.

Keep styling separate from logic.

---

# Three.js

Keep rendering code separate from UI code.

Avoid mixing HTML interface logic with 3D scene logic.

---

# Animation

Animation logic belongs inside animation systems.

Do not hardcode animations inside unrelated components.

---

# Audio

Audio should be managed through the AudioManager.

Avoid playing sounds directly inside UI components.

---

# Interaction

Every interactive object should use the common Interaction System.

Avoid creating custom interaction logic unless necessary.

---

# Camera

All camera movement should pass through the CameraManager.

Do not manually manipulate the camera inside object components.

---

# Data

Never hardcode portfolio information.

Always read from the data layer.

---

# Error Handling

Handle errors gracefully.

Display placeholders when data is missing.

Never allow the application to crash because of missing content.

---

# Performance

Avoid unnecessary re-renders.

Memoize expensive calculations when appropriate.

Reuse components.

Reuse materials.

Reuse geometries.

---

# Accessibility

Provide keyboard navigation where appropriate.

Ensure sufficient text contrast.

Allow adjustable mouse sensitivity.

---

# Imports

Prefer absolute imports.

Group imports by

External

↓

Internal

↓

Styles

↓

Assets

Maintain consistent ordering.

---

# Git

Commit messages should be descriptive.

Examples

Add projector interaction

Implement camera manager

Create recreation room

Avoid

Update

Fix

Changes

Stuff

---

# AI Coding Assistant Guidelines

When generating code

- Follow existing architecture.
- Reuse existing systems.
- Do not duplicate functionality.
- Prefer composition over duplication.
- Respect folder structure.
- Do not introduce new libraries without approval.
- Preserve placeholder data.
- Write clean, documented TypeScript.

---

# Success Criteria

A developer should be able to read any file in the project and immediately understand its purpose.

Every new feature should feel like a natural extension of the existing architecture.
