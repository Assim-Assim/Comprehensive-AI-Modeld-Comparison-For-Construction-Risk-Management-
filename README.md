# AI-Driven Construction Risk Management: Predictive Modeling for Project Delays

## 🚀 Research Overview
This repository contains the R-based implementation for a Master's thesis study titled **"AI Models for Construction Risk Management"**. The project aims to enhance decision-making in the construction industry by comparing three advanced Machine Learning architectures to predict project delays and classify risk categories.

## 🛠️ Methodology & Models
[span_0](start_span)The framework processes 120 construction projects[span_0](end_span) [span_1](start_span)using an 80/20 train-test split[span_1](end_span). Three models were rigorously evaluated:
1. **[span_2](start_span)Random Forest (RF):** Ensemble learning with 300 decision trees[span_2](end_span).
2. **[span_3](start_span)Support Vector Machine (SVM):** Radial Basis Function (RBF) kernel with optimized cost parameters[span_3](end_span).
3. **[span_4](start_span)Long Short-Term Memory (LSTM):** Deep learning architecture with 64 units and Adam optimizer[span_4](end_span).



## 📊 Key Findings

### 1. Delay Prediction (Regression)
- **[span_5](start_span)Top Performer:** Random Forest achieved the highest predictive accuracy with a Root Mean Square Error (RMSE) of 7.78 and Mean Absolute Error (MAE) of 3.66[span_5](end_span).
- **[span_6](start_span)Coefficient of Determination ($R^2$):** LSTM recorded the highest $R^2$ value at 0.185[span_6](end_span).

### 2. Risk Categorization (Classification)
- **[span_7](start_span)Accuracy:** Both Random Forest and SVM demonstrated robust performance with an accuracy of 70.83%[span_7](end_span).
- **[span_8](start_span)High-Risk Sensitivity:** LSTM and SVM showed exceptional capabilities in identifying "High" risk projects, each achieving an Area Under the Curve (AUC) of 0.977[span_8](end_span).

### 3. Feature Importance
Analysis identified the top three most influential construction risk factors:
1. **[span_9](start_span)Planned Budget** (Importance Score: 1196.04)[span_9](end_span).
2. **[span_10](start_span)Design Quality** (Importance Score: 903.88)[span_10](end_span).
3. **[span_11](start_span)Permit Procedures** (Importance Score: 731.67)[span_11](end_span).

## 📂 Repository Structure
- `Complete_Analysis_Script.R`: The core implementation script.
- `/Data_Files`: Contains performance metrics and prediction outputs (CSV).
- `/Visualizations`: High-resolution plots including Confusion Matrices and ROC curves.
- `/Saved_Models`: Pre-trained models in `.rds` and `.keras` formats.

## 💻 Requirements
- **[span_12](start_span)R Version:** 4.4.3 or higher[span_12](end_span).
- **Key Libraries:** `keras3`, `tensorflow`, `randomForest`, `e1071`, `pROC`, `ggplot2`.

## 📜 Citation & Research Integrity
This research maintains the highest standards of scientific integrity. All results are derived from real project data with strict separation between training and testing sets to prevent data leakage.

**Author:** [Your Name]  
**Institution:** [Your University]  
**[span_13](start_span)Date:** January 2026[span_13](end_span)
