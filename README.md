# 🚀 Unified Robust Duality-Informed Convex Equilibrium Allocation Theory

A reproducible framework for robust convex risk and allocation modeling using CVaR, nested CVaR, and distributional robustness.

---

## 🌟 Overview

This repository provides an end-to-end environment to:

* ✅ Implement and test robust portfolio allocation under CVaR and nested CVaR constraints.
* 🔎 Analyze dual variable economic interpretations.
* ⚖️ Run sensitivity and stress tests for practical risk management.

---

## 💻 Installation

```bash
pip install cvxpy numpy
```

> 💡 **Note:** For Gurobi users, make sure your license file is properly configured. See the [Gurobi Installation Guide](https://www.gurobi.com/documentation/).

---

## 🧬 Data Generation

Loss scenarios are simulated using a Gaussian distribution:

* **Mean:** `3.0`
* **Standard Deviation:** `1.0`
* **Assets:** `2`
* **Scenarios:** `1000`

Fixed random seed `42` to ensure reproducibility.

---

## ⚙️ Running the Code

Clone the repository and run:

```bash
python URDCEAT.py
```

**Outputs include:**

* Portfolio allocation vector `x`
* Inner CVaR parameter `eta_alpha`
* Outer nested CVaR parameter `eta_gamma`
* Dual economic interpretation values
* Stress test and sensitivity analysis results

---

## 📊 Results & Interpretation

* Empirical tail verification (VaR and CVaR).
* Perturbation and convexity checks.
* Stress scenario analysis for extreme market events.
* Economic interpretations of dual variables.

---

## 💬 Contact

Santiago de Jesus Villalobos-Gonzalez
✉️ [prefrontalcorporate@gmail.com](mailto:prefrontalcorporate@gmail.com)
📞 +1 (510) 298-8218

---

## 🤝 Contribute

Pull requests are welcome. For major changes, open an issue first to discuss your proposed modifications.

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for details.
