# DisasterResourceOpt

**DisasterResourceOpt** is a project that optimizes post-disaster resource allocation using **Genetic Algorithms** and **Simulated Annealing** to meet area demands efficiently, minimizing travel distances and adhering to resource constraints.

## Features
- **Multi-Objective Optimization**: Balances distance minimization with demand satisfaction.
- **Genetic Algorithm (GA)**: Population-based evolution using mutation, crossover, and elitism.
- **Simulated Annealing (SA)**: Gradual refinement using temperature-controlled exploration.
- **Constraint Handling**: Respects resource and demand limits.

## Algorithms & Parameters
- **Genetic Algorithm (GA)**: Population Size (50–300), Mutation Rate (0.3–0.9), Crossover Type, Elitism.
- **Simulated Annealing (SA)**: Initial Temperature (1000), Cooling Rate (0.995), Neighborhood Size (e.g., 10, 50).

## Installation
```bash
git clone https://github.com/username/DisasterResourceOpt.git
cd DisasterResourceOpt
pip install -r requirements.txt
