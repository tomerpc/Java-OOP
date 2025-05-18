# Java-OOP
# Arkanoid Game – Java OOP Course Project

This project is a Java-based implementation of the classic **Arkanoid** game, developed as part of an Object-Oriented Programming (OOP) course. The game was built from scratch with a strong emphasis on OOP principles such as encapsulation, inheritance, interfaces, modularity, and event-driven design.

---

## 🎮 Features

- **Multiple Levels** – Three unique levels, each with a custom background and block layout.
- **Animations** – Includes animations for:
  - Game countdown
  - Pause screen
  - Win/Lose end screens
- **Game Flow Management** – Handles transitions between levels and game states (start, pause, game over).
- **Collision System** – Custom physics for ball and block/paddle interactions.
- **Event Listeners** – Modular hit-listener system for tracking and reacting to collisions.
- **Score System** – Real-time score display and tracking throughout the game.

---

## 🧱 Code Structure

The source code is organized into several clearly separated packages:

### `Animation/`
Manages all game animations and screen transitions.
- `YouWinAnimation`, `YouLoseAnimation`, `CountdownAnimation`, etc.

### `GameEnvironment/`
Handles core gameplay logic, sprite management, and score display.
- `GameFlow`, `SpriteCollection`, `GameEnvironment`, etc.

### `HitListeners/`
Implements listeners for in-game events like removing blocks/balls or updating the score.
- `BlockRemover`, `BallRemover`, `ScoreTrackingListener`, etc.

### `Levels/`
Defines levels and visual backgrounds.
- `Level1Class`, `Level2Class`, `Level3Class`, `BackGround1`, etc.

### `Object/`
Core game objects like:
- `Ball`, `Block`, `Paddle`, `Counter`, etc.

### `Geometry/`
Mathematical classes for collision and movement.
- `Point`, `Line`, `Rectangle`, `Velocity`

---

## 🚀 Entry Point

The main entry point to launch the game is:
```java
Ass6Game.class

