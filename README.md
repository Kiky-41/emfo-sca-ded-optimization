# 🚀 Initial Release – EMFO-SCA for Dynamic Economic Dispatch
[![DOI](https://zenodo.org/badge/1205001889.svg)](https://doi.org/10.5281/zenodo.19472613)

This release presents the implementation of a hybrid optimization method:
**Electromagnetic Field Optimization with Sine-Cosine Algorithm (EMFO-SCA)**
for solving the **Dynamic Economic Dispatch (DED)** problem.

---

## 📄 Related Publication

Ikhsan, R.R.N., Marsuki, A.I., Wijaya, I.G.P.O (2025)
*Reducing Operational Costs in Sulselbar's 150 kV System with Electromagnetic Field and Sine-Cosine Optimization*
Journal on Advanced Research in Electrical Engineering (JAREE)
🔗 DOI: https://doi.org/10.12962/jaree.v9i1.458

---

## ⚡ Key Features

- Hybrid metaheuristic optimization (EMFO + SCA)
- Handles **non-linear cost functions**
- Supports **dynamic 24-hour load scheduling**
- Enforces:
  - Power balance constraint
  - Generator limits
  - Ramp rate constraints
- Fast convergence and robust performance

---

## 📊 Performance Highlights

- Achieves **0.27% operational cost reduction** compared to KKA
- Ensures:
  - ✅ Zero power mismatch
  - ✅ No ramp rate violations
  - ✅ Full constraint satisfaction
- Suitable for real-world power system applications

---

## 🧠 Method Overview

The algorithm consists of two main phases:

### 🔹 EMFO (Exploration)

- Attraction–repulsion mechanism
- Strong global search capability
- Avoids local optima

### 🔹 SCA (Exploitation)

- Sine-cosine oscillatory update
- Fine-tuning near optimal solution
- Improves convergence accuracy

---

## 🏗️ Problem Formulation

**Objective:** Minimize total fuel cost:

$$F(P) = \sum_{i=1}^{n} (a_i P_i^2 + b_i P_i + c_i)$$

**Subject to:**
- Power balance constraint
- Generator limits
- Ramp rate constraints

---

## 📁 Repository Contents

```text
EMFO-SCA/
├── EMFO-SCA.ipynb      # Main implementation
├── dataset/            # Sulselbar 150 kV system data
├── results/            # Results & analysis
└── README.md
```

---

## 🎯 Use Cases

- Economic Dispatch (ED)
- Dynamic Economic Dispatch (DED)
- Power system optimization
- Metaheuristic benchmarking

---

## 🔖 Version

`v1.0.0` — Initial release based on published research.

---

## 📌 Notes

This repository is intended for:
- Research reproduction
- Academic reference
- Algorithm development

---

## 📬 Citation

If you use this work, please cite:

```bibtex
@article{ikhsan2025emfosca,
  title={Reducing Operational Costs in Sulselbar's 150 kV System with Electromagnetic Field and Sine-Cosine Optimization},
  author={Ikhsan, R.R.N. and Marsuki, A.I. and Wijaya, I.G.P.O},
  journal={Journal on Advanced Research in Electrical Engineering},
  year={2025},
  doi={10.12962/jaree.v9i1.458}
}
```
