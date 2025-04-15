# Stochastic SIR and Network Simulations

This project simulates the spread of infectious diseases using stochastic SIR models and explores how different network topologies affect the dynamics of transmission. It implements Gillespie’s algorithm with Monte Carlo simulations, compares deterministic and stochastic models, and analyzes various vaccination strategies.

## Course Info

This project was created as part of the course **"Introduction to Computational Science"** at the **University of Amsterdam**.

It was completed in collaboration with **Zoë Azra Blei** as part of our group assignment.

## Features

- Stochastic and deterministic SIR model comparison
- Implementation of Gillespie’s algorithm (with optional Gaussian noise)
- Simulation of disease spread on:
  - Erdős–Rényi networks
  - Barabási–Albert networks
  - Watts–Strogatz networks
- Targeted vaccination strategies based on node centrality

## Project Structure

notebooks/          # Jupyter Notebook with the full simulation and analysis  
report/             # Final PDF report with background, methods, and results  
figures/            # Plots exported from simulations  

## ▶️ How to Run

Install the required Python packages:

pip install -r requirements.txt

Then open the notebook:

jupyter notebook notebooks/DErcole_15424596_Blei_15762467_assignment2.ipynb

## 👥 Authors

- Costanza D’Ercole  
- Zoë Azra Blei
