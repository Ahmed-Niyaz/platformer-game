# Platformer Game

## Demo

[Platformer Game Demo](https://ahmed-niyaz.github.io/platform-game/)

## Overview

This is a simple platformer game developed using HTML5, CSS, and JavaScript. The player navigates through different platforms to reach checkpoints using keyboard controls. The game demonstrates the use of object-oriented programming (OOP) concepts in JavaScript to create an interactive and engaging user experience.

## Features

- Interactive platformer gameplay
- Multiple platforms
- Platform collision detection that prevents the player from falling off or passing through platforms.
- Gravity simulation to add a realistic movement effect.
- Checkpoints that act as milestones for the player to reach.

## Object-Oriented Programming Concepts

This project showcases several OOP concepts:

- **Classes**: The game utilizes classes such as `Player`, `Platform`, and `CheckPoint` to create and manage game objects.
- **Encapsulation**: Each class encapsulates its own properties and methods, keeping the code organized and modular.
- **Polymorphism**: The `draw()` method is implemented differently for each class, demonstrating polymorphism.
- **Inheritance**: While not explicitly shown in the provided code, the project structure allows for easy implementation of inheritance if needed (e.g., creating different types of players or platforms).
- **Abstraction**: Game mechanics are abstracted into simple methods like `update()`, `claim()`, and `animate()`.

## Code Structure

- **index.html**: The main HTML file that structures the game's UI.
- **styles.css**: Contains the styling for the game elements.
- **script.js**: The main JavaScript file containing the game logic and OOP implementation.

## Key Classes

### Player

- Represents the main character in the game.
- **Properties**: `position`, `velocity`, `width`, `height`.
- **Methods**: `draw()`, `update()`.

### Platform

- Represents the platforms in the game.
- **Properties**: `position`, `width`, `height`.
- **Methods**: `draw()`.

### CheckPoint

- Represents the checkpoints in the game.
- **Properties**: `position`, `width`, `height`, claimed status.
- **Methods**: `draw()`, `claim()`.

## Game Loop

The game uses `requestAnimationFrame()` to create a smooth animation loop. The `animate()` function handles:

- Clearing the canvas
- Drawing game objects
- Updating player position
- Handling collisions
- Moving the game world

## Event Handling

The game responds to keyboard inputs for player movement:

- Arrow keys for movement
- Spacebar for jumping

## How to Run

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Press the "Start Game" button to begin playing.
