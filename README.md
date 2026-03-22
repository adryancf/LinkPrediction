# Link Prediction

Predicting missing edges in graphs using Machine Learning and Graph Neural Networks.

## Overview

This project implements link prediction using:
- **GNN (Graph Neural Network)** with PyTorch Geometric
- **Random Forest** classifier
- **Node2Vec** embeddings
- Structural features (centrality, communities)

## Structure

```
├── data/                  # Datasets and graph
├── pre_processing/        # Feature extraction & embeddings
├── link prediction/       # GNN and RF models
└── plots/                 # Visualizations
```

## Quick Start

1. **Preprocessing**
   ```bash
   jupyter notebook pre_processing/unified_preprocessing.ipynb
   ```

2. **Train Models**
   ```bash
   jupyter notebook "link prediction/gnn_link_prediction.ipynb"
   jupyter notebook "link prediction/randomForest.ipynb"
   ```

## Requirements

```
torch torch-geometric
networkx pandas scikit-learn
node2vec gensim python-louvain
matplotlib seaborn jupyter
```

## Results

Models output submission files with edge predictions and performance metrics (AUC, F1, AP).

---

**Course**: Network Science in UTFPR (Federal Technological University of Paraná)
