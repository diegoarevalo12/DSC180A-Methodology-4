---
layout: page
title: Home
---

# Methodology Assignment 4 — Task 2

**Name & Email**  
Diego Arevalo Fernandez — darevalofernandez@ucsd.edu

**Section & Mentor**  
Section: B13: Wildfire and Property Intelligence Modeling with Cotality  
Mentor: Ilyes Meftah

---

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic has been spatiotemporal wildfire prediction using publicly available environmental data.  I’ve learned how climate, vegetation, and topographic variables—such as PRISM temperature and precipitation, MODIS NDVI, NLCD land cover, and USGS elevation—interact to drive ignition risk and burn severity.  I find the idea of combining these heterogeneous geospatial layers into a single predictive model fascinating because it blends environmental science, remote sensing, and machine learning into one reproducible pipeline.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, I would like to build an early-season wildfire risk forecasting tool for San Diego County.  Using the same gridded datasets from Quarter 1, I’d extend the model to predict not only where fires occur but also when conditions become most conducive to ignition and spread.  The goal would be to integrate temporal features (e.g., lagged NDVI or VPD) and ensemble models (Random Forest, XGBoost, and GAMs) to produce a monthly burn-probability map.  The final output could be an interactive web dashboard displaying real-time predicted risk and historical validation metrics.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
In Quarter 1 we focused mainly on static classification within burn perimeters.  A key improvement would be to incorporate temporal dynamics and calibration.  Rather than treating each burn scar independently, I’d implement spatial-temporal cross-validation and include lag features to capture pre-fire environmental trends.  Additionally, I’d enhance interpretability and uncertainty estimation using SHAP values and conformal prediction so that our probability maps communicate model confidence as well as accuracy.

**What other techniques would you be interested in using in your project?**  
- GAMs for smooth, interpretable effects; gradient boosting for nonlinear interactions  
- Conformal prediction for uncertainty bands on risk maps  
- HDBSCAN/BERTopic to cluster fire events by conditions or seasonality  
- Partial dependence/accumulated local effects** and SHAP for interpretability  
- Time-aware feature engineering (rolling stats, lags) and geospatial CV
