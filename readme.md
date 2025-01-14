# Flappy Bird AI Using NEAT

This project implements an AI agent to play Flappy Bird using the **NEAT (NeuroEvolution of Augmenting Topologies)** algorithm. The bird learns to play by evolving its neural network over generations.

---

## Features
- **Flappy Bird Gameplay**: A basic implementation of the Flappy Bird game using `pygame`.
- **NEAT Integration**: The AI agent learns to play by evolving its neural network using the NEAT library.
- **Dynamic Obstacles**: Pipes appear at random heights and move across the screen.
- **Fitness Evaluation**: The bird is rewarded for staying alive longer and successfully passing pipes.

---

## Prerequisites
Make sure you have the following installed:
- Python 3.x
- Required Python libraries:
  - `pygame`
  - `neat-python`

You can install the dependencies using:
```bash
pip install pygame neat-python
