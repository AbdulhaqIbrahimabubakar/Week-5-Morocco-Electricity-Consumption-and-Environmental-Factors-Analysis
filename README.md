# Statistical and Time-Series Analysis of Electricity Consumption in Morocco

## Project Overview

This project focuses on analyzing electricity consumption patterns across three different zones in Morocco using statistical analysis, exploratory data analysis (EDA), and time-series techniques.

The objective is to understand how electricity demand changes over time, investigate relationships between electricity consumption and environmental conditions, and identify differences in consumption patterns across the three zones.

The project was completed as part of my Data Science internship with **AnalyticsLab Africa**.

## Project Objectives

- Explore and understand the structure and quality of the electricity consumption dataset.
- Perform data cleaning and preprocessing.
- Calculate descriptive statistics to understand consumption distributions.
- Identify hourly, daily, weekly, and monthly electricity consumption patterns.
- Investigate relationships between environmental variables and electricity demand.
- Compare consumption levels and variability across the three zones.
- Apply statistical tests to determine whether observed differences are statistically significant.
- Develop meaningful insights and recommendations from the analysis.

## Dataset Description

The dataset contains approximately 52,416 observations recorded at 10-minute intervals, covering the period from January 1, 2017, to December 30, 2017.

It contains nine columns:

| Column | Description |
|---|---|
| Datetime | Date and time of observation |
| Temperature | Recorded temperature |
| Humidity | Recorded humidity |
| WindSpeed | Recorded wind speed |
| GeneralDiffuseFlows | General diffuse flow measurements |
| DiffuseFlows | Diffuse flow measurements |
| PowerConsumption_Zone1 | Electricity consumption in Zone 1 |
| PowerConsumption_Zone2 | Electricity consumption in Zone 2 |
| PowerConsumption_Zone3 | Electricity consumption in Zone 3 |

## Tools and Technologies

- **Python:** Primary programming language.
- **Jupyter Notebook:** Interactive development and analysis environment.
- **Pandas:** Data manipulation and preprocessing.
- **NumPy:** Numerical computations.
- **Matplotlib:** Data visualization.
- **Plotly:** Interactive visualizations.
- **SciPy:** Statistical analysis and hypothesis testing.
- **Statsmodels:** Time-series analysis and statistical modelling.

## Project Workflow and Methodology

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined dataset dimensions, data types, and structure.
- Inspected missing values and duplicate records.
- Converted the Datetime column into an appropriate datetime format.

### 2. Data Cleaning and Preprocessing
- Checked and handled missing values.
- Investigated duplicate observations.
- Verified data types and consistency.
- Prepared the dataset for statistical and time-series analysis.

### 3. Exploratory Data Analysis (EDA)
- Examined distributions of numerical variables.
- Calculated mean, median, standard deviation, variance, quartiles, skewness, and kurtosis.
- Used histograms, boxplots, and other visualizations to understand data characteristics.
- Identified potential outliers and unusual consumption patterns.

### 4. Time-Series Analysis
Investigated electricity consumption patterns at different time intervals:

- Hourly consumption patterns.
- Daily consumption trends.
- Weekly consumption patterns.
- Monthly consumption trends.

Also explored time-series decomposition to examine trend, seasonal, and residual components.

### 5. Environmental Relationship Analysis
Investigated the relationship between electricity consumption and environmental variables, including:

- Temperature.
- Humidity.
- Wind speed.
- General diffuse flows.
- Diffuse flows.

Correlation analysis and statistical testing were used to examine these relationships.

### 6. Statistical Testing and Comparative Analysis

Applied statistical techniques to compare electricity consumption across the three zones.

Methods included:

- Pearson and Spearman correlation analysis.
- Analysis of Variance (ANOVA).
- Kruskal-Wallis test.
- Levene's test.

These techniques helped investigate differences in consumption levels, distributions, and variability.

### 7. Interpretation and Reporting

Translated analytical findings into meaningful insights, discussed dataset limitations, and developed recommendations based on the observed consumption patterns.

## Key Areas of Investigation

The analysis focuses on answering questions such as:

1. Which of the three zones records the highest electricity consumption?
2. How does electricity demand change throughout the day and across different months?
3. Are there noticeable daily and weekly seasonal patterns?
4. What relationships exist between environmental conditions and electricity consumption?
5. Are the differences in electricity consumption across the three zones statistically significant?
6. Which zone demonstrates the greatest variability in electricity demand?

## Key Findings

The project investigates differences in average electricity consumption, relative variability, temporal patterns, and environmental relationships across the three zones.

Detailed statistical results, visualizations, and interpretations are available in the Jupyter Notebook.

## Limitations

- The dataset covers approximately one year, limiting long-term seasonal comparisons.
- Observational relationships do not necessarily establish causation.
- Electricity consumption may be influenced by additional factors not included in the dataset.
- Time-series observations are temporally dependent, which must be considered when interpreting statistical tests.
- Measurement units and the precise interpretation of environmental flow variables should be verified against the dataset documentation.

## Project Structure

```text
Morocco-Electricity-Consumption-Analysis/
│
├── powerconsumption.csv
├── data_dictionary.csv
├── Morocco_Electricity_Consumption_Analysis.ipynb
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone [<repository-url>](https://github.com/AbdulhaqIbrahimabubakar/Week-5-Morocco-Electricity-Consumption-and-Environmental-Factors-Analysis/tree/main)
```

2. Navigate into the project directory:

```bash
cd Morocco-Electricity-Consumption-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib plotly scipy statsmodels jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the project notebook and execute the cells sequentially.

Ensure the dataset files are available in the appropriate project directory.

## Learning Outcomes

Through this project, I strengthened my practical understanding of:

- Data cleaning and preprocessing.
- Exploratory data analysis.
- Descriptive and inferential statistics.
- Time-series analysis and decomposition.
- Correlation analysis and hypothesis testing.
- Comparative statistical analysis.
- Data visualization and analytical reporting.

## Acknowledgement

Special appreciation to **AnalyticsLab Africa** for providing this internship opportunity and creating a platform to gain practical experience in Data Science through hands-on projects.

This project represents another step in my continuous learning journey toward becoming a Data Scientist and Machine Learning Engineer.

---

**Project Category:** Data Science | Statistical Analysis | Time-Series Analysis

**Programming Language:** Python

**Environment:** Jupyter Notebook

**Internship:** AnalyticsLab Africa
