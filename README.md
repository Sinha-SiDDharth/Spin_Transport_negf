# Spin Transport Simulations using NEGF

This repository contains Jupyter notebooks implementing basic spin transport simulations using the Non-Equilibrium Green's Function (NEGF) formalism. These simulations are adapted from the models presented in Chapter 23 of Supriyo Datta's book *Lessons from Nanoelectronics: Part B – Quantum Transport*.

---

## Contents

### `1_ordinarySpinVALVES.ipynb`
Simulates a simple spin valve with spin-polarized ferromagnetic contacts connected to a single-level non-magnetic channel.

- Ferromagnets modeled via spin-dependent outflow rates: α > β
- Current shows dependence on the relative magnetization angle
- Computes spin-resolved transmission and current
- Extracts the normalized spin signal as a function of contact angle

### `2_NonLocalMeasurement.ipynb`
Simulates a four-terminal non-local spin valve geometry using NEGF.

- A voltage probe is introduced at the center of the channel
- The voltage sensed by the probe depends on the free magnet’s angle
- Computes how the spin-dependent electrochemical potential varies
- Demonstrates non-local spin signal detection via NEGF formalism

---

## Requirements

These notebooks require:

- Python 3.10+
- `numpy`
- `scipy`
- `matplotlib`
- `jupyter`

To run:
```bash
jupyter notebook
```

---

## Reference

- Supriyo Datta, *Lessons from Nanoelectronics: Part B – Quantum Transport*, World Scientific, Chapter 23.
- Numerical implementation inspired by the MATLAB codes from the book.

---

## 👨‍🔬 Author

Siddharth Sinha  
B.Tech Engineering Physics  
NEGF Simulations for Spin Transport · 2025  
