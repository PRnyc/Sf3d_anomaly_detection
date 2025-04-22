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

3. Install the required dependencies:

```bash
pip install -r requirements.txt

```

## Follow the Notebook Steps:
Reconstruct a 3D mesh from an image using SF3D

Train a Graph Autoencoder (GAE)

Create synthetic anomalies (vertex shifts, holes, cracks)

Visualize and evaluate anomaly detection

## 🔥 Key Results

F1-score: 0.81 on synthetic datasets

AUC-ROC: 0.90

Real-world generalization: Detecting natural defects in SF3D-generated meshes

Color-coded heatmaps and ROC curves are generated inside the notebook.

## 🛠️ Technologies

Stable Fast 3D (SF3D)

PyTorch

PyTorch Geometric (PyG)

Open3D

Jupyter Notebook


## 🧠 Thesis Reference Agyapong, P. K. (2025). Evaluation of the Potential of Mesh Reconstructions from SF3D for Anomaly Detection. Master of Science Thesis, University of Wuppertal.


## 📚 External Dependencies 
SF3D (Stable Fast 3D) for 3D mesh reconstruction was downloaded and used under its original license.

SF3D GitHub Repository

Credit to the original authors of SF3D for their open-source contribution.

Note: The sf3d/ directory refers to the downloaded SF3D repository.
Please download it separately from: https://github.com/OpenVisionAI/Stable-Fast-3D

## 🛡️ License This project is licensed under the MIT License.

Developed with ❤️ in the spirit of Computer simulations and machine learning research.

