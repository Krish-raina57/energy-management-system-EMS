# Energy Management System using Stacking Ensemble & Genetic Algorithm

**Shri Mata Vaishno Devi University — 6th Semester Mini Project**
**By: Krish Raina, Vikrant Mohan, Lakshaya Jandial**
**Guide: Dr. Manoj Kumar Gupta**

---

## Overview
This project presents an intelligent Energy Management System (EMS)
that combines Stacking Ensemble Learning with Genetic Algorithm (GA)
optimization to manage PV solar generation, battery storage, and
grid interaction.

**Baseline Paper:** Showole & Afaqui (2026) — *Optimization of
renewable energy management using machine learning and genetic
algorithms*, Energy Storage and Saving.

---

## Results vs Baseline Paper

| Metric | Paper | Ours |
|---|---|---|
| Grid Dependency Reduction | 39.29% | 54.17% |
| Energy Cost Reduction | 35.14% | 72.96% |

---

## Our Contributions Beyond the Paper
- Stacking Ensemble (RF + XGBoost → meta-learner) for PV forecasting
- Stacking Ensemble (LR + DT + GB) for demand forecasting
- Continuous GA chromosome encoding (vs discrete in paper)
- Multi-objective fitness function
- Battery sensitivity analysis
- Gradio web interface for real-time monitoring

---

## Project Structure
