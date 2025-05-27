# Bright Motor Company – Data Analysis

## 📊 Overview

In this project, I analyzed the impact of rising CO₂ concentrations on global temperature changes using historical data. It combines data preprocessing, visualization, statistical modeling, and performance evaluation to interpret climate trends and predict future behavior.
---
## 🔍 Key Insights
- The mean temperature change is around  **0.54°C**, with a **median of 0.47°C and variance of 0.43°C**, indicating slight variability in temperature anomalies.
- For CO2 concentrations, the mean is **180.72ppm**, the median is **313.84** which is much higher than mean with the variance of **32,600**, which reflects substantial variability in CO2 level over the **1961 to 2022**. This shows the stronger fluctuation in CO2 data compared to temperature changes.
- A consistent increase in CO2 concentrations over the years, which can cause due the greenhouse gases. Simultaneously, there is a slight upward trend in global temperature change suggests that rising CO2 levels are associated with global warming.
- CO₂ levels are rising rapidly, the temperature impact, though slower, is accumulating steadily and may have long-term consequences.
- The heatmap reveals a very strong positive correaltion (0.96) between Temperature Change and CO2 Concentrations.
- This graph highlights the seasonal changes in CO2 Concentration which peak during late spring and early summer (around May) and reach the lowest levels in fall (around September).
- Pearson Correalation (0.955) & Spearman Correlation (0.938) both indicates very string linear and monotonic relationship between CO2 Concentration and Temperature change.
- Granger Causality Test shows no proof for causality.
- 10% increase in CO2 results in a notable rise in temperature anomalies, which demonstrated the sentivity of global temperatures to CO2 levels. Conversely, a 10% - 20% reduction in CO2 could lead to significant cooling effects, which will potentially reverse some warming trends.

---

## 🤖 Model: 

* **Input Features**: `CO2 Concentration`
* **Target Variable**: `Temperature Change`
* **Model Used**: Linear Regression

### 🔢 Model Results:

* **R2 Score**: 0.91 indicating good fit. 
* **RMSE & MAE**: 0.15 & 0.13 suggesting the model is accurate and consistent. 

---

## ✅ Conclusion
- There is **strong positive** correlation between rising **CO2 Concentration** and **Global temperature** Anomalies.
- CO2 levels are **increasing at a faster rate** than temperature changes.
- Time Series reveals a clear trends of **escalating emission driving temperature increases**, while seasonal variation suggest the moderate role of natural carbon sinks.
- Lagged effects suggest that **current CO2 levels have most significant impact on temperature changes**, with very small influence from the past emissions.
- Simulating "what-if" scenarios to demonstrate the sensitivity of Global temperature to CO2 levels, which shows that **even modest reduction in emissions could significantly ease global warming**.