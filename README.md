# Superstar-Driven Running Mode: Optimization, Pricing & Hedging

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Optimization: PuLP](https://img.shields.io/badge/Optimization-PuLP-brightgreen)](https://coin-or.github.io/pulp/)

This repository contains the official source code and data processing pipeline accompanying the manuscript:  
**"Superstar-driven running mode: A Multi-objective Framework for Roster Optimization, Dynamic Pricing, and Risk Management in Professional Sports"**

The framework implements a unified, three-stage quantitative pipeline utilizing Operations Research (MOMILP), Econometrics (Tobit & 2SLS), and Financial Engineering (Monte Carlo & CVaR) to address the complex couplings in modern professional sports management under hard salary caps.

---

## 📁 Repository Structure

```text
├── main_framework.py          # Core computational pipeline (Algorithms I, II, & III)
├── merged_result.xlsx         # Empirical player performance, usage, & contract dataset
├── 2023年上座.xlsx / ...      # Historical attendance datasets (2023-2024)
├── 2023年门票.xlsx / ...      # Historical ticket pricing datasets
├── 主场门票/                   # Directory containing secondary market transaction panels (CSVs)
├── Paper_Figures/             # Auto-generated directory for all visual outputs (PDF/SVG/PNG)
└── README.md                  # Academic documentation and execution guide
