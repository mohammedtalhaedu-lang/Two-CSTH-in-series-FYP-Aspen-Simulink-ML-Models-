# Two-CSTH-in-series-FYP-Aspen-Simulink-ML-Models- 

https://mohammedfyp.netlify.app 

# Modeling and Simulation of Hierarchical Control of Two Continuous Stirred Tank Heaters in Series 

**BEng (Hons) Petroleum Engineering Final Year Project Poster**   
**Asia Pacific University of Technology & Innovation (APU)** — School of Engineering (August 2026)

---

## Project Overview
This repository contains the interactive, responsive A2 academic poster web application for the Final Year Project: **"Modeling and Simulation of Hierarchical Control of Two Continuous Stirred Tank Heaters in Series"**.

- **Student:** Mohammed (TP061730 | APD4F2511PE)
- **Supervisor:** Ts. Dr. Muhammad Syahmi Afif Bin Mokhtar Yazid
- **Institution:** Asia Pacific University of Technology & Innovation (APU)
- **Degree:** BEng (Hons) Petroleum Engineering

---

## Technical Highlights & Results Summary
- **First-Principles & Steady-State Validation:** Non-linear ODE modeling for 2-CSTH with 20% hydraulic recycle loop validated in **Aspen HYSYS V14** ($T_1 = 59.97^\circ\text{C}$, $T_2 = 69.56^\circ\text{C}$, $h_1 = 1.301\text{ m}$).
- **Internal Model Control (IMC):** Achieves **75% faster settling time** ($16\text{ s}$ vs. $64\text{ s}$) and **30% reduction in IAE** compared to conventional multi-loop PID with zero overshoot on $T_1$.
- **Machine Learning Digital Twins:** **Random Forest** and **XGBoost** surrogate models achieve near-perfect virtual sensing accuracy ($R^2 > 0.9999$, $\text{RMSE} < 0.01^\circ\text{C}$) on dynamic time-series data.
- **NARX Neural Networks:** Trained via Bayesian regularization ($\text{MSE} = 8.30 \times 10^{-12}$).

---

## Repository Structure


├── index.html        # Main HTML poster document (Semantic HTML5, fully responsive)
├── poster.css        # Print-ready A2 stylesheet with CSS Grid, Flexbox, & Mobile Breakpoints
├── images/           # All high-resolution diagram & result chart assets
│   ├── APU_Logo.jpg
│   ├── SDG.png
│   ├── AspenModel.png
│   ├── CSTH_tanks_subsystems.PNG
│   ├── Model Performance Comparison for T2 Temperature.png
│   ├── Dynamic Performance and Tracking Comparison for T2 Temperature.png
│   ├── PID_T_Scope_spstep.PNG
│   ├── IMC_T_Scope_spstep.PNG
│   ├── [IMC] Dynamic Response of T2 Temperature under Step Changes...png
│   ├── IMC_ANN_Training_progress.PNG
│   └── PID_ANN_Training_progress.PNG
└── README.md         # Project documentation and deployment guide
```
