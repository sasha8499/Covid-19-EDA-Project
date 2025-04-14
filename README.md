# 🌍 COVID-19 Global Data Analysis (EDA Project)

This project is an Exploratory Data Analysis (EDA) of the global COVID-19 pandemic, using data from [https://www.kaggle.com/datasets/josephassaker/covid19-global-dataset]. 
The goal of this analysis is to uncover patterns, trends, and insights from the pandemic timeline by analyzing cases, deaths, and country-wise variations.

<br>

## 📁 Dataset

The dataset contains daily COVID-19 statistics for multiple countries. Key columns include:
- `date`
- `country`
- `cumulative_total_cases`
- `daily_new_cases`
- `active_cases`
- `cumulative_total_deaths`
- `daily_new_deaths`

The data was cleaned to handle:
- Missing values (NaNs)
- Negative values in daily case counts and deaths
- Date format inconsistencies

📂 Files used:
- `worldometer_coronavirus_daily_data.csv` (main dataset)
- `cleaned_covid19_data.csv` (cleaned version)

<br>

## 🔧 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

<br>

## 📊 Visualizations Created

1. **Global Daily New COVID-19 Cases Over Time**
2. **Global Daily New COVID-19 Deaths Over Time**
3. **Top 10 Countries by Total COVID-19 Cases**
4. **Top 10 Countries by Total COVID-19 Deaths**
5. **COVID-19 Trend in India**
6. **Monthly COVID-19 Cases & Deaths (Worldwide)**
7. **Monthly COVID-19 Cases – Top 5 Countries**
8. **Correlation Matrix of COVID-19 Metrics**

Each visualization helped identify key patterns in global spread, country-wise surges, and interrelationships among case and death trends.

<br>

## 📌 Key Insights

- The United States, Brazil, and India recorded the highest total deaths and cases.
- COVID-19 waves peaked at different times across countries, reflecting varied policy responses.
- Daily new deaths globally showed a declining trend after peak months.
- There’s a strong positive correlation between daily new cases and active cases.

<br>
