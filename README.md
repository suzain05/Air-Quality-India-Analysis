 ## AIR QUALITY ANALYSIS - INDIA (2015-2020) EDA ANALYSIS

 

##  OVERVIEW

Analysis of daily air quality data across **26 Indian cities from 2015-2020**, **exploring pollution trends, seasonal patterns**, and the impact of COVID-19 lockdowns on air quality.

## DATASET

- Source: [Air Quality Data in India (2015-2020)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) - Kaggle, sourced from CPCB (Central Pollution Control Board, Govt. of India)

- 29,531 rows, 16 columns (city, date, pollutant readings, AQI

## TOOLS USED
  
- **Python (Pandas, Matplotlib, Seaborn)**
- **Jupyter Notebook**


  ## OBJECTIVES
  
- Identify India's most and least polluted cities based on average AQI
- Analyze how national air quality trended over 2015-2020
- Investigate whether India's COVID-19 lockdown measurably improved air quality
- Uncover seasonal pollution patterns across Indian cities
- Determine which pollutants most strongly influence overall AQI

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

## SKILLS DEMONSTRATED

- Data cleaning: handling missing values with group-wise (city-level) imputation strategies
- Exploratory Data Analysis (EDA) using Pandas
- Time-series feature engineering (extracting Year/Month from Date)
- Data visualization with Matplotlib and Seaborn (bar charts, line charts, correlation heatmaps)
- Deriving and validating real-world insights from raw data (e.g. cross-checking city AQI rankings against data availability)
- Documenting and communicating analytical findings clearly

## QUESTIONS SOLVED 

1. Which Indian cities have the highest and lowest average AQI?
2. How did national air quality change year-over-year from 2015 to 2020?
3. Did India's 2020 COVID-19 lockdown have a measurable effect on air quality?
4. Is there a seasonal pattern to pollution levels across India?
5. Which pollutants are most strongly correlated with overall AQI?

   
## PROJECT FILES

- 📓 [Jupyter Notebook](./air_quality_analysis.ipynb)
- 📄 [Full Documentation (PDF)](./Air_Quality_Project_Documentation.pdf)
- 📁 [Screenshots](./screenshots)

## Author
**Fathima Suzain** — **Data Analyst**

[![GitHub](https://img.shields.io/badge/GitHub-suzain05-181717?style=flat&logo=github)](https://github.com/suzain05)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/suzain-3090b82a7)
