# 15 - Testing Checklist

---

# Purpose

This document defines the quality assurance process for the project.

Every milestone must pass these tests before development continues.

The goal is to ensure the project remains stable, performant, and immersive throughout development.

No milestone should be considered complete until all applicable tests pass.

---

# Testing Philosophy

Every new feature should satisfy three conditions:

1. It works as intended.
2. It does not break existing functionality.
3. It maintains the overall experience and performance.

---

# Testing Stages

Every milestone follows this sequence.

Development

↓

Compilation

↓

Functional Testing

↓

Visual Testing

↓

Performance Testing

↓

Regression Testing

↓

Approval

---

# Build Verification

Verify that

- Project compiles successfully.
- Development server starts without errors.
- Production build completes successfully.
- No TypeScript errors exist.
- No ESLint errors exist.
- No dependency conflicts exist.

---

# Console Verification

The browser console should contain

- No runtime errors.
- No unhandled promise rejections.
- No failed asset loading.
- No unnecessary warnings.

Warnings should be investigated before continuing.

---

# Camera Tests

Verify

- Mouse look functions correctly.
- Camera rotation limits work.
- Camera never clips through walls.
- Camera transitions are smooth.
- Camera returns correctly after interactions.
- Head bob behaves correctly.
- Idle breathing animation functions.

---

# Player Tests

Verify

- WASD movement.
- Collision detection.
- Interaction distance.
- Pointer lock.
- Mouse sensitivity.
- Player cannot walk through furniture.
- Player cannot leave the playable area.

---

# Interaction Tests

For every interactive object verify

- Prompt appears.
- Prompt disappears.
- Interaction starts.
- Camera moves correctly.
- Animation plays.
- UI appears.
- UI closes.
- Camera returns.
- Player movement resumes.

---

# Portfolio Content Tests

Verify every section

Personal Information

Education

Projects

Internships

Certifications

Skills

Languages

Hobbies

Socials

Each should display correctly.

---

# Data Tests

Verify

- JSON loads successfully.
- Missing values show placeholders.
- Invalid data does not crash the application.
- Images load correctly.
- Links work correctly.

---

# UI Tests

Verify

- Text is readable.
- Buttons respond.
- Hover effects work.
- Windows open.
- Windows close.
- Cursor appears during interaction.
- Cursor disappears afterwards.

---

# Animation Tests

Verify

Idle animations

↓

Interaction animations

↓

Return animations

↓

Lighting transitions

↓

Particles

Animations should never stutter.

---

# Audio Tests

Verify

Ambient sound

Footsteps

Object sounds

Background music

Volume settings

Audio synchronization

No overlapping audio issues.

---

# Lighting Tests

Verify

Ambient lighting

Object lighting

Shadows

Window lighting

Dynamic lighting

No flickering.

---

# Room Tests

Studio

Verify

All objects present

Lighting correct

Navigation smooth

No collision issues

---

Recreation Room

Verify

Door functions

Objects present

Interactions function

Lighting differs from studio

---

# Performance Tests

Target

60 FPS or higher on a modern desktop browser.

Verify

No frame drops

No memory leaks

No unnecessary rerenders

Smooth camera

Smooth animations

Stable interaction

---

# Browser Compatibility

Verify functionality in

- Chrome
- Microsoft Edge
- Firefox

Future versions may include Safari support.

---

# Accessibility

Verify

Adjustable mouse sensitivity

Readable fonts

Good contrast

Keyboard usability

Interaction prompts visible

---

# Regression Checklist

Before completing a milestone verify

Previous milestones still work.

Nothing previously completed should become broken.

Regression testing is mandatory.

---

# Milestone Acceptance

A milestone is complete only if

✓ Project builds successfully.

✓ No TypeScript errors.

✓ No runtime errors.

✓ All new functionality works.

✓ Existing functionality still works.

✓ Documentation remains accurate.

✓ Performance remains acceptable.

---

# Bug Reporting

Every bug should contain

Title

Description

Steps to reproduce

Expected result

Actual result

Priority

Status

Assigned milestone

---

# Release Candidate Checklist

Before deployment verify

All milestones complete

All tests pass

No placeholder debug code

No unused files

No unused imports

No console errors

Production build successful

---

# Success Criteria

The portfolio should feel polished, reliable, and stable.

Visitors should never encounter broken interactions, visual glitches, or performance issues.
