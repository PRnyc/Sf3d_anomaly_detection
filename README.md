# 📚 Evaluation of Mesh Reconstructions from SF3D for Anomaly Detection

Code for 3D anomaly detection using SF3D reconstructions and Graph Autoencoders, developed for my Master’s Thesis.

This repository contains the code and experiments from my Master’s Thesis:  
**"Evaluation of the Potential of Mesh Reconstructions from SF3D for Anomaly Detection"**  
*(University of Wuppertal, 2025)*

It integrates **SF3D-based 3D mesh reconstruction** and **Graph Autoencoder (GAE)** anomaly detection — all in a unified Jupyter Notebook.

---

## 📂 Repository Structure

| Folder / File            | Description |
|---------------------------|-------------|
| `graph.ipynb`             | Main notebook: full pipeline for mesh reconstruction, graph conversion, GAE training, and evaluation |
| `sf3d/`                   | Downloaded SF3D repository (Stable Fast 3D) for 3D mesh generation |
| `images/input/`           | Input images for SF3D mesh reconstruction (e.g., chairs, cups) |
| `images/output/`          | Reconstructed meshes and anomaly visualizations |
| `requirements.txt` (optional) | Python dependencies list (PyTorch, Open3D, PyG, etc.) |

---

## 🚀 How to Run

1. Clone this repository and make sure you have the SF3D repo downloaded inside.

2. Install the required dependencies:

```bash
pip install -r requirements.txt


