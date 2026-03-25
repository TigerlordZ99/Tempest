# Tempest (Prototype)

**PROTOTYPE** This project is a technical demonstration of 2D character controllers and procedurally generated weather-based hazards in Unity. It is not a finished product.

## Overview
Tempest is a 2D survival platformer where the player must navigate an environment while dodging dynamic weather patterns. Players must reach a specific objective to win while managing a limited health pool.

## Core Prototype Features
* **Agile Movement**: Includes horizontal traversal and a double-jump mechanic.
* **Invincibility Dash**: A directional dash that provides a brief window of invincibility to pass through hazards unharmed.
* **Lightning System**: A manager that tracks "Floor" tiles and triggers lightning strikes preceded by a visual warning indicator.
* **Procedural Tornadoes**: A spawner that uses raycasting to detect ground levels and place moving tornadoes at various vertical heights.
* **Survival Mechanics**: A health system that triggers a loss state at zero, and a win condition triggered by reaching the level objective.

## Controls
* **Move**: Horizontal movement keys.
* **Jump**: Press for a standard jump; press again in mid-air for a double-jump.
* **Dash**: Use shift to activate for a burst of speed and temporary invincibility.
* **Reset**: Instantly reload the scene to restart the prototype.

## Technical Stack
* **Engine**: Unity.
* **Input**: Modern Unity Input System.
* **Rendering**: Universal Render Pipeline (URP).
