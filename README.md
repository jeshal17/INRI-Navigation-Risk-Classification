<div align="center">

# INRI — Navigation Risk Classification

### Identifying and assessing navigation failures using Machine Learning + Rule-Based Risk Analysis

</div>

<br>

## About

INRI is a machine learning and rule-based framework designed to classify navigation failures and assess their potential risk.

It combines machine learning models with domain-based safety rules to generate **RED, AMBER, and GREEN** risk alerts.

## 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-31543F?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-3F6B50?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-527A5D?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-6B8F71?style=for-the-badge&logo=python&logoColor=white"/>

</p>

## 📊 Model Results

<div align="center">

| Metric | Result |
|:---:|:---:|
| **Best Model** | KNN |
| **Accuracy** | 81.8% |
| **F1 Score** | 78.8% |
| **5-Fold CV** | 65.6% ± 8.8% |

</div>

## 📈 Visual Analysis

<div align="center">

### Severity & Incident Categories

<img src="https://raw.githubusercontent.com/jeshal17/INRI-Navigation-Risk-Classification/assets/fig1_severity_category.png" width="85%"/>

<br><br>

### State & Seasonal Distribution

<img src="https://raw.githubusercontent.com/jeshal17/INRI-Navigation-Risk-Classification/assets/fig2_state_season.png" width="85%"/>

<br><br>

### Model Comparison

<img src="https://raw.githubusercontent.com/jeshal17/INRI-Navigation-Risk-Classification/assets/fig3_model_comparison.png" width="85%"/>

<br><br>

### Feature Importance & Terrain Analysis

<img src="https://raw.githubusercontent.com/jeshal17/INRI-Navigation-Risk-Classification/assets/fig4_importance_heatmap.png" width="85%"/>

<br><br>

### Signal & Time Analysis

<img src="https://raw.githubusercontent.com/jeshal17/INRI-Navigation-Risk-Classification/assets/fig5_signal_time.png" width="85%"/>

</div>

## 🚦 Risk Framework

```text
Navigation Incident
        ↓
Feature Analysis
        ↓
Machine Learning
        ↓
INRI Risk Score
        ↓
Domain Safety Rules
        ↓
RED · AMBER · GREEN
