# Hidden Markov Modelling of Brain State Dynamics

## Overview
This project analyses large-scale brain activity using Hidden Markov Models to identify latent brain states across tasks.

---

## Dataset
- Human Connectome Project (N=339)
- 360 brain regions (Glasser parcellation)
- Multiple cognitive tasks + resting state

---

## Approach
- Modelled fMRI time series using HMMs
- Identified latent brain states and transitions

### Analysis
- State similarity:
  - Euclidean distance
  - Cosine similarity
  - Pearson correlation

### Visualisation
- Brain network visualisation using nilearn

---

## Results
- Identified consistent latent states across tasks
- Observed task-dependent transition patterns

---

## Tech Stack
- Python
- nilearn
- NumPy, SciPy

---

## Key Insights
- Brain activity can be represented as transitions between discrete states
- State dynamics vary significantly across cognitive tasks

---

## Future Work
- Link brain states to behavioural outcomes
- Apply to clinical datasets
