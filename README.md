# Vehicle Fuel Type Registration Time Series Analysis (2014–2024)

## Overview

This project analyzes monthly vehicle registration trends across different fuel types in India from 2014 to 2024. Using a Vector Autoregression (VAR) model, it explores the interdependencies between major fuel categories-petrol, diesel, CNG, hybrid, and electric vehicles (EVs)-and provides forecasts for future registrations. The analysis offers insights into the evolving automotive landscape and the adoption of alternative fuels.

---

## Dataset

- **Source:** Merged monthly vehicle registration data (`merged_df.xlsx`)
- **Period:** January 2014 to September 2024
- **Features:**  
  - Date (monthly)
  - Registration counts for:  
    - Petrol  
    - Diesel  
    - CNG  
    - Hybrid  
    - Electric (EV)  
    - Additional types (e.g., LPG, Ethanol, Solar, etc.)

---

## Project Workflow

- **Data Loading & Cleaning:**  
  - Import data and handle missing values.
  - Aggregate and rename columns for key fuel types.
- **Exploratory Data Analysis (EDA):**  
  - Visualize trends for each fuel type.
  - Examine summary statistics and outliers.
- **Stationarity Checks:**  
  - Apply differencing and statistical tests to ensure time series are suitable for VAR modeling.
- **VAR Model Building:**  
  - Select optimal lag order.
  - Fit the VAR model to the multivariate time series.
- **Forecasting:**  
  - Generate forecasts for major fuel types.
- **Result Interpretation:**  
  - Analyze how trends in one fuel type may influence others.
  - Discuss implications for industry and policy.

---

## Key Findings

- **Petrol and Diesel:**  
  Petrol registrations have consistently led the market, with diesel as the second most common fuel type. Both show fluctuations, with petrol generally increasing and diesel showing a gradual decline in recent years.
- **Rise of EVs and Hybrids:**  
  Electric vehicle (EV) and hybrid registrations, while much lower in absolute numbers, have shown steady growth-especially post-2020-signaling a shift toward cleaner mobility.
- **CNG:**  
  CNG registrations remain stable with moderate growth, reflecting its role as a transitional alternative fuel.
- **Interdependencies:**  
  The VAR model suggests that increases in EV and hybrid registrations may coincide with slowdowns in diesel and, to some extent, petrol vehicle growth.
- **Forecasts:**  
  - Petrol and diesel are projected to remain dominant in the near term but may plateau or decline as EV and hybrid adoption accelerates.
  - EV and hybrid vehicles are expected to continue their upward trend, though with some volatility.


## Conclusion

This project demonstrates how multivariate time series analysis can reveal the dynamic relationships among different vehicle fuel types. The findings highlight India's gradual transition from traditional fuels (petrol/diesel) toward electric and hybrid vehicles. The VAR model's forecasts provide valuable guidance for policymakers, manufacturers, and investors as they navigate the future of mobility in India.

