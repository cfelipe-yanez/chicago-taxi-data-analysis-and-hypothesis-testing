# Chicago Taxi Data Analysis and Hypothesis Testing

## Project Description

This project focuses on the exploratory analysis and statistical hypothesis testing of real taxi trip data from the city of Chicago. The analysis is based on multiple datasets obtained from previous SQL queries and provided as CSV files.

The objective is to explore taxi company activity, identify the most common drop-off locations, visualize key patterns, and test whether weather conditions affect trip duration.

---

## Datasets Used

### 1. Taxi Company Trips  
**File:** `project_sql_result_01.csv`

- `company_name`: Name of the taxi company  
- `trips_amount`: Number of trips made by each taxi company on November 15–16, 2017  

### 2. Drop-off Locations  
**File:** `project_sql_result_04.csv`

- `dropoff_location_name`: Chicago neighborhoods where trips ended  
- `average_trips`: Average number of trips ending in each neighborhood in November 2017  

### 3. Trip Duration and Weather  
**File:** `project_sql_result_07.csv`

- `start_ts`: Date and time when the trip started  
- `weather_conditions`: Weather conditions at the start of the trip  
- `duration_seconds`: Trip duration in seconds  

---

## Exploratory Data Analysis (EDA)

The EDA process includes:

- Importing and inspecting the datasets
- Verifying and correcting data types
- Identifying the top 10 neighborhoods by number of trip drop-offs
- Creating visualizations:
  - Taxi companies vs. number of trips
  - Top 10 neighborhoods by number of drop-offs
- Drawing conclusions from each visualization and explaining the observed patterns

---

## Hypothesis Testing

The following hypothesis is tested:

> **"The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays."**

### Methodology

- Definition of null and alternative hypotheses
- Selection of a significance level (alpha)
- Choice of an appropriate statistical test and justification
- Interpretation of the test results based on statistical evidence

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- SciPy
- Jupyter Notebook

---

## Outcome

The final notebook presents:
- Cleaned and well-structured datasets
- Clear exploratory insights supported by visualizations
- A well-documented hypothesis testing process
- Data-driven conclusions about taxi trip behavior in Chicago
