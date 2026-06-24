# Multi-Agent Reinforcement Learning for Warehouse Location Optimization

## Overview

This project applies **Multi-Agent Reinforcement Learning (MARL)** to a warehouse location optimization problem in logistics.

Each candidate warehouse is modeled as an agent that decides whether to open or remain closed. The agents cooperate to maximize the overall logistics profit while considering:

* Warehouse opening cost
* Transportation cost
* Warehouse capacity
* Customer demand
* Service coverage
* Overlapping service areas

The implementation is based on the **MAPPO (Multi-Agent Proximal Policy Optimization)** algorithm with the **Centralized Training with Decentralized Execution (CTDE)** paradigm.

---

## Problem Description

The project studies a profit-oriented variant of the Capacitated Facility Location Problem (CFLP).

Input:

* Candidate warehouse locations
* Customer demand distribution
* Warehouse capacities
* Transportation costs

Output:

* Warehouses to open
* Warehouses to close
* Profit and service performance metrics

---

## Method

The workflow consists of:

1. Generate candidate warehouse locations
2. Create demand distribution from population density
3. Build MARL environment
4. Train MAPPO agents
5. Evaluate the final warehouse selection strategy

---

## Evaluation Metrics

The following metrics are used:

* Total Profit
* Revenue
* Transportation Cost
* Warehouse Opening Cost
* Service Coverage
* Capacity Utilization
* Number of Open Warehouses
* Training Time

---

## Results

The proposed MAPPO approach is compared with:

* Random
* Greedy

Experimental results show that MAPPO achieves higher profit and better service quality while maintaining reasonable operational costs.

---




## Author

Nguyen Duc Anh

Phenikaa University

Course Project – Multi-Agent Reinforcement Learning for Logistics Facility Location
