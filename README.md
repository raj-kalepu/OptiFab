# OptiFab
Optimizing 3D Printing Parameters Using Machine Learning
This project investigates the relationship between 3D printing process parameters and the mechanical properties of printed parts, focusing on tensile strength. Using a dataset generated from physical experiments, we apply machine learning to model, analyze, and optimize parameter combinations.

# Project Overview
Experimental data collected from 3D printed specimens tested for tensile strength.

Dataset includes key printing parameters like layer height, infill percentage, raster angle, and others.

Machine Learning (ML) pipeline using Support Vector Regression (SVR) with Leave-One-Out Cross-Validation (LOOCV) to predict mechanical performance.

Feature engineering includes Signal-to-Noise Ratio (SNR) and parameter interaction terms.

Analytical techniques like Grey Relational Analysis (GRA) and DEAR (Efficiency Ranking) to identify and rank influential parameters.

# Key Techniques Used
Machine Learning: SVR with hyperparameter tuning (GridSearchCV).

Cross-Validation: LOOCV for robust prediction validation.

Feature Engineering: Custom metrics like SNR and combined features.

Parameter Analysis: GRA and DEAR for understanding parameter influence.

# Outputs
Predictive models with performance metrics (MAE, MSE, R²).

Visual comparisons of actual vs. predicted tensile strength.

Parameter rankings for better print performance optimization.
