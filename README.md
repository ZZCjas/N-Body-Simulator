# N-Body Simulator

An interactive multi-body gravitational simulation system developed with Python and Tkinter, capable of simulating celestial motion, collisions, and evolution under gravitational forces.

## Key Features

### 🌌 Core Physics Simulation
- **Precise Gravity Calculations**: Uses leapfrog integration for numerical simulation, ensuring energy conservation
- **Multi-body Interactions**: Supports gravitational interactions between any number of celestial bodies
- **Real-time Parameter Adjustment**: Adjustable time steps, boundary size, and other simulation parameters

### 💥 Collision & Fragmentation System
- **Smart Collision Detection**: Dual detection using geometric overlap
- **Fragment Generation**: Creates fragments based on energy ratios during collisions
- **Adjustable Parameters**: Roche coefficient, maximum fragment count, minimum mass, and more

### 🎮 Interactive Interface
- **Visual Display**: Real-time visualization of celestial positions, velocities, and trajectories
- **Data Monitoring**: Live display of physical quantities like velocity, acceleration, and mass
- **Flexible Operations**: Click-to-add, coordinate input, single-step execution, and more

### 🌟 Rich Example Systems
- **Binary Systems**: Stable equal-mass binary star systems
- **Three-Body Problem**: Classical three-body motion simulation
- **Planetary Systems**: Stars with orbiting planets
- **Gravity Assist**: Probe acceleration through gravitational slingshot effects
- **Lagrange Points**: Stability demonstration of L1-L5 points

## Technical Highlights

- **Modular Design**: Separated physics engine and UI interface for easy expansion
- **Performance Optimized**: Vectorized calculations using NumPy
- **Physical Realism**: Includes tidal forces, momentum conservation, and approximate energy conservation
- **Visual Effects**: Collision animations, color-coded fragments and main bodies

## Requirements

- Python 3.6+
- NumPy
- Tkinter (usually included with Python)

## Quick Start

```bash
python Nbody.py
```

1. Click on the canvas or input coordinates to add celestial bodies
2. Adjust mass, diameter, and initial velocity parameters
3. Click "Start" to run the simulation
4. Observe celestial motion, collisions, and evolution

## Application Scenarios

- **Physics Education**: Intuitive demonstration of gravitational laws and orbital mechanics
- **Scientific Research**: Verification of numerical methods for multi-body problems
- **Science Communication**: Visualization of astronomical phenomena
- **Algorithm Testing**: Reference for physics engine development

This simulator presents complex gravitational interactions in an intuitive way, allowing users to explore various astronomical phenomena from simple binary systems to complex multi-body systems.
