# Basic Level Generator

This is a simple level generator script for Unity. It creates rooms with walls, floors, doors, and spawners. Each room is randomly generated, and the player can move between rooms through doors that appear after a delay.

## Features

- Randomly generated room dimensions
- Prefab-based walls, floors, and corners
- Doors that appear after a delay and trigger new room generation
- Enemy spawners
- Player teleportation to the center of the room

## Getting Started

### Prerequisites

- Unity 2020.3 or later

### Installation

1. Clone the repository or download the file.
2. Open your Unity project and import the scripts and prefabs into your project.

### Usage

1. Attach the `BasicLevelGenerator` script to an empty GameObject in your scene.
2. Assign the appropriate prefabs to the script's public fields in the Inspector:
    - Corner Prefabs (top left, top right, bottom left, bottom right)
    - Wall Prefabs (top, bottom, left, right)
    - Floor Prefab
    - Door Prefab
    - Spawner Prefab
3. Ensure your player GameObject has the tag "Player".
4. Start the game, and the level generator will create a room at the origin point. The player will be teleported to the center of the room.