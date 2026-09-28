# 🚴 Yulu Bike Rental Demand Analysis

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-purple) ![Statistics](https://img.shields.io/badge/Statistics-Hypothesis%20Testing-orange) ![EDA](https://img.shields.io/badge/EDA-Business%20Analytics-green) ![Status](https://img.shields.io/badge/Project-Completed-success)

## 📊 Project Overview

A **business analytics and statistical hypothesis-testing case study** focused on understanding factors influencing demand for shared electric cycles in the Indian market.

The project combines **Python, Pandas, exploratory data analysis and statistical testing** to investigate how working days, seasons, weather and environmental conditions relate to bike-rental demand.

**Data Understanding → Data Quality → EDA → Relationship Analysis → Hypothesis Testing → Business Interpretation**

## 🎯 Business Problem

Yulu wants to understand the factors affecting demand for its shared electric cycles.

The analysis is designed to answer:

1. Which variables significantly affect demand for shared electric cycles?
2. How well do these variables explain differences in rental demand?

The project moves beyond descriptive charts and uses statistical hypothesis tests to evaluate whether observed differences between groups are statistically significant.

## 📁 Dataset

The dataset contains **10,886 hourly observations** covering the 2011–2012 period.

| Field | Description |
|---|---|
| datetime | Date and time |
| season | Season category |
| holiday | Holiday indicator |
| workingday | Working-day indicator |
| weather | Weather category |
| temp | Temperature |
| atemp | Feeling temperature |
| humidity | Humidity |
| windspeed | Windspeed |
| casual | Casual-user rentals |
| registered | Registered-user rentals |
| count | Total rental count |

## 🔎 Exploratory Data Analysis

### Univariate Analysis

The analysis examines rental-demand distribution, seasonal distribution, weather distribution, working vs non-working days, temperature, humidity, windspeed and casual vs registered users.

### 📈 Bivariate Analysis

Demand is examined against **season, weather, working day, temperature, humidity and windspeed**. The objective is to identify patterns worth testing statistically rather than treating visual differences as proof.

## 🧪 Hypothesis Testing

A key objective is to move from **observed differences to statistically supported conclusions**.

### 1. Working Day vs Non-Working Day

**H₀:** Average rental demand is the same on working and non-working days.  
**H₁:** Average rental demand differs between working and non-working days.

A **two-sample t-test** is used.

### 2. Seasonal Demand

**H₀:** Average rental demand is the same across seasons.  
**H₁:** At least one season has a different average rental demand.

**ANOVA** is used to compare demand across multiple seasonal groups.

### 3. Weather and Demand

**H₀:** Average rental demand is the same across weather conditions.  
**H₁:** Rental demand differs across weather conditions.

A multi-group statistical test is used to evaluate differences across weather categories.

### 4. Weather × Season Relationship

The project examines whether weather conditions and seasons are statistically associated using a **Chi-square test of independence**.

**H₀:** Weather and season are independent.  
**H₁:** Weather and season are associated.

## 📊 Statistical Thinking

**Business Question → H₀ / H₁ → Variables & Groups → Test Selection → Test Statistic & p-value → Statistical Decision → Business Interpretation**

The focus is not simply on obtaining a p-value, but on translating statistical evidence into a meaningful business conclusion.

## 💡 Business Applications

### Fleet Availability
Understanding demand patterns can support better allocation of available bikes.

### Seasonal Planning
Seasonal demand analysis can support capacity and operational planning.

### Weather-Aware Operations
Weather conditions can be incorporated into demand planning and operational preparedness.

### Customer Analysis
Separating casual and registered users provides additional insight into demand behaviour.

### Demand Forecasting
The analytical dataset provides a foundation for future predictive modelling.

## 🧠 Skills Demonstrated

**Python:** Python • Pandas • NumPy • Matplotlib • Seaborn

**EDA:** Univariate analysis • Bivariate analysis • Distribution analysis • Outlier analysis • Correlation analysis

**Statistics:** Hypothesis formulation • Two-sample t-test • ANOVA • Chi-square • Significance testing • p-value interpretation

**Business Analytics:** Demand analysis • Seasonal analysis • Weather analysis • Customer behaviour • Operational planning

## ⚠️ Analytical Limitations

1. Statistical significance does not automatically establish causation.
2. Rental demand is influenced by multiple factors simultaneously.
3. The dataset represents a historical observation period and may not represent current Yulu demand.
4. Weather categories may hide variation within individual conditions.
5. Business decisions should combine statistical evidence with operational, financial and market information.

## 📂 Repository Structure

    yulu_business_case/
    ├── README.md
    ├── Analysis Notebook
    ├── Dataset

## 🛠️ Technology Stack

| Tool | Purpose |
|---|---|
| Python | Statistical analysis and EDA |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib | Visualisation |
| Seaborn | Statistical visualisation |
| SciPy / Statistics | Hypothesis testing |
| Jupyter / Google Colab | Analysis environment |
| GitHub | Version control and portfolio documentation |

## 👤 Author

**Vijay Kumar**  
Data Analytics | Python | Statistics | Hypothesis Testing | Business Analytics

## ⭐ Project Summary

This project demonstrates how a business question can be converted into a **statistical analysis framework**.

Rather than relying only on visual trends, the analysis uses hypothesis testing to distinguish between **observed differences and statistically supported evidence**.

**Business Question → EDA → Hypothesis → Statistical Test → Evidence → Business Interpretation**
