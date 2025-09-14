# 🏭 Soft Sensor for Sulphur Recovery Unit (SRU)  

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)  
[![MATLAB](https://img.shields.io/badge/MATLAB-R2020a-orange.svg)](https://www.mathworks.com/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

This repository implements **soft sensor models** for a **Sulphur Recovery Unit (SRU)** in refinery plants, inspired by the paper:  

> *Echo-state networks for soft sensor design in an SRU process*, L. Patanè & M.G. Xibilia, *Information Sciences, 2021*  

Soft sensors allow accurate **real-time estimation** of process variables (e.g., H₂S and SO₂ concentrations) when physical analyzers are unavailable due to maintenance or cost constraints.  

---

## 🚀 Project Overview  

- **Objective**:  
  Build and compare **machine learning soft sensors** for predicting acid gas concentrations in SRU tail gas.  

- **Approach**:  
  - Applied **Echo State Networks (ESN)** with and without **Intrinsic Plasticity (IP)**.  
  - Benchmarked against **Long Short-Term Memory (LSTM)** networks.  
  - Evaluated prediction accuracy, peak detection, stoichiometric proportion, and computational efficiency.  

- **Industrial Motivation**:  
  SRUs are critical for pollution control in refineries. Online analyzers often suffer downtime, and soft sensors provide redundancy and fault detection for continuous monitoring.  

---

## 🛠️ Techniques & Tools  

- **Algorithms**:  
  - Echo State Networks (ESN)  
  - ESN with Intrinsic Plasticity (ESN-IP)  
  - LSTM (single, stacked, and bidirectional)  

- **Metrics**:  
  - Normalized Root Mean Square Error (NRMSE)  
  - Correlation Coefficient (R)  
  - Peak detection accuracy  
  - Stoichiometric ratio: [H₂S] – 2[SO₂]  

- **Tools**:  
  - MATLAB R2020a (training & evaluation)  
  - Python (optional extensions)  
  - Data preprocessing with Z-score normalization, outlier detection, interpolation  

 

