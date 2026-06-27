# 10 - Folder Structure

---

# Purpose

This document defines the folder organization of the project.

The goal is to maintain a clean, modular, and scalable codebase.

Every feature should have a clear location.

Future developers (or AI coding assistants) should immediately understand where new code belongs.

---

# Root Directory

portfolio-game/

├── docs/
├── public/
├── src/
├── package.json
├── vite.config.ts
├── tsconfig.json
├── eslint.config.js
├── README.md

---

# Docs

Contains every design and technical document.

This folder should never contain source code.

---

# Public

Contains static assets.

Examples

favicon

placeholder images

icons

audio files

resume pdf

---

# Source

Contains every line of application code.

Nothing outside src should contain application logic.

---

# Source Structure

src/

├── app/
├── assets/
├── components/
├── config/
├── constants/
├── data/
├── hooks/
├── layouts/
├── managers/
├── scenes/
├── systems/
├── ui/
├── utils/
├── types/
├── styles/
├── App.tsx
└── main.tsx

---

# app/

Responsible for bootstrapping the application.

Contains

Application initialization

Provider setup

Global configuration

---

# assets/

Contains reusable assets.

Examples

Placeholder textures

Fonts

Icons

Simple procedural materials

Future models (if ever added)

---

# components/

Reusable components shared across multiple systems.

Examples

InteractiveObject

Door

Desk

Bookshelf

Phone

Projector

Chair

Window

Lamp

Plant

---

# config/

Contains configurable values.

Examples

Camera settings

Movement speed

Lighting intensity

Audio volume

Animation durations

Interaction distance

Nothing should be hardcoded elsewhere if it belongs here.

---

# constants/

Contains application-wide constants.

Examples

Key bindings

Color palette

Scene names

Object identifiers

Animation identifiers

---

# data/

Contains placeholder portfolio data.

Examples

personal.json

projects.json

education.json

skills.json

languages.json

internships.json

certifications.json

socials.json

hobbies.json

Eventually this folder can be replaced by an API.

---

# hooks/

Reusable React hooks.

Examples

usePlayer

useInteraction

useCamera

useAudio

useKeyboard

usePointerLock

---

# layouts/

Responsible for arranging world objects.

Examples

StudioLayout

RecreationRoomLayout

FutureRoomLayout

---

# managers/

Contains high-level managers.

Examples

InteractionManager

CameraManager

AudioManager

UIManager

SceneManager

DataManager

Managers coordinate systems but avoid rendering.

---

# scenes/

Each physical room exists here.

Examples

Studio

RecreationRoom

Future AI Lab

Future Balcony

Each scene owns its own lighting and object placement.

---

# systems/

Contains reusable game systems.

Examples

Movement System

Collision System

Interaction System

Animation System

Lighting System

Audio System

Particle System

These are reusable across scenes.

---

# ui/

Contains interface components.

Examples

Panels

Buttons

Windows

Project Details

Education View

Phone Screen

Book Interface

Certificate Viewer

UI components should remain independent of world logic.

---

# utils/

Helper functions.

Examples

Math helpers

Animation helpers

Formatting

General utilities

No application state should exist here.

---

# styles/

Global styling.

Examples

Fonts

Theme variables

Tailwind customizations

General CSS

---

# types/

TypeScript types.

Examples

Project

Education

Skill

Language

Internship

Certificate

Social

PlayerState

CameraState

InteractionState

Every shared type belongs here.

---

# Naming Convention

Folders

lowercase

Files

PascalCase for components

camelCase for utilities

JSON

lowercase

Interfaces

PascalCase

Enums

PascalCase

Constants

UPPER_CASE

---

# Import Philosophy

Prefer

Absolute imports

Avoid

Long relative paths

---

# Component Philosophy

Each component should have one responsibility.

Avoid components larger than necessary.

Reusable logic belongs in hooks or systems.

---

# Future Expansion

The folder structure should support

More rooms

More interactions

Networking

AI assistant

Localization

Without major restructuring.

---

# Success Criteria

A new contributor should understand where every file belongs within a few minutes of opening the project.
