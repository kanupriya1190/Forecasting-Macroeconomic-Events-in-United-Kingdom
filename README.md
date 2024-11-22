# Forecasting Macroeconomic Events in the United Kingdom

**Location**: Los Angeles, California  
**Role**: Forecaster | Forecasting and Data Analysis  
**Duration**: October 2023 – December 2023  
**Tools**: Excel, Python

---

## Project Overview

This project analyzed macroeconomic data from the United Kingdom to forecast key economic trends and uncover relationships among variables like GDP, CPI, and bank rates. Utilizing advanced econometric models, the study highlighted the impact of events such as Brexit, the COVID-19 pandemic, and geopolitical tensions on inflation, interest rates, and economic policies.

---

## Key Insights

- **Causal Relationships**: Applied **Granger Causality** tests to uncover bidirectional causation between the UK bank rate and inflation, confirming the intricate relationship between monetary policy and price levels.
- **Long-Term Trends**: Cointegration analysis revealed stable, statistically significant relationships:
  - GDP and public debt showed poor debt management trends.
  - UK’s trade dependency on the EU decreased post-Brexit, signaling diversification.
- **Policy Impacts**: The VAR model and error variance decomposition demonstrated how policy variables like interest rates propagate through the economy, providing crucial forecasting insights.

---

## Methodology

1. **Econometric Models**:
   - **Cointegration Analysis**: Identified long-term equilibrium relationships among variables.
   - **Granger Causality**: Explored predictive causality between economic variables.
   - **VAR (Vector AutoRegression)**: Modeled interdependencies and forecasted responses to shocks.
   - **FEVD (Forecast Error Variance Decomposition)**: Quantified the contribution of shocks to forecast errors.

2. **Key Variables**:
   - GDP, CPI, bank rates, public debt, trade balances, unemployment, and output.

3. **Data Processing**:
   - Seasonally adjusted, quarterly time series from 2017 Q1 to 2023 Q3.
   - Python libraries: `statsmodels`, `pandas`, `numpy`, `matplotlib`.

---

## Results

- Inflation in the UK was primarily driven by post-Brexit conditions, the pandemic, and geopolitical crises.
- The bidirectional causality between bank rates and inflation highlighted the challenges of balancing monetary policy.
- The UK’s GDP and trade balance with the EU demonstrated weak dependency, signaling economic shifts towards non-EU trade partners.

---

## Repository Contents

- **Data Processing Scripts**: Python scripts for preprocessing, seasonal adjustments, and feature engineering.
- **Econometric Models**: Implementation of VAR, cointegration, and Granger Causality tests.
- **Visualization Outputs**: Plots and graphs of impulse response functions, FEVD, and time series trends.
- **Documentation**: A comprehensive report on findings and implications for UK policymakers.

