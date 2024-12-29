# Social Behavior Dynamics Simulation

This repository contains a Python-based Agent-Based Model (ABM) for simulating and analyzing social behavior dynamics in a population of agents. 

## Features
- Simulates interactions between agents on a 2D grid.
- Tracks three social states:
  - **Neutral**: No particular social behavior.
  - **Social**: Positive engagement with others.
  - **Antisocial**: Negative engagement with others.
- Visualizes how agents' social states evolve over time.

## How It Works
1. **Agents** are placed on a 2D grid.
2. Each agent interacts with its neighbors, influencing their social behavior based on a predefined probability.
3. The model runs for a fixed number of steps, collecting data on the distribution of social states at each time step.
4. The results are visualized using a line plot, showing the dynamics of social behavior over time.

## Setup and Usage
### Prerequisites
- Python 3.6+
- Required libraries: `mesa`, `matplotlib`, `pandas`

Install the required libraries using:
```bash
pip install mesa matplotlib pandas
