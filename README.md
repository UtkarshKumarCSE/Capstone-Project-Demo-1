# Capstone Project — IMPSO Cloud Task Scheduler

**Project title:** Energy-Efficient Multi-Objective Task Scheduling using Improved Particle Swarm Optimization (IMPSO)

A B.Tech capstone project exploring cloud task scheduling across heterogeneous virtual machines.

## Live demo

Once GitHub Pages is enabled, the interactive dashboard will be published at:

**https://utkarshkumarcse.github.io/Capstone-Project-Demo-1/**

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Choose a workload size, search population, iteration count, and random seed.
4. Click **Run demo simulation**.
5. Click **Export results as CSV** to save the output.

No Java installation is required for this browser-based demo.

## What the demo currently shows

- Synthetic independent tasks
- Heterogeneous virtual-machine profiles
- Round Robin baseline comparison
- A simplified discrete search heuristic
- Estimated energy, makespan, and load imbalance
- VM load table and CSV export

## Important status note

This browser dashboard is an **educational prototype using a simplified search heuristic**. It is not yet the canonical IMPSO algorithm and does not use CloudSim. Its numbers are estimates from the simplified model and must not be presented as validated research results.

## Planned capstone implementation

The intended research implementation will use Java and CloudSim 3.0 and work toward the features in the approved project report:

- Non-linear adaptive inertia weight
- Pareto archive and diversity-aware leader selection
- Energy, makespan, and load-imbalance objectives
- DVFS-aware energy modelling with documented assumptions
- Baseline scheduling algorithms and workloads from 50 to 1,000 tasks
- Reproducible experiments, charts, and results analysis

## Team

- Utkarsh Kumar
- Gagan Tiwari

## Technology

- HTML, CSS, JavaScript — interactive demo
- Java + CloudSim 3.0 — planned simulator implementation

## License

No open-source license has been selected yet.
