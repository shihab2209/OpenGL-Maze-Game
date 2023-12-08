# OpenGL Maze Game

This interactive maze game is implemented using OpenGL in Python. Players navigate a circle through a maze using the WASD keys on the keyboard.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Controls](#controls)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A maze is a type of puzzle game where a player navigates through complex and branched passages to reach a specific target or location. This project utilizes the mid-point line drawing algorithm to create the maze structure and the mid-point circle drawing algorithm to represent the player's ball. The transformation method is employed to move this ball within the maze.

The Desmos calculator is utilized to create a precise shape for the maze and determine the actual coordinates. This tool significantly aids in saving time during the maze creation process.

## Features

- Maze navigation using WASD keys
- Utilizes mid-point line and circle drawing algorithms
- Transformation method for moving the player's ball within the maze
- Creation of complex maze structures
- Desmos calculator integration for maze design

## Prerequisites

To run this project locally, you'll need:

- Python (version 3.x)
- OpenGL library
- Keyboard library (for handling keyboard inputs)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/shihab2209/OpenGL-Maze-Game.git
    ```

2. Install the required dependencies:

    ```bash
    pip install opengl keyboard numpy
    ```

## Usage

To run the game, navigate to the project directory and execute the main Python file:

```bash
python opengl_maze_game.py
```

## Controls

- `W`: Move the ball up
- `A`: Move the ball left
- `S`: Move the ball down
- `D`: Move the ball right
- `R`: Restart the game
- `ESC`: Exit the game

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, please feel free to create an issue or a pull request.

