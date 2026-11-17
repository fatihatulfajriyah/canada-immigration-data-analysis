# **Canada Immigration Data Analysis (1980–2013)**

## **Project Overview**

This project analyzes historical immigration records to Canada from 1980 to 2013 using Python. The analysis explores annual immigration trends, identifies the five countries with the highest cumulative recorded counts, and compares their immigration patterns over time.

## **Project Details**

- **Tools:** Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn
- **Dataset:** Canada Immigration Dataset
- **Total Records:** 195 Countries
- **Analysis Period:** 1980–2013

## **Project Objectives**

- Analyze annual immigration trends to Canada from 1980 to 2013.
- Identify the five countries with the highest cumulative immigration counts.
- Compare annual immigration patterns across the top five countries.
- Identify years with the largest year-over-year increases and decreases.
- Present analysis results through data visualizations.

## **Analysis Process**

**1. Data Loading**

Imported the Canada Immigration dataset from an Excel workbook and inspected its initial records.

**Key Findings:**
- 195 country records.
- 43 original columns.
- Annual immigration data covering 1980–2013.

**2. Data Understanding**

Explored dataset columns, data types, and descriptive statistics to understand the dataset structure and identify relevant fields.

**3. Data Cleaning & Preparation**

Removed unnecessary classification columns, renamed metadata columns, converted year columns to numeric values, and checked data quality.

**Key Findings:**
- 195 country records retained.
- 37 columns after removing unnecessary fields.
- No missing values.
- No duplicate rows or country names.

**4. Exploratory Data Analysis (EDA)**

Reshaped the dataset from wide to long format using Pandas `melt()` and explored the distribution of immigration counts using descriptive statistics.

**Key Findings:**
- 195 countries across 34 years.
- 6,630 country-year records.
- 6,409,153 total recorded immigration counts across the period.

**5. Data Analysis**

- **Overall Immigration Trend:** Aggregated annual immigration counts and calculated year-over-year changes.
- **Top 5 Countries:** Ranked countries based on their cumulative recorded immigration counts.
- **Country Trend Comparison:** Compared annual immigration patterns across the five leading countries.

**Key Findings:**
- The highest annual immigration count occurred in 2010, with 276,956 recorded immigrants.
- India ranked first with 691,904 cumulative recorded counts.
- The largest year-over-year increase occurred in 1987.
- The largest year-over-year decrease occurred in 1998.

**6. Data Visualization**

Created visualizations using Matplotlib and Seaborn to present:
- Overall annual immigration trends.
- Top five countries by cumulative recorded counts.
- Annual immigration trends across the top five countries.

## **Key Findings & Recommendations**

- Immigration counts varied across the 1980–2013 period, with the highest annual total recorded in 2010.
- India had the highest cumulative recorded count, followed by China and the United Kingdom.
- The leading countries showed different annual immigration patterns.
- Further investigation of years with significant changes could provide additional historical context.

**Recommendations:**
- Use historical trends as a reference for further research, not as a forecast of current immigration.
- Examine leading countries separately to understand differences in immigration patterns.
- Investigate significant annual changes using reliable historical, policy, or economic sources.

## **Python Skills Applied**

- Data Loading and Exploration
- Data Cleaning and Validation
- Data Transformation using `melt()`
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Data Aggregation using `groupby()` and `sum()`
- Year-over-Year Analysis using `diff()`
- Data Sorting and Filtering
- Data Visualization using Matplotlib and Seaborn

## **Project Files**

- `canada_immigration_dataset.xlsx` – Original dataset.
- `canada_immigration_trend_analysis.ipynb` – Python analysis notebook.
- `annual_immigration_trend.csv` – Annual immigration summary.
- `top5_countries.csv` – Top five countries by cumulative counts.
- `canada_immigration_long.csv` – Transformed immigration dataset.
- `README.md` – Project documentation.

## **Conclusion**

This project demonstrates the use of Python for data cleaning, exploration, transformation, and analysis. The results highlight historical immigration trends to Canada, the countries with the highest cumulative recorded counts, and differences in their annual patterns.

*Note: This analysis uses historical data from 1980 to 2013 and does not represent current Canadian immigration statistics.*
