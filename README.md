# 📡 Interference Evaluation in 5G Networks using NETSIM

This project investigates how different types of interference affect 5G network performance using the NETSIM simulator. It simulates real-world interference conditions — including co-channel, adjacent-channel, and intra/inter-cell interference — to measure degradation in throughput, latency, SINR, and packet delivery.

---

## 📑 Project Overview

### 🧠 Problem Statement
With increasing demand for ultra-reliable, high-speed mobile networks, 5G performance is heavily impacted by various forms of interference. This project evaluates the effect of:
- Co-Channel Interference (CCI)
- Adjacent Channel Interference (ACI)
- Inter-cell and intra-cell interference
- Beamforming-related signal overlaps

### 🎯 Objective
To simulate and evaluate how interference affects:
- Throughput  
- Latency  
- Packet Loss  
- Signal-to-Interference-plus-Noise Ratio (SINR)  

---

## ⚙️ Simulation Tool: NETSIM

NETSIM is a professional simulation software that models the behavior of network protocols and topologies. This project uses its 5G NR module to:
- Simulate high-density 5G networks
- Apply different interference types
- Measure key performance metrics under each condition

### 🔍 Key Features Used
- Drag-and-drop network design
- Beamforming and massive MIMO configuration
- SINR analysis and packet tracing
- Support for IoT/mMTC/URLLC simulations

---

## 📁 Repository Structure

```
5g-interference-evaluation/
├── report/
│   └── 5G_PBL_Report.pdf
├── README.md
```

---

## 📈 Key Observations

- Interference significantly lowers SINR, increasing packet loss and delay.
- mmWave frequencies suffer most in high-density scenarios.
- Beamforming helps but can create directional overlap without tuning.
- Smart small cell placement and spectrum reuse are critical.

---

## 🧑‍💻 Authors

- **Anshuman**

👨‍🏫 *Under the guidance of:*  
**Prof. (Dr.) Arundhati A. Shinde** — HOD
**Prof. (Dr.) Dhiraj M. Dhane** — Project Coordinator

---

## 📚 References

- [Tetcos NetSim 5G Module](https://www.tetcos.com/downloads/v14.1/5G-NR.pdf)
- [DiVA Portal Thesis on 5G Interference](https://www.diva-portal.org/smash/get/diva2:1827313/FULLTEXT01.pdf)
