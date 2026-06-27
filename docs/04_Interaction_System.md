# 04 - Interaction System

---

# Purpose

This document defines how visitors interact with the world.

Every interactive object inside the portfolio must follow the same interaction philosophy.

Interactions should feel natural, immersive and cinematic.

The player should never feel like they are clicking website buttons.

Instead, they should feel like they are using real objects.

---

# Interaction Philosophy

Objects are real.

Objects exist in the environment.

The player physically approaches them.

Interaction happens because the player is near them.

The environment is the interface.

---

# General Interaction Flow

Every interactive object follows exactly the same sequence.

Player notices object

↓

Player walks toward object

↓

Player enters interaction range

↓

Interaction prompt appears

↓

Player presses E

↓

Camera moves smoothly toward object

↓

Object animation begins

↓

Portfolio information appears

↓

Player finishes reading

↓

Player exits interaction

↓

Camera smoothly returns

↓

Player regains control

---

# Interaction Distance

Each object has an interaction radius.

The prompt should only appear when the player is close enough.

The prompt disappears immediately after leaving the interaction radius.

---

# Interaction Prompt

The prompt should be minimal.

Examples

Press E to Use Projector

Press E to Read Notice Board

Press E to Inspect Globe

Press E to Open Phone

Press E to View Certificates

Press E to Explore Recreation Room

Avoid large UI boxes.

Avoid flashing text.

Avoid unnecessary tutorials.

---

# Camera Control During Interaction

Once interaction begins:

Player movement is temporarily disabled.

Mouse look is disabled.

Camera animation begins.

After the interaction ends:

Camera returns.

Movement is restored.

---

# Portfolio Panels

Portfolio information should never appear instantly.

The object should become the focus first.

Only then should the UI appear.

The world should remain visible whenever possible.

Avoid replacing the entire screen.

---

# Object Animation

Every interactive object should have its own unique animation.

Animations should reinforce the identity of the object.

No two objects should feel identical.

---

# Interaction Cancellation

The player may cancel at any time.

Press ESC

↓

Panel closes

↓

Object animation reverses

↓

Camera returns

↓

Movement restored

---

# Rules

Only one object can be interacted with at a time.

No overlapping interactions.

No stacked UI.

No nested interactions.

---

# Interactive Objects

Version 1 contains the following objects.

Projector

Education Board

Notice Board

Bookshelf

Globe

World Map

Certificate Cabinet

Phone

Door to Recreation Room

Chess Table

Guitar

Gaming Console

Reading Shelf

Writing Desk

Coding Laptop

---

# Object Behaviour

Every object follows this template.

Object

↓

Idle Animation

↓

Player Approaches

↓

Prompt Appears

↓

Player Presses E

↓

Camera Moves

↓

Object Animates

↓

Portfolio UI Appears

↓

Player Closes

↓

Object Returns To Idle

---

# Object States

Every object has five states.

Idle

Highlighted

Interacting

Displaying

Returning

Transitions between states should always be smooth.

---

# Hover Behaviour

Objects should subtly respond when the player looks directly at them.

Examples

Slight glow

Small light increase

Gentle pulse

Very small movement

Avoid exaggerated animations.

---

# Audio Feedback

Every interaction should have sound.

Examples

Projector

Projector startup sound

Phone

Screen unlock sound

Bookshelf

Book sliding sound

Notice Board

Paper rustling

Globe

Soft rotation sound

Door

Door opening

Sound should reinforce immersion.

---

# Visual Feedback

Interactive objects should communicate that they can be used.

Examples

Warm lighting

Gentle glow

Subtle movement

Animated indicator

Avoid giant arrows.

Avoid floating UI icons.

Avoid obvious game markers.

---

# User Experience Goals

Interactions should feel

Natural

Intentional

Rewarding

Responsive

Comfortable

Visitors should instinctively understand how to interact without reading instructions.

---

# Future Compatibility

Every new interactive object added in future versions must follow this exact interaction system.

Consistency is more important than uniqueness.
