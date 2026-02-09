# Reusable Rocket Inventory Optimization

**Type**: Reinforcement agent for stock levels

**Description**: Build a reinforcement learning or ML model (like scikit-optimize) to manage multi-echelon inventory for rocket parts—accounting for reusable turnaround times, high launch cadences, and lower costs.

**First Principles**: Holding cash dies, reusability rebirths it. Queueing law—flow times lag equals pile-up. Optimize from there.

**Approach**: Incorporate scenarios where Starship reusability reduces holding costs by twenty-two percent (like Raytheon examples). Add sensitivity analysis on launch frequency impacts.

## Interactive Visualizer
🚀 **[Launch Inventory Alchemist](visualizer.html)**
Explore Reinforcement Learning optimization for multi-echelon inventory in real-time.

## Overview
This repository explores optimizing inventory for reusable aerospace systems using RL, focusing on Little's Law and cost-per-flight reduction.

## Getting Started
1. Install dependencies: `pip install -r requirements.txt`
2. Explore the inventory environment in `notebooks/`.
3. Check [data_links.md](docs/data_links.md) for supply chain datasets.
