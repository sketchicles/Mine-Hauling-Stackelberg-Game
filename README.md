# Smart Mining Decision Support System (DSS)

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://wushanshan.github.io/smartmining-dss)

## 📋 Overview

An interactive visualization platform for optimizing open-pit mining haulage operations using **Stackelberg Game Theory**. This project serves as a conceptual framework for an MBA thesis demonstrating how bi-level optimization can resolve conflicts between mine dispatch centers and haulage fleets.

**🔗 Live Demo:** [View on GitHub Pages](https://sketchicles.github.io/Mine-Hauling-Stackelberg-Game/)

## 🎯 Problem Statement

Open-pit mining operations face a critical challenge in truck-shovel allocation:
- **Dispatch Center** aims to maximize production and grade adherence
- **Haulage Fleet** (often outsourced) aims to minimize fuel consumption and operational costs

Traditional heuristic methods fail to find global optima, leading to excessive queue times and suboptimal fuel usage. This DSS proposes a quantitative framework to resolve this bi-level decision-making process.

## ✨ Features

- **Interactive Bird's-Eye Visualization**: Real-time simulation of fleet movements around the pit
- **Dynamic Parameter Controls**: Adjust fleet size, ore value, and fuel costs via sliders
- **Real-Time KPI Dashboard**: 
  - Fleet Efficiency (%)
  - Cost per Ton ($)
  - Projected NPV (5-year proxy)
- **Sensitivity Analysis**: Test economic viability under varying operational constraints

## 🛠️ Methodology

1. **Data Acquisition**: Real-time telemetry (GPS, fuel sensors) and geological block models
2. **Bi-Level Formulation**: Upper Level (Maximize Production) + Lower Level (Minimize Cost)
3. **Solution Algorithm**: Hybrid Genetic Algorithm (GA) + Linear Programming
4. **Simulation & Validation**: Discrete-event simulation (Python SimPy)
5. **Sensitivity Analysis**: Robustness testing against fuel prices and fleet availability

## 💻 Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Visualization**: HTML5 Canvas API
- **Backend (Planned)**: Python (NumPy, Pandas, Streamlit)
- **Deployment**: GitHub Pages

##  Usage

1. **Adjust Operational Parameters**:
   - Fleet Size (5-25 trucks)
   - Ore Value ($10-100/ton)
   - Fuel Cost ($0.80-2.50/liter)

2. **Observe Real-Time Updates**:
   - Watch truck movements in the Bird's-Eye view
   - Monitor KPI changes in the dashboard
   - Analyze economic impact via NPV calculations

3. **Conduct Sensitivity Analysis**:
   - Test different fuel price scenarios
   - Evaluate optimal fleet sizing
   - Assess profitability thresholds
  
## 📄 License

This project is licensed under the MIT License

## 🤝 Acknowledgments

- Dr. Zhao Chuan for academic guidance and mentorship
- Beijing Technology and Business University for research support
- Open-source community for visualization libraries and tools

## 📧 Contact

For questions or collaboration opportunities, please open an issue in this repository.
