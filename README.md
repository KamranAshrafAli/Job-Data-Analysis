# Jobs in Data science analysis

## Github Profile Link
- [Kamran Ashraf](https://github.com/KamranAshrafAli)

## About the Dataset

This project utilizes a dataset sourced from [Kaggle](https://www.kaggle.com/), containing information about
jobs in Data science fields relate to salary, company size, Employe Experience and number of employe in different fields.

## Project Objectives

This project aims to analyze jobs, the number of employees, and salaries in relation to company size. It provides insights into the salary ranges within the data science field.

1. **Job Distribution:**  
   This column represents the distribution of various jobs across industries or fields, providing an overview of the most common job types.

2. **Jobs in Each Field:**  
   This column categorizes the number of jobs available in each specific field, offering insights into the popularity and demand of different domains.

3. **Company Size:**  
   This column reflects the size of companies (e.g., small, medium, large) and helps analyze how company size correlates with job opportunities and salaries.

4. **Salary According to Field:**  
   This column displays salary data segmented by field, highlighting the variations in compensation across different job roles and industries.


## Content of Notebook (`analysis.ipynb`)

The Jupyter Notebook (`analysis.ipynb`) performs the following steps:

1. **Libraries Import and Data Description:**
   - Imports necessary libraries such as `pandas` for data manipulation and visualization.
   - Loads the dataset into a Pandas DataFrame.
   - Conducts initial data exploration using functions like `head()`, `info()`, and `describe()` to understand the structure, data types, and basic statistics of the dataset.

2. **Data Preprocessing and Cleaning:**
   - Selects relevant columns for analysis: 'Job Title', 'Company Size', 'Number of Employees', 'Salary'.
   - Handles missing values through appropriate methods like mean/mode.
   - Confirms data quality by checking for remaining missing or erroneous values.

3. **Exploratory Data Analysis (EDA):**
   - **Job Distribution:** Visualizes the distribution of job roles to identify the most common positions in the dataset.
   - **Jobs by Field:** Analyzes the number of jobs available in each field or industry.
   - **Company Size Distribution:** Examines the distribution of companies by size (e.g., small, medium, large) and its relationship to job availability and salaries.
   - **Salary Analysis:** Explores salary ranges in relation to job fields and company size, identifying trends and patterns.

4. **Insights and Visualizations:**
   - Includes bar charts, boxplots, and other visualizations to summarize findings, such as:
     - The relationship between company size and average salary.
     - Differences in salaries across various job fields.
     - The correlation between the number of employees and salary ranges.

## Conclusion

This project provides valuable insights into the relationship between job roles, company size, number of employees, and salaries in the dataset. Key findings include:

- **Job Distribution:** There is a clear concentration of job roles within specific fields, with some job titles appearing more frequently than others.
- **Company Size and Salary:** The analysis shows that larger companies tend to offer higher salaries, while smaller companies have a broader range of salary variations.
- **Salary by Field:** Different job fields exhibit distinct salary ranges, with certain industries offering higher compensation compared to others.

Overall, this analysis provides a comprehensive view of salary trends in relation to job roles, company size, and other key factors within the dataset.

**Libraries Used:**

*   **pandas:**  Data manipulation and analysis in tabular format.

**Functions and Techniques Used:**

*   **Data Preprocessing:** Missing value handling (median and mode imputation), data cleaning, handling duplicates, and dealing with inconsistent data formats.
*   **Exploratory Data Analysis (EDA):** Descriptive statistics, data visualization using bar charts and histograms, grouping data by specific columns with `groupby()`, categorizing data using `pd.cut()`, and analyzing distributions.
*   **Functions:** 
    - `pandas.read_csv()` for loading the dataset.
    - `pandas.DataFrame.head()`, `pandas.DataFrame.info()`, and `pandas.DataFrame.describe()` for initial data exploration.
    - `pandas.DataFrame.isnull().sum()` to check missing values.
    - `pandas.DataFrame.fillna()` and `pandas.DataFrame.dropna()` for handling missing data.
    - `pandas.DataFrame.duplicated()` and `pandas.DataFrame.drop_duplicates()` for detecting and removing duplicates.
    - `pandas.DataFrame.groupby()` to group data for analysis.
    - `pandas.DataFrame.plot()` for data visualization.
    - `pandas.cut()` for binning numerical data into categories.
    - `pandas.DataFrame.value_counts()` to count occurrences of unique values.
