# Pacman Q-learning

CDS524 Assignment 1 - Reinforcement Learning Game Design

## Project Overview

This project implements a Pacman game where an AI agent learns to play using the Q-learning reinforcement learning algorithm. The agent learns to eat all pellets while avoiding a ghost.

## Game Features

- **10×10 Grid World**: Pacman and ghost move in a discrete grid
- **State Space**: 25 states (ghost direction × pellet direction)
- **Action Space**: 4 actions (Up, Down, Left, Right)
- **Reward System**: 
  - Eating pellet: +20
  - Valid movement: +0.1
  - Caught by ghost: -5
  - Victory: +30
  - Boundary attempt: -0.3

## Q-learning Implementation

- **Learning Rate (α)**: 0.1
- **Discount Factor (γ)**: 0.9  
- **Exploration Rate (ε)**: 0.2 → 0.01 (decay 0.995)
- **Training Episodes**: 700
- **State Space Explored**: 25/25 states

## How to Run

### Requirements
```bash
pip install numpy matplotlib# Pacman Q-learning
