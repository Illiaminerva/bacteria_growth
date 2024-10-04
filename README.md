# Bacteria Growth Simulation

## Project Overview
This project involves simulating the growth and behavior of bacteria within a grid-based ecosystem, exploring the effects of varying initial parameters on bacterial evolution. This simulation can help in understanding population dynamics and resource management in microbial communities.

## Background
The simulation is based on a model where a grid represents an environment with food and bacteria. Each grid cell contains food units and bacteria, with the food having a maximum capacity. The simulation incorporates periodic boundary conditions to mimic an infinite looping environment, providing a realistic model for bacterial movement and growth dynamics.

## Features
- **Grid-based Simulation Environment:** Represents an ecosystem with configurable size and properties.
- **Dynamic Food and Bacteria Growth:** Simulates real-time interactions between food supply and bacterial growth.
- **Customizable Simulation Parameters:** Allows users to set initial values for food capacity, growth rates, and other essential factors.
- **Visualization:** Animations showing the change in grid states over time, tracking food and bacteria populations.

## Objectives
- To analyze how different growth rates and food availabilities affect bacterial proliferation.
- To observe the long-term population stability under various simulation settings.
- To provide insights into optimal conditions for bacterial survival and expansion.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the simulation with different parameters by modifying the configuration settings in `config.py`.
4. View the results through the generated animations and output data files.

## Key Results
- **Population Dynamics:** Understanding how bacterial populations change in response to environmental conditions.
- **Resource Utilization:** Analysis of how efficiently bacteria can consume and deplete available resources.
- **Optimal Growth Conditions:** Recommendations on environmental settings that support sustainable bacterial growth.

## Installation
```bash
git clone https://github.com/yourusername/bacteria-growth-simulation.git
cd bacteria-growth-simulation
pip install -r requirements.txt
