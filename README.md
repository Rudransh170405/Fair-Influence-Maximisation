# Influence Maximization in Social Networks (Greedy & CELF)

This project implements influence maximization using the Independent Cascade (IC) model with both Greedy and CELF (Cost-Effective Lazy Forward) algorithms. The experiments are run on Zachary's Karate Club graph, with visualization of selected seed nodes and their influence spread.

## Overview

Influence Maximization is the task of selecting k seed nodes in a network such that the expected spread of influence is maximized under a probabilistic diffusion model.

- Diffusion Model: Independent Cascade (IC)
- Algorithms: 
  - Greedy Influence Maximization
  - CELF (an optimized Greedy variant using lazy evaluations)

## Dataset

- Graph: Karate Club Graph (networkx.karate_club_graph)
- Nodes: 34
- Edges: 78 (undirected)

## Features

- Simulates influence spread using Independent Cascade model
- Implements both Greedy and CELF algorithms
- Tracks computational cost (number of influence spread simulations)
- Visualizes selected seed nodes in the network


