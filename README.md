# SE4050 – Deep Learning Lab 1
## Introduction to Python Libraries for Deep Learning

This repository contains the complete solutions for **Lab Sheet 1** of the SE4050 Deep Learning course.  
The objective of the lab is to familiarize students with essential Python libraries used in deep learning, including **NumPy**, **Matplotlib**, **Pandas**, and **Seaborn**.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Dataset Information](#dataset-information)
- [Tasks & Solutions](#tasks--solutions)
  - [Task 1 – Basic NumPy & Matplotlib](#task-1--basic-numpy--matplotlib)
  - [Task 2 – Au Nanoparticle Data Analysis](#task-2--au-nanoparticle-data-analysis)
- [Running the Notebook](#running-the-notebook)
- [Results Summary](#results-summary)
- [Submission](#submission)
- [Acknowledgements](#acknowledgements)

---

## Overview

The lab is split into two main parts:

1. **Task 1** – Exercises with NumPy and Matplotlib:
   - Generate random arrays from exponential distribution.
   - Visualise histograms of exponential, uniform, and normal distributions.
   - Create a 3D surface plot of \( Z = X^2 + Y^2 \).
   - Compute Pearson and Spearman correlations on Pokémon stats and visualise with heatmaps.

2. **Task 2** – Data analysis with Pandas and Seaborn using the **Au nanoparticle dataset**:
   - Filter the dataset to keep only four features: `N_total`, `N_bulk`, `N_surface`, `R_avg`.
   - Display first 20 samples.
   - Calculate descriptive statistics (mean, std, quartiles).
   - Plot histograms in a 1×4 layout.
   - Generate pairplots and custom PairGrid visualisations.

All code is written in a single Jupyter Notebook (`.ipynb`) and can be run in **Google Colab** or locally.

---

## Requirements

The code requires the following Python libraries:

- `numpy`
- `matplotlib`
- `pandas`
- `seaborn`
- `scipy` (for correlation)
- `mpl_toolkits.mplot3d` (built‑in with matplotlib)
  The Pokémon dataset is loaded directly from a public GitHub repository: URL: https://raw.githubusercontent.com/omkarsawant30/Pokemon---Gotta-catch-Em-all-/master/Pokemon.csv

