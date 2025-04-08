# FAULT-DETECTION-IN-TENNESSEE-EASTMAN-PROCESS-USING-KERNEL-PRINCIPAL-COMPONENT-ANALYSIS


This project presents a machine learning-based framework for fault detection and diagnosis (FDD) in industrial chemical processes using the **Tennessee Eastman Process (TEP)** as a benchmark. It leverages **Kernel Principal Component Analysis (kPCA)** to handle the high dimensionality and nonlinear relationships inherent in industrial process data, aiming for more effective and reliable fault detection.

---

## 📌 Overview

Industrial processes, especially in the chemical sector, are prone to complex and sometimes catastrophic failures due to human error, equipment malfunction, and process disturbances. This project builds on the motivation to prevent such incidents—like the **Bhopal Gas Tragedy** and **Fukushima Nuclear Disaster**—by developing robust FDD systems.

The TEP is chosen due to its complexity and realism, making it a standard benchmark in academia and industry for testing control and monitoring systems.

---

## ⚙️ Key Features

- Simulation of **fault scenarios** in the Tennessee Eastman Process
- Use of **Kernel PCA (kPCA)** for feature extraction and fault detection
- Calculation of:
  - **Q-Statistic** (Squared Prediction Error): Measures residual deviation
  - **T²-Statistic**: Measures variation within the principal component space
- **Comparison with standard PCA** to highlight the effectiveness of kernel methods in capturing nonlinear fault patterns

---

## 🏭 The Tennessee Eastman Process (TEP)

- Developed by Eastman Chemical Company (Downs & Vogel, 1993)
- Simulates a real-world chemical plant with:
  - 41 process variables (e.g., temperature, pressure, flow)
  - Multiple fault types (valve stiction, pump failure, etc.)
  - Operating conditions like start-up, shut-down, and steady-state
- Widely used for research in **statistical process monitoring**, **sensor validation**, and **data-driven modeling**

---

## 🧠 Methodology

1. **Data Collection & Preprocessing**
   - Simulated TEP data including fault and non-fault scenarios
   - Normalization and noise handling

2. **Feature Extraction**
   - Apply **Kernel PCA** to extract nonlinear components
   - Compare with traditional **PCA** for baseline evaluation

3. **Fault Detection**
   - Calculate **Q-statistic** for reconstruction error
   - Calculate **T²-statistic** for variation within feature space
   - Set thresholds to detect anomalies

4. **Analysis & Visualization**
   - Plot detection statistics over time
   - Evaluate accuracy and robustness against known fault labels

---

## 🧰 Tools & Libraries

- MATLAB
- Simulation
- ML AND DL
- Matplotlib & Seaborn
- Jupyter Notebooks
- Dimensionality Reduction

---

## 📈 Results

- **kPCA** significantly outperformed PCA in detecting nonlinear fault patterns.
- Effective in distinguishing between normal and faulty operations under noisy and high-dimensional conditions.
- Demonstrated high sensitivity and reliability in identifying anomalies early.

---


