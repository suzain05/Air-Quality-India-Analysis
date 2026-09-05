 ## AIR QUALITY ANALYSIS - INDIA (2015-2020) EDA ANALYSIS
 

##  OVERVIEW

Analysis of daily air quality data across **26 Indian cities from 2015-2020**, **exploring pollution trends, seasonal patterns**, and the impact of COVID-19 lockdowns on air quality.

## DATASET

- Source: [Air Quality Data in India (2015-2020)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) - Kaggle, sourced from CPCB (Central Pollution Control Board, Govt. of India)

- 29,531 rows, 16 columns (city, date, pollutant readings, AQI

## TOOLS USED
  
- **Python (Pandas, Matplotlib, Seaborn)**
- **Jupyter Notebook**

## DATA CLEANING

- Dropped Xylene column (61% missing values)
- Filled missing pollutant values using city-wise median, with overall median as fallback
- Dropped rows missing AQI (calculated field, not raw sensor data)
- Final dataset: 24,850 rows, zero missing values
