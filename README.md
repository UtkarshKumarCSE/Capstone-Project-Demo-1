# Capstone-Project-Demo-1
Energy-Efficient Multi-Objective Task Scheduling using Improved Particle Swarm Optimization (IMPSO) — interactive demo and capstone development.

# Energy-Efficient Multi-Objective Task Scheduling using IMPSO

A B.Tech CSE capstone project exploring energy-efficient task scheduling in cloud computing using an Improved Multi-Objective Particle Swarm Optimization (IMPSO) approach.

## Project Overview

Cloud data centers execute tasks across virtual machines (VMs). Poor scheduling can increase energy consumption, completion time, and uneven resource utilization.

The objective of this project is to develop and evaluate a scheduling approach that considers three objectives:
- Minimize energy consumption
- Minimize makespan (total completion time)
- Minimize load imbalance across VMs

## Current Demo

The repository's initial browser-based prototype provides:
- A configurable synthetic task workload
- Heterogeneous VM specifications
- A simplified scheduling demonstration
- A comparison with a Round Robin baseline
- A results table and visual comparison
- CSV export

### Run the HTML Demo

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Choose a task count and parameters.
4. Click **Run demo simulation**.
5. Click **Export results as CSV** to save the demo output.

No Java installation is required for this browser-based demo.

## Planned Implementation

The intended capstone implementation follows the project report:
- Java and CloudSim 3.0 simulation environment
- Heterogeneous hosts and virtual machines
- Adaptive inertia weight
- Pareto-based archive and leader selection
- Energy, makespan, and load-imbalance evaluation
- Comparison with baseline scheduling algorithms
- Workload testing from 50 to 1,000 tasks
- Experiment results, charts, and analysis

## Current Status

The HTML dashboard is an educational prototype using a simplified discrete search procedure. It is **not yet the canonical IMPSO implementation and does not produce CloudSim simulation results**. Results must not be treated as validated research findings.

The Java/CloudSim implementation and experimental validation are planned next steps.

## Technology

- HTML, CSS, JavaScript — interactive demo
- Java — planned scheduling implementation
- CloudSim 3.0 — planned cloud simulation framework

## Academic Project

B.Tech Capstone Project  
**Title:** Energy-Efficient Multi-Objective Task Scheduling using Improved Particle Swarm Optimization (IMPSO)

## Contributors

- Utkarsh Kumar
- Gagan Tiwari

## License

No open-source license has been selected yet.
