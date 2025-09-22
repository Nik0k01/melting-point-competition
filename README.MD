# 🧊 Melting Point Prediction

[![Kaggle Competition](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle)](https://www.kaggle.com/competitions/melting-point)
[![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)](https://www.python.org/)
[![Notebooks](https://img.shields.io/badge/Notebooks-Jupyter%2BColab-orange?logo=jupyter)](https://jupyter.org/)

This repository contains my machine learning solutions for the **Kaggle competition: "Thermophysical Property: Melting Point"**, hosted by Frank Mtetwa and John Hedengren.

Predicting the melting point of organic molecules is a significant challenge in chemistry and chemical engineering. This property is crucial for applications in **drug design, material science, and process safety**. However, experimental determination can be costly and time-consuming.

This competition tasks participants with building ML models to predict melting points using **group contribution features**—subgroup counts that represent the functional groups within each molecule. The goal is to capture the complex, nonlinear relationships between molecular structure and melting behavior.

Through adding all of the RDKit descriptors and tweaking the parameters of RandomForest i managed to achieve MAE 29.76197 which placed me middle of the pack in the competition leaderboard. This was a fun experiance! 