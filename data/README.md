# 📂 Battery Dataset Information

This repository uses publicly available datasets from academic and government sources to train and validate voltage prediction models for lithium-ion batteries.

## 📊 Datasets Used

### 🔹 Stanford EV Battery Dataset
- **Link**: [Stanford Battery Data GitHub](https://github.com/walidl/BatteryData)
- Includes: HPPC, constant current, drive cycle profiles
- Applications: Aging, thermal variation, and degradation analysis

### 🔹 NASA Prognostics Battery Dataset
- **Link**: [NASA PCoE Dataset Portal](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)
- Includes: Experimental cycles with current-voltage-time profiles
- Applications: RUL prediction, battery fault diagnosis

### 🔹 University of Maryland (CALCE) Battery Dataset
- **Link**: [UMD CALCE Dataset](http://www.calce.umd.edu/battery-data/)
- Includes: Li-ion batteries tested under different environmental and load conditions
- Applications: Degradation modeling, thermal impact analysis

⚠️ **Disclaimer**: The datasets listed above are publicly available from their respective institutions. This repository does **not redistribute** any proprietary or copyrighted data.  
Users are responsible for downloading and using them in accordance with the original licensing terms.

---

## 📁 Data Format (Expected)

For model training and testing, each dataset is expected to contain:
- `Time [s]`
- `Current [A]`
- `Voltage [V]`
- `Temperature [°C]` (if available)
- `Cycle number` or index (optional)

---

## 🧼 Preprocessing

Preprocessing scripts and conversion utilities will be added under the `/src/` directory. These will:
- Clean and normalize input variables
- Handle resampling and cycle segmentation
- Support training/validation/test splits

---

## ✅ Use in Research

These datasets enable:
- Accurate voltage prediction across aging and temperature regimes
- Benchmarking closed-loop forecasting under real-world conditions
- Comparative testing of hybrid, RNN, and physics-informed models
