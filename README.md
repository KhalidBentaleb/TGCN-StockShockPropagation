# TGCN: Stock Market Shock Propagation with Graph Neural Networks

Official implementation of a Temporal Graph Convolutional Network (TGCN) framework for analyzing and comparing the propagation of stock market shocks.

Based on the paper:  
*A Graph Neural Network for Comparing the Propagation of Stock Market Shocks*

📄 Paper (IEEE Access): https://doi.org/10.1109/ACCESS.2024.3487766

---

## 📌 Overview

This project proposes a deep learning framework to study how financial shocks spread across companies in the S&P 500.

The approach integrates:

- Granger causality for constructing directed financial networks  
- Temporal Graph Convolutional Networks (TGCN) for modeling dynamic relationships  
- Network analysis to capture structural changes during shock periods  

The model enables:

- Identification of key propagating companies  
- Analysis of sector-level sensitivity to shocks  
- Comparison of different market crises (2008, 2016, COVID-19)  

Experiments are conducted on daily stock price data, using log-returns and multiple detected shock periods to evaluate the evolution of market interdependencies.

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
