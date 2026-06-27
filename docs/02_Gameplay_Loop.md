# 02 - Gameplay Loop

---

# Purpose

This document defines exactly how visitors experience the portfolio from the moment the application starts until they exit.

This is not a website navigation flow.

This is the gameplay flow.

Every future system (camera, interactions, UI, animations, lighting, sound, etc.) should support this gameplay loop.

---

# Core Gameplay Loop

The visitor repeatedly performs the following actions:

Observe

↓

Explore

↓

Discover

↓

Interact

↓

Learn

↓

Return to Exploration

The visitor should never feel like they have left the game world.

---

# Complete Experience Flow

Application Launch

↓

Loading Sequence

↓

Spawn in Studio

↓

Free Exploration

↓

Discover Object

↓

Interact

↓

Object-specific Animation

↓

Portfolio Panel Opens

↓

Read Information

↓

Close Panel

↓

Camera Returns

↓

Continue Exploring

↓

Exit Portfolio

---

# Stage 1 - Loading Sequence

The application begins with a minimal loading experience.

This should feel like entering a world rather than loading a webpage.

Examples:

- Fade from black
- Ambient audio begins
- Lights gradually illuminate
- Environment loads
- Camera smoothly settles into its starting position

Avoid:

- Loading spinners
- Progress bars
- Website splash screens

The loading experience should last only a few seconds.

---

# Stage 2 - Spawn

The visitor starts inside the Studio.

The starting camera position should provide only a partial view of the room.

The entire room should NOT be visible immediately.

This encourages exploration.

The visitor immediately has control.

No lengthy introduction.

---

# Stage 3 - Exploration

The visitor explores freely.

Movement:

- Walk
- Look around

The environment should naturally attract attention through:

- Lighting
- Object placement
- Ambient animation

No arrows.

No objective markers.

No tutorial popups.

---

# Stage 4 - Discovery

Interesting objects should naturally draw attention.

Examples:

- Warm projector light

- Glowing monitor

- Illuminated globe

- Desk lamp

- Notice board

The visitor becomes curious.

Curiosity drives exploration.

---

# Stage 5 - Interaction

When the visitor approaches an interactive object:

A subtle interaction prompt appears.

Example:

Press E to Interact

No large buttons.

No flashing UI.

Interaction should feel natural.

---

# Stage 6 - Camera Focus

After interaction begins:

The camera should smoothly move toward the object.

Examples:

Projector

↓

Camera moves toward projector screen

Bookshelf

↓

Camera slides toward bookshelf

Notice Board

↓

Camera steps closer

Phone

↓

Camera tilts downward

World Map

↓

Camera rotates toward wall

The camera should never teleport.

Movement should feel cinematic.

---

# Stage 7 - Portfolio View

After camera movement completes:

The portfolio information becomes visible.

Examples:

Projects

↓

Project list appears on projector

Languages

↓

Countries illuminate

Personal Info

↓

Notice board becomes readable

Socials

↓

Phone screen activates

The environment should remain visible whenever possible.

Avoid replacing the world with a full-screen webpage.

---

# Stage 8 - Exit Interaction

After reading:

Press ESC

or

Click Close

The panel disappears.

Camera smoothly returns.

The visitor regains movement.

---

# Repeat

The visitor repeats this process until every section has been explored.

The experience should never force a particular order.

---

# Exit

The visitor may leave at any time.

Exit should feel intentional.

Examples:

Walk to Exit Door

↓

Press Exit

↓

Fade to Black

↓

Thank You Message

Avoid browser-style navigation.

---

# Gameplay Rules

The visitor should always have control.

Movement should never feel restrictive.

Interactions should never interrupt immersion.

Information should never feel hidden.

Objects should always be discoverable.

---

# Design Rules

Every interaction should answer these questions:

What attracted the visitor?

↓

How does the visitor interact?

↓

What animation plays?

↓

How is information presented?

↓

How does the visitor return?

Every future object should follow this same structure.

---

# Success Criteria

A visitor should be able to:

Explore naturally

↓

Understand interactions without tutorials

↓

Access every portfolio section

↓

Enjoy the experience

↓

Leave remembering the journey, not just the information.
