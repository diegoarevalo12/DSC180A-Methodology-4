---
layout: page
title: Home
---

# Methodology Assignment 4 — Task 2

**Name & Email**  
Diego Arevalo-Fernandez — darevalofernandez@ucsd.edu

**Section & Mentor**  
Section: _[fill in]_  
Mentor: _[fill in]_

---

**What is the most interesting topic covered in your domain this quarter?**  
I’m most interested in **spatiotemporal wildfire risk modeling**—specifically how climate signals (PRISM), vegetation dynamics (MODIS NDVI), land cover (NLCD), and topography combine to shape ignition and spread risk at ~800 m resolution.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
Build a **monthly wildfire occurrence forecaster** for San Diego County that outputs calibrated probabilities per 800 m grid cell. I’d compare baselines (regularized logistic regression, GAM) to tree ensembles (XGBoost, LightGBM) and a spatial model. I’d emphasize **spatial cross-validation**, lagged features (e.g., 1–3 month NDVI/VPD lags), and **model interpretability (SHAP)**.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Improve **evaluation and calibration**: move from random CV to **spatial block CV**, address **class imbalance** with focal loss/threshold tuning, and add **conformal prediction** or Platt/Isotonic calibration so probabilities are well-calibrated across space and time.

**What other techniques would you be interested in using in your project?**  
- **GAMs** for smooth, interpretable effects; **gradient boosting** for nonlinear interactions  
- **Conformal prediction** for uncertainty bands on risk maps  
- **HDBSCAN/BERTopic** to cluster fire events by conditions or seasonality  
- **Partial dependence/accumulated local effects** and **SHAP** for interpretability  
- **Time-aware feature engineering** (rolling stats, lags) and **geospatial CV**
