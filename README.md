# Robotic Car Painting Cell Simulation

**Robotics Simulation Intern Assessment — Yuktii AI Labs**

## Overview
This project demonstrates an industrial robot simulation for painting the roof of a vehicle using RoboDK. It focuses on robot setup, painting-tool integration, target-based trajectory planning, simulation, and collision checking.

## Software and Robot
- **Simulation software:** RoboDK
- **Industrial robot:** ABB IRB 2600ID-8/2.00
- **End-effector:** Generic Paint Sprayer
- **Application:** Vehicle roof painting simulation

## Simulation Features
- 3D vehicle model and basic robotic cell layout
- Industrial robot with a painting tool
- Taught robot target positions
- Simulated roof-painting trajectory
- Path visualization in RoboDK
- Collision checking using RoboDK

## Validation
The RoboDK collision check reported:

> No problems found for this path. No collisions detected.

This result applies to the program path checked in the simulation. The demonstrated trajectory focuses on the roof; complete exterior vehicle coverage is not claimed.

## Project Files
- `Simulation_Files/` — RoboDK station file
- `Screenshots/` — simulation and validation evidence
- `Demo_Video/` — demonstration video links

## How to View
1. Install RoboDK.
2. Download `Car_Painting_Cell_v2.rdk` from `Simulation_Files/`.
3. Open the file in RoboDK.
4. Run the robot program to view the roof trajectory.

## Author
**Swarup Jadhav**

Prepared for the Yuktii AI Labs Robotics Simulation Intern assessment.
