# Robot Maze Decision-Making Simulation

This project is a simple robot decision-making simulation built with Python and Pygame.  
It demonstrates how a robot can sense obstacles in a maze and decide how to move based on simple rules and random decisions.

## Description

In this simulation, a robot navigates through a 2D maze represented by walls and pathways.  
The robot is equipped with a basic distance sensor, which detects if an obstacle is near in front of it.  
Based on the sensor reading, the robot makes a decision to:
- Move forward if no obstacle is detected.
- Otherwise, randomly choose between turning left, turning right, or stopping.

The simulation visually shows:
- The robot’s current position and orientation.
- The maze walls.
- The robot’s sensing line.
- Real-time text displaying the robot’s sensor reading, chosen action, and reasoning.

## Features

- 2D Maze with walls and pathways
- Robot represented as a circle with a directional sensor line
- Obstacle detection within a short range
- Decision-making logic combining deterministic and random choices
- Real-time display of actions and reasoning
- Built entirely in Python with Pygame
```

