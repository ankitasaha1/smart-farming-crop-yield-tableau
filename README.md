# Smart Farming Crop Yield Analysis 🌾

## Overview
Interactive Tableau dashboard analysing IoT sensor data from 500 smart farms 
to identify which farming conditions, crop types and irrigation practices 
most reliably predict high agricultural yield.

## Tableau Live Dashboard
🔗 https://public.tableau.com/views/SMARTFARMINGCROPYIELDANALYSIS/Dashboard4?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Business Questions Answered
1. Which crop type delivers highest and most consistent yield?
2. Does irrigation type significantly impact yield?
3. Are environmental conditions or management decisions stronger yield predictors?
4. Where do geographic yield gaps exist across farming regions?

## Key Business Insights

**Irrigation Strategy:**
Cotton with Drip irrigation underperforms Cotton with No irrigation by 12% — 
challenging the assumption that more irrigation always improves yield. 
For agritech platforms recommending irrigation investment, this suggests 
drip systems may not deliver ROI in all soil conditions.

**Crop Selection:**
Soybean consistently delivers highest average yield of 4,256 kg/hectare 
across ALL irrigation types including No Irrigation — making it the most 
resilient crop in this dataset. For agricultural lenders assessing crop loan 
risk, Soybean farms represent the lowest yield risk across variable 
rainfall conditions.

**Management vs Environment:**
Rainfall and NDVI vegetation index show weak correlation with yield while 
irrigation type and crop selection show measurable yield differences. 
Management decisions outperform environmental conditions as yield predictors — 
critical insight for precision agriculture platforms.

**Geographic Yield Gaps:**
Geographic map reveals yield clustering patterns where farms in certain 
regions consistently outperform others despite similar environmental 
conditions — suggesting soil quality and farming practice quality drive 
differences that satellite weather data alone cannot explain.

**Fertilizer Finding:**
Inorganic fertilizer shows only 1.2% higher yield than Organic — 
statistically negligible difference providing no evidence that organic 
farming meaningfully reduces yield.

## Data Limitation
Crop disease severity shows no yield impact in this dataset — likely 
reflecting synthetic data generation rather than real biological patterns. 
Disease status should be excluded as a predictor variable until real 
observational data is available.

## Tools Used
- Tableau Public 2024
- IoT Sensor Data Analysis
- Geographic Mapping
- Heatmap Visualisation
- Trend Line Analysis

## Dataset
Smart Farming Crop Yield Dataset 2024 — Kaggle
- 500 farms
- 22 fields
- IoT sensor variables including NDVI Index, soil pH, 
  rainfall, humidity, temperature, disease status

## Dashboard Features
- 5 KPI cards — Avg Yield, Rainfall, Soil Moisture, Temperature, NDVI Index
- Geographic farm location map with yield colour coding
- Heatmap — Crop Type vs Irrigation Type with exact yield values
- Scatter plots with trend lines — Rainfall vs Yield, NDVI vs Yield
- Interactive filters — Crop Type, Irrigation Type, Region
- Yield by Fertilizer Type comparison

## Screenshots
<img width="1172" height="529" alt="MAIN DASHBOARD" src="https://github.com/user-attachments/assets/3f797380-a32d-4d0e-8301-d7daeee7e1c4" />
<img width="1164" height="527" alt="COTTON PERFORMANCE" src="https://github.com/user-attachments/assets/6305138a-85b5-45d5-a1c4-b3324fdfb761" />
<img width="1166" height="536" alt="SOYBEAN PERFORMANCE" src="https://github.com/user-attachments/assets/79632a70-09a7-4874-974a-5230c6c2012f" />


## Contact
LinkedIn:https://www.linkedin.com/in/ankitasahawork96/ 
