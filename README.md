# ML_Battery_Models

This repository contains machine learning-based dynamic modeling techniques for lithium-ion batteries, developed as part of an independent research initiative aligned with the proposed endeavor of advancing battery control and diagnostics systems for electric vehicles (EVs) and energy storage systems (ESS). The models here integrate physical insight (e.g., Thevenin equivalent circuits) with data-driven architectures such as NARX, LSTM, Koopman operators, and graph neural networks.

These efforts support the U.S. national goals in electrification, grid modernization, and energy resilience through the development of safer, more reliable, and more efficient Battery Management Systems (BMS).

---

## 📌 Key Contributions

- 🔁 NARX + Thevenin hybrid models for nonlinear system identification  
- 🔄 Closed-loop voltage forecasting using LSTM and NARX  
- 🔬 Deep Koopman operator models for latent dynamical structure  
- 🌐 Graph Neural Networks for battery pack-level voltage prediction  
- 📖 Emphasis on reproducibility, transparency, and public access  

---

## 📂 Repository Structure

| Folder        | Description |
|---------------|-------------|
| `notebooks/`  | Jupyter notebooks demonstrating all ML models |
| `data/`       | Dataset links and format expectations |
| `src/`        | Source code for modular components (planned) |
| `results/`    | Prediction results, plots, and metrics |
| `docs/`       | Research goals, NIW statement, and methods |
| `configs/`    | Configuration templates for experiments |
| `experiments/`| Planned experiment logs or JSON trackers |
| `tests/`      | Placeholder for validation/unit tests |

---

## 🧠 Research Context

This repository supports the author’s proposed endeavor and future plan to:
- Improve BMS modeling accuracy using ML and hybrid approaches
- Combine physics-based modeling (Thevenin) with learning-based estimators (NARX)
- Build reusable models for EVs and grid-based battery systems
- Support sustainable deployment through open science

---

## 🌐 Open Science and Reuse

This repository is open-source under the MIT License and encourages reuse by the academic and engineering communities. If this work is helpful in your research, please cite the repo using the citation metadata or link to the associated paper (pending review).

📄 **Citation**: See [CITATION.cff](./CITATION.cff)  
📘 **License**: [MIT License](./LICENSE)

---

## 📊 Getting Started

```bash
pip install -r requirements.txt
