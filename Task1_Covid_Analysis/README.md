# COVID-19 Data Analysis

## 1. Project Overview

This project analyzes COVID-19 data using Python. The analysis focuses on confirmed cases, deaths, recoveries, active cases, new cases, new deaths, and new recoveries across different countries.

The project was completed as part of the Data Science Internship tasks provided by Kodbud.

## 2. Objective

The main objectives of this project are:

* Load and understand a COVID-19 dataset.
* Perform basic data cleaning.
* Analyze confirmed COVID-19 cases.
* Analyze COVID-19 deaths.
* Analyze recovered cases.
* Analyze active and new cases.
* Compare COVID-19 statistics across countries.
* Analyze relationships between COVID-19 variables.
* Present findings using visualizations.

## 3. Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 4. Dataset

The dataset contains country-level COVID-19 statistics.

Important columns used in the analysis include:

* Country/Region
* Confirmed
* Deaths
* Recovered
* Active
* New cases
* New deaths
* New recovered
* WHO Region

## 5. Data Cleaning

The following data preparation steps were performed:

1. Loaded the dataset using Pandas.
2. Examined the number of rows and columns.
3. Checked column names and data types.
4. Checked for missing values.
5. Checked for duplicate records.
6. Removed duplicate records where applicable.
7. Created additional columns for Death Rate and Recovery Rate.

## 6. Analysis Performed

The following analyses were performed:

### Confirmed Cases

The countries with the highest number of confirmed COVID-19 cases were identified.

### Deaths

The countries with the highest number of COVID-19 deaths were identified.

### Recoveries

The countries with the highest number of recovered cases were identified.

### New Cases and New Deaths

Countries with the highest numbers of new cases and new deaths were analyzed.

### WHO Region Analysis

COVID-19 statistics were grouped by WHO region to compare regional trends.

### Death Rate

Death rate was calculated using:

Death Rate = (Deaths / Confirmed) × 100

### Recovery Rate

Recovery rate was calculated using:

Recovery Rate = (Recovered / Confirmed) × 100

### Correlation Analysis

A correlation matrix and heatmap were created to examine relationships between COVID-19 variables.

## 7. Visualizations

The project includes visualizations for:

* Top 10 countries by confirmed cases
* Top 10 countries by deaths
* Top 10 countries by recovered cases
* Top 10 countries by new cases
* Top 10 countries by new deaths
* Confirmed cases by WHO region
* Comparison of confirmed cases, deaths, and recoveries
* Correlation heatmap

## 8. Project Structure

```text
Task1_Covid_Analysis
│
├── dataset
│   └── covid.csv
│
├── notebooks
│   └── Covid_Analysis.ipynb
│
├── images
│   ├── top_confirmed_cases.png
│   ├── top_deaths.png
│   ├── top_recovered.png
│   ├── top_new_cases.png
│   ├── top_new_deaths.png
│   ├── cases_by_who_region.png
│   ├── covid_comparison.png
│   └── correlation_heatmap.png
│
├── results
│   └── covid_analysis_results.csv
│
└── README.md
```

## 9. Conclusion

This project provided practical experience in loading, cleaning, analyzing, and visualizing real-world COVID-19 data. Pandas was used for data manipulation, while Matplotlib and Seaborn were used to create visualizations. The analysis helped identify differences in COVID-19 cases, deaths, recoveries, and other statistics across countries and WHO regions.
