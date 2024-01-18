# Churn on Telecom Services - Exploratory Data Analysis 📊🔍

This Jupyter Notebook serves as a powerful tool for analyzing customer churn, providing a step-by-step exploration of data using Python libraries. 🐍📈

## Requirements
To run this notebook you'll need to have the following installed:
- Python 3.11.ˆ
- Jupyter Notebook

## Usage
1. Clone the Repository
2. Run ```jupyter notebook```on your terminal (or through the VSCode)
3. Open the `eda_churn.ipynb` file in the Jupyter Notebook interface that appears in your web browser.
4. Run the cells to perform the EDA and generate the report.

## Acquired Knowledge

### Data Loading 📥

Begin by loading three essential datasets: `churn_customers.csv`, `churn_services.csv`, and `churn_contracts.csv`. These datasets contain valuable information about customers, their services, and contract details.

### Data Transformation 🔄

Explore various data transformation techniques, including handling missing values, renaming columns, and merging dataframes. Learn how to convert the 'TotalCharges' column to a float type and overcome challenges.

### Rename Columns 🏷️

Discover methods to rename columns in a dataframe using dictionaries or lists of new column names. Ensure your data is well-organized and labeled.

### Merge Dataframes 🔗

Master the art of merging dataframes based on a common column ('CustomerId') using different approaches. Gain insights into the length of each dataframe and merge multiple dataframes simultaneously.

### Missing Values Detection ❓

Explore techniques for detecting and handling missing values, including identifying, removing, and filling missing values. Ensure your data is robust and complete.

### Input Missing Values 🔄

Learn different methods for inputting missing values, such as replacing them with zeros, specific values, or the mean of the column. Keep your data consistent and reliable.

### Univariate Analysis 📊

Perform univariate analysis to understand the distribution of variables. Generate hypothesis tests and create engaging visualizations, including bar plots and histograms.

### Bivariate Analysis 📈📊

Investigate relationships between variables using contingency tables and chi-square tests. Explore the independence of categorical variables and assess correlations between numerical variables.

### Outliers Detection 🚨

Identify outliers using box plots, Tukey tests, and Z-scores, with a focus on the 'TotalCharges' variable within month-to-month contracts.

### Automating EDA 🤖📊

Experience the power of the Sweetviz library to automate the exploratory data analysis (EDA) process. Generate comprehensive visualizations and insights with ease.

For more details and hands-on exploration, dive into the code and visualizations provided in this notebook. Happy analyzing! 🚀🔍
