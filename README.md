# Advanced Control-Oriented Modeling of Lithium-Ion Battery Systems Using Machine Learning

This repository presents a suite of machine learning-based modeling techniques for predicting terminal voltage in lithium-ion batteries. These models are developed as part of an independent research initiative aligned with the goal of improving Battery Management Systems (BMS) for electric vehicles (EVs) and renewable energy storage systems (ESS).

If you're interested in **collaborating on future research projects**, including experimental validation, hybrid modeling, or AI-based battery control, please feel free to reach out.  
**Contact:** Suyash Jadhav | **Email:** suyash7.j@gmail.com | **GitHub:** [github.com/Suyash7j](https://github.com/Suyash7j)

---

## Overview

This repository contributes to the proposed endeavor of developing control and modeling algorithms that improve the safety, efficiency, and reliability of advanced battery systems. The models and tools developed herein are intended for public dissemination and reproducible research.

They support key national objectives in energy resilience, clean transportation, and smart grid technologies.

---

## Key Contributions

### Ongoing Work

- Development and validation of a hybrid model combining Thevenin equivalent circuits with NARX neural networks for dynamic voltage prediction
- Benchmarking of LSTM-NARX and Deep Koopman operator models for transient and steady-state voltage behavior
- Closed-loop forecasting and model evaluation using normalized RMSE and MAE metrics on Stanford/NASA datasets
- Preparation of peer-reviewed publication submitted to *Batteries (MDPI)*

### Planned Contributions

- Incorporation of temperature and aging effects into voltage prediction using the Stanford cycler dataset
- Application of transfer learning techniques across lithium-ion chemistries (LFP, NCM, LCO) to improve model generalizability
- Design of reinforcement learning-based control strategies for health-aware charging
- Integration of physics-informed constraints into ML training for safe, real-time battery operation
- Modeling of recycled/second-life batteries with power derating estimation for extended lifecycle applications
- Modularization of model training pipelines into structured Python scripts under `/src/`

---

## Repository Structure

| Folder        | Description |
|---------------|-------------|
| `notebooks/`  | Jupyter notebooks for each model with demo runs |
| `data/`       | Dataset source links and preprocessing details |
| `src/`        | Modular source code for future refactoring (in progress) |
| `results/`    | Evaluation plots, predicted vs actual outputs |
| `docs/`       | Research summary, NIW statement, and technical notes |
| `configs/`    | Training configurations for reproducibility |
| `tests/`      | Planned unit testing and reproducibility checks |

---

## Reproducibility

Install required libraries:
```bash
pip install -r requirements.txt
