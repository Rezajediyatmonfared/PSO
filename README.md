# Migratory Bird Path Optimization Using Particle Swarm Optimization (PSO)

This project simulates migratory bird route planning using **Particle Swarm Optimization (PSO)**. The goal is to find an energy-efficient path from a starting point to a destination while considering environmental factors such as wind, altitude, food availability, and hazards.

The model represents a bird's migration route as a sequence of waypoints and uses PSO to optimize those waypoints over multiple iterations.

## Project Idea

Migratory birds do not always fly in a straight line. Their routes are influenced by many environmental and survival-related factors, such as:

- Energy consumption over long distances
- Favorable wind direction
- Changes in altitude
- Access to food sources
- Avoidance of dangerous areas

This project models that behavior as an optimization problem and solves it using Particle Swarm Optimization.

## Features

- Uses **Particle Swarm Optimization (PSO)** to optimize a migration path
- Represents the path as a set of intermediate waypoints
- Models energy consumption using multiple environmental effects
- Includes randomly generated:
  - food sources
  - hazards
- Visualizes the final optimized route with `matplotlib`
- Easy to modify for experimentation and research purposes

## Technologies Used

- Python
- NumPy
- Matplotlib

## Problem Setup

The bird starts at:
```python
start = np.array([0, 0])
