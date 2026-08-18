---
title: "Graph Neural Networks for Power System Operation"
excerpt: "PhD research project: geometric deep learning that generalizes across grid topologies — from AC optimal power flow to EMT simulation surrogates.<br/>"
collection: portfolio
---

Power grids are graphs: buses are nodes, lines and transformers are edges. My PhD research at the Delft AI Energy Lab builds on this observation to develop **graph neural networks (GNNs) that learn the physics of power system operation** and generalize to grid topologies and operating conditions they were never trained on.

**Why it matters.** Grid operators solve hard computational problems — optimal power flow, security assessment, time-domain simulation — every few minutes, and conventional solvers struggle to keep up as renewables make the grid more dynamic. Machine learning surrogates can be orders of magnitude faster, but only if they remain trustworthy when the grid changes shape. That generalization gap is the core of my work.

**What I've built:**

* GNN architectures for **AC optimal power flow** that transfer across network topologies ([Energy and AI, 2026](https://doi.org/10.1016/j.egyai.2026.100842))
* **Spatio-temporal GNNs** for multi-period optimal power flow ([IEEE PES ISGT Europe, 2025](https://doi.org/10.1109/ISGTEurope64741.2025.11305408))
* Machine learning surrogates for **time-domain / electromagnetic transient (EMT) simulation**, with a systematic study of their extrapolation behavior ([SEGAN, 2025](https://doi.org/10.1016/j.segan.2025.101908))
* **Learning-accelerated distributed optimization** (ADMM) for stochastic scheduling with numerous scenarios ([IEEE Transactions on Sustainable Energy, 2025](https://doi.org/10.1109/TSTE.2025.3562640))

**Stack:** Python, PyTorch, PyTorch Geometric, power-system simulation tools.
