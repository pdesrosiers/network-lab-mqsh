# Network Lab – MQSH 2025  
*Hands-on introduction to network analysis in social sciences, health, and neuroscience*

This repository contains interactive Jupyter notebooks prepared for the practical workshop at the **Colloque Méthodes quantitatives en sciences humaines (et santé)**, held in person on June 5–6, 2025, at the MIL Campus of Université de Montréal (rooms AB1007, B2061, and A3541).
---

## Overview

Many phenomena in social sciences, health, and neuroscience arise from complex webs of interactions — between individuals, symptoms, brain regions, or social variables. These relational structures span multiple scales, from neurons to societies, and often resist traditional quantitative approaches.

Network science provides a formal framework to represent and analyze such complexity. Rooted in graph theory and enriched by contributions from physics, computer science, and biology, it offers tools to better understand the interdependence underlying many biological and human systems.

This workshop offers an accessible introduction through practical exercises and real-world examples. No programming experience is required.

---

## Notebooks

### 1. Introduction to Network Analysis

- Basic definitions: nodes, edges, degree
- Visualizing networks with NetworkX
- Centrality and clustering measures
- Simple network models

📁 [`network_intro.ipynb`](notebooks/network_intro.ipynb)  
<a target="_blank" href="https://colab.research.google.com/github/pdesrosiers/network-lab-mqsh/blob/main/notebooks/network_intro.ipynb">  
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>  
</a>

### 2. Real-World Networks

- Explore simplified datasets from social, health, and neuroscience domains
- Identify structural features and interpret centrality
- Compare different types of networks

📁 [`real_world_networks.ipynb`](notebooks/real_world_networks.ipynb)  
<a target="_blank" href="https://colab.research.google.com/github/pdesrosiers/network-lab-mqsh/blob/main/notebooks/real_world_networks.ipynb">  
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>  
</a>

---

## Getting Started

### ▶️ Run in Google Colab (Recommended)

Click the **"Open in Colab"** badge under each notebook to run it in your browser — no installation needed.

💾 Save a personal copy via  
```File → Save a copy in Drive```

### 🖥️ Run Locally

```bash
git clone https://github.com/pdesrosiers/network-lab-mqsh
cd network-lab-mqsh
pip install -r requirements.txt
jupyter notebook
```

---
## Author

Patrick Desrosiers (CERVO Brain Research Center & Université Laval)