# TGCN: Stock Market Shock Propagation

Official implementation of a Temporal Graph Convolutional Network (TGCN) for analyzing stock market shock propagation.

📄 Paper: https://doi.org/10.1109/ACCESS.2024.3487766

---

## Overview

- Granger causality → build financial networks  
- TGCN → model temporal + graph dependencies  
- Analyze shock propagation across S&P 500  

---

## Pipeline

1. Data collection  
2. Returns + shock periods  
3. Granger causality  
4. Adjacency matrices  
5. TGCN model  
6. Analysis  

---

## Project Structure

notebooks/
├── 01_get_stock_prices.ipynb
├── 02_returns_and_shocks.ipynb
├── 03_granger_causality.ipynb
├── 04_adjacency_matrix.ipynb
├── 05_tgcn_model.ipynb
└── 06_interpretation.ipynb

---

## Requirements

```bash
pip install -r requirements.txt