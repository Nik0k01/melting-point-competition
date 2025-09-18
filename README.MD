# 🧊 Melting Point Prediction

[![Kaggle Competition](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle)](https://www.kaggle.com/competitions/melting-point)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Notebooks](https://img.shields.io/badge/Notebooks-Jupyter%2BColab-orange?logo=jupyter)](https://jupyter.org/)

This repository contains my machine learning solutions for the **Kaggle competition: "Thermophysical Property: Melting Point"**, hosted by Frank Mtetwa and John Hedengren.

Predicting the melting point of organic molecules is a significant challenge in chemistry and chemical engineering. This property is crucial for applications in **drug design, material science, and process safety**. However, experimental determination can be costly and time-consuming.

This competition tasks participants with building ML models to predict melting points using **group contribution features**—subgroup counts that represent the functional groups within each molecule. The goal is to capture the complex, nonlinear relationships between molecular structure and melting behavior.

## 📁 Repository Structure

melting-point-competition/
├── data/ # Directory for competition data (not stored on GitHub)
├── notebooks/ # Jupyter notebooks for analysis and modeling
│ └── 01_baseline_model_decision_tree.ipynb.ipynb
├── README.md # This file
└── environment.yaml # Python dependencies