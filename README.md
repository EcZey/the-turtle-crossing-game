# Turtle Crossing Game

Welcome to the Turtle Crossing game! In this game, you control a turtle that must navigate across the screen while avoiding moving cars. The goal is to reach the finish line and advance through levels as you avoid collisions with cars.

## Project Overview

This project simulates a turtle crossing game using Python's `turtle` graphics library. It features:
- A turtle controlled by the player.
- Moving cars that pose obstacles.
- A scoring system that tracks the player's level.

## Features

- **Player Movement**: Control the turtle using the Up arrow key.
- **Car Movement**: Cars move across the screen at increasing speeds.
- **Level Advancement**: Each time the player reaches the finish line, the level increases, making the cars move faster.
- **Collision Detection**: The game ends if the turtle collides with a car.
- **Scoreboard**: Displays the current level and game over message.

## Requirements

- Python 3.10 or newer (Tested with Python 3.12)
- `turtle` module (comes with Python standard library)

## Usage

1. **Run the Game**:
   Execute `python main.py` to start the game.

2. **Controls**:
   - **Player**: 
     - **Up Arrow**: Move the turtle forward.

3. **Gameplay**:
   - The turtle moves forward each time the Up arrow key is pressed.
   - Avoid colliding with moving cars.
   - Reach the finish line to advance to the next level.
   - The game ends if the turtle collides with a car.

4. **Exiting the Game**:
   - Click on the window to exit the game.

## Code Structure

- **`main.py`**: The main file that runs the Turtle Crossing game.
- **`player.py`**: Contains the `Player` class that manages the turtle's movement and position.
- **`car_manager.py`**: Contains the `CarManager` class that creates and manages the cars.
- **`scoreboard.py`**: Contains the `Scoreboard` class that handles the display of the current level and game over message.

## Object-Oriented Programming

This project utilizes Object-Oriented Programming (OOP) principles to structure the game:
- **Encapsulation**: The `Player`, `CarManager`, and `Scoreboard` classes encapsulate related data and behavior.
- **Inheritance**: The `Player`, `CarManager`, and `Scoreboard` classes inherit from the `Turtle` class to leverage its functionalities.

