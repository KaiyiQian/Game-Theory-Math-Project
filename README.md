# Game Theory for Mathematicians

This repository contains Jupyter notebooks analyzing different game theory models in strategic scenarios and Prisoner's Dilemma on a Torus. The focus is mainly analyzing strategic interactions using computational methods.

## Table of Contents
- [Introduction](#introduction)
- [Notebooks](#notebooks)
  - [RepeatedGames.ipynb](#1-RepeatedGames.ipynb)
  - [ChainStore.ipynb](#2-chainstoreipynb)
  - [PD_on_Torus.ipynb](#3-pd_on_torusipynb)
- [Installation](#installation)
- [Dependencies](#dependencies)

## Notebooks
**1. RepeatedGames.ipynb**

This Notebook explores 6 types of repeated games scenarios (Tit-for-Tat, Always Defect, Grim Trigger, Always Cooperate, Generous Tit-for-Tat and Adaptive)

**2. ChainStore.ipynb**

In this notebook, we test the competing ideas in the paradox by setting up a variety of “chainstore strategies” (AlwaysFight, AlwaysAccommodate, GrimTrigger-Chain, TitForTatChain) and “challenger strategies” (AlwaysEnter, GrimTrigger, TitForTat).  And the two sides play one another for 20 rounds.

**3. PD_on_Torus.ipynb**

## Installation
To run these notebooks, ensure you have Python and Jupyter Notebook installed. You can install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

Or, if a `requirements.txt` file is not provided, install the core dependencies manually:

```bash
pip install numpy pandas matplotlib scipy jupyter
```
## Dependencies
These notebooks require the following Python libraries:
- `numpy` (for numerical computations)
- `pandas` (for data manipulation)
- `matplotlib` (for visualizations)
- `scipy` (for game-theoretic analysis)
- `jupyter` (for running the notebooks)

