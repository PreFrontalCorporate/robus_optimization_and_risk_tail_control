# 🎯 URDCEAT: Unified Robust Duality-Informed Convex Equilibrium Allocation Theory

Welcome to the reproducibility package for the Unified Robust Duality-Informed Convex Equilibrium Allocation Theory (URDCEAT). This repository contains code, proofs, and data to replicate all key numerical results presented in the associated papers and slides.

---

## 🚀 Overview

This framework demonstrates a **nested Conditional Value-at-Risk (CVaR)** formulation for robust convex equilibrium allocation. It uses advanced duality-based techniques to control extreme tail risk in portfolio allocations.

---

## ⚙️ Environment Setup

### ✅ Requirements

- **Python** ≥ 3.8 (tested on 3.11)
- **Libraries**:
  - `cvxpy >= 1.3`
  - `numpy >= 1.23`
  - Solver: `GUROBI` (preferred), or fallback options: `ECOS`, `OSQP`, `SCS`

### 💻 Installation

```bash
pip install cvxpy numpy
