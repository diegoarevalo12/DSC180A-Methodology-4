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
The most interesting topic has been looking into spatial and temporal wildfire predictions using publicly available environmental data.  I'm currently learning how climate, vegetation, and topographic variables such as temperature, precipitation, land cover, and elevation interact to drive ignition risk and burn severity.  I find the idea of combining these heterogeneous geospatial layers into a single predictive model interesting because it it consists of looking into a diverse array of domain all at once including environmental science, remote sensing, and machine learning, thus turning them into one reproducible pipeline.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, a potential investigation I would like to consider consists of an early-season wildfire risk forecasting tool for San Diego County.  Using the same gridded datasets from Quarter 1, I’d extend the model to predict not only where fires occur but also when conditions become most conducive to ignition and spread.  The goal would be to integrate temporal features (e.g., lagged NDVI or VPD) and ensemble models (Random Forest, XGBoost, and GAMs) to produce a monthly burn-probability map.  The final output could be an interactive web dashboard displaying real-time predicted risk and historical validation metrics.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
A potential change I would like to make is to emphazie time-based data and relationships between fire severety and its relevant predictors. In Quarter 1 we focused mainly on static classification within burn perimeters. A key improvement would be to incorporate temporal dynamics and calibration.  Rather than treating each burn scar independently, I could look into implementing spatial and temporal cross-validation and include lag features to capture pre-fire environmental trends and conditions.  Additionally, I’d enhance interpretability and uncertainty estimation using SHAP values and conformal prediction so that our probability maps can effectively communicate model confidence as well as accuracy.

**What other techniques would you be interested in using in your project?**  
- GAMs for smooth, interpretable effects; gradient boosting for nonlinear interactions  
- Conformal prediction for uncertainty bands on risk maps  
- HDBSCAN/BERTopic to cluster fire events by conditions or seasonality (I have previous experience with these algorithms from projects/internships, therefore it would be interesting to extrapolate them to a very different context.)
- Partial dependence/accumulated local effects and SHAP for interpretability  
- Timestamped feature engineering and geospatial cross-validation
