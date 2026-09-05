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


## KEY INSIGHTS

1. **Ahmedabad has the highest average AQI (452)**, surpassing even Delhi (259)
2. **AQI dropped sharply during India's 2020 COVID lockdown** (Jan: 166 → April: 87), confirming reduced traffic/industrial activity improved air quality
3. **Strong seasonal pattern**: AQI peaks in Nov-Jan (winter smog, stubble burning) and drops lowest in Jun-Sep (monsoon)
4. **PM2.5 and CO show the strongest correlation with AQI** (0.66 and 0.68), confirming vehicle emissions as a major pollution driver
5. **National average AQI declined from 213 (2015) to 113 (2020) over the 6-year period**

## PROJECT FILES

- 📓 [Jupyter Notebook](./air_quality_analysis.ipynb)
- 📄 [Full Documentation (PDF)](./Air_Quality_Project_Documentation.pdf)
- 📁 [Screenshots](./screenshots)
