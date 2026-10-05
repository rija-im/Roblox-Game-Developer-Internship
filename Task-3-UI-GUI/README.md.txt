# Roblox Game Developer Internship — Task 3

## UI & GUI Fundamentals

This project is part of my **Roblox Game Developer Internship**.

Task 3 focuses on creating a basic user interface in Roblox Studio using **ScreenGui**, displaying a welcome message, creating an interactive button, and triggering a particle effect when the button is clicked.

## Task Objectives

* Create a `ScreenGui`.
* Display a welcome message using a `TextLabel`.
* Create an interactive on-screen button using a `TextButton`.
* Create a `ParticleEmitter`.
* Use a `LocalScript` to detect the button click.
* Trigger a particle effect when the button is clicked.
* Understand the difference between a `Script` and a `LocalScript`.

## Features

### 1. Welcome Message

A `TextLabel` displays a welcome message on the player's screen:

```text
Welcome to my Game!
```

### 2. Interactive Button

A `TextButton` is displayed on the screen:

```text
CLICK ME ✨
```

The button responds when the player clicks it.

### 3. Particle Effect

A `ParticleEmitter` is attached to a Part in the Workspace.

When the player clicks the button, the script triggers the particle effect:

```lua
particleEmitter:Emit(30)
```

## Concepts Learned

* ScreenGui
* TextLabel
* TextButton
* GUI positioning and sizing
* LocalScript
* Button click events
* `MouseButton1Click`
* `:Connect()`
* ParticleEmitter
* `:Emit()`
* Script vs LocalScript
* Basic event-driven programming

## Task Status

**Task 3 — Completed ✅**

This task helped me understand the fundamentals of Roblox GUI development, player interaction, and event-driven scripting.


