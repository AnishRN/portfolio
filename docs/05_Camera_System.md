# 05 - Camera System

---

# Purpose

The camera represents the visitor's eyes.

The visitor should never think about the camera.

The camera should feel completely natural.

Every movement should feel smooth, responsive and cinematic.

The camera should never behave like webpage scrolling or PowerPoint transitions.

The camera is responsible for immersion.

---

# Camera Style

Camera Type

First Person

Perspective

Perspective Camera

Control

Mouse Look

Movement

WASD

The visitor experiences the world entirely through the camera.

There is no visible player character.

---

# Camera Philosophy

The camera should feel alive.

It should have subtle weight and momentum.

It should never snap instantly unless absolutely necessary.

Every movement should ease naturally.

The player should feel physically present inside the room.

---

# Default Camera State

At launch

Player is standing naturally.

Looking slightly toward the center of the room.

The horizon should feel level.

Camera height should represent an average standing adult.

---

# Mouse Look

Mouse movement controls camera rotation.

Horizontal movement

Yaw

Vertical movement

Pitch

Pitch should have limits.

The player should never rotate upside down.

---

# Movement

Movement keys

W

Forward

S

Backward

A

Left

D

Right

Movement should be smooth.

Acceleration should feel natural.

Stopping should not be instantaneous.

---

# Camera Smoothing

The camera should have slight inertia.

Small smoothing should be applied.

Avoid robotic movement.

The player should feel that the camera has weight.

---

# Head Bob

While walking

The camera performs a subtle head bob.

Requirements

Very small movement

Comfortable

Not distracting

Head bob immediately stops when the player stops moving.

---

# Idle Breathing

When standing still

Very subtle breathing movement.

Almost unnoticeable.

The room should never feel frozen.

---

# Field of View

Normal FOV

Approximately 75°–85°

Interaction FOV

Slightly narrower

The change should happen smoothly.

Never instantly.

---

# Camera During Interaction

Once interaction begins

Player movement disabled.

Mouse look disabled.

Camera animation begins.

Camera moves toward object.

Camera rotates naturally.

Camera settles.

Portfolio interface appears.

The player should feel like they walked closer to inspect the object.

---

# Camera Return

When interaction ends

Portfolio panel disappears.

Camera slowly returns.

Movement restored.

Mouse look restored.

The transition should feel seamless.

---

# Camera Animation Principles

Never teleport.

Never instantly rotate.

Never instantly zoom.

Always ease movement.

Always preserve orientation.

Movement should feel cinematic.

---

# Object Focus

Every interactive object has a predefined camera target.

Examples

Projector

Camera moves in front of the screen.

Bookshelf

Camera moves toward shelf.

Phone

Camera tilts downward.

Notice Board

Camera moves closer.

World Map

Camera rotates toward wall.

Each object controls its own camera destination.

---

# Camera Collision

The camera should never pass through

Walls

Furniture

Objects

Collision should feel natural.

---

# Camera Height

Standing height only.

No crouching.

No jumping.

No sprinting.

The experience should remain calm.

---

# Motion Comfort

Avoid excessive movement.

Avoid violent shaking.

Avoid aggressive zooming.

Avoid rapid rotation.

Visitors unfamiliar with games should remain comfortable.

---

# Mouse Sensitivity

Provide adjustable sensitivity.

Default should feel comfortable.

---

# Cursor Behaviour

While exploring

Mouse cursor hidden.

During interaction

Mouse cursor visible.

After interaction

Mouse cursor hidden again.

---

# Interaction Transition

Example

Walk toward projector

↓

Press E

↓

Camera slowly moves

↓

Projector powers on

↓

Camera stops

↓

Portfolio panel appears

↓

Close panel

↓

Projector powers off

↓

Camera returns

↓

Movement resumes

Every interaction follows this philosophy.

---

# Audio Synchronization

Camera movement should synchronize with

Footsteps

Object sounds

Ambient audio

Interaction sounds

Everything should feel connected.

---

# Performance

Camera movement must remain smooth.

Target

Stable FPS

No stuttering

No sudden jumps

No camera jitter

---

# Future Compatibility

Future rooms and objects should reuse this exact camera behaviour.

The visitor should never need to learn a different camera system.

Consistency creates immersion.

---

# Success Criteria

The camera should disappear from the visitor's attention.

Visitors should feel like they are naturally looking around a real space rather than controlling software.

The camera should make the portfolio feel like an interactive game world rather than a website.
