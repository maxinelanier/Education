# Education Inequality Analysis

## Overview: 
This project analyzes whether socioeconomic factors (income, parental education, etc.) are associated with student performance on standardized tests (SAT/ACT).

## Tools Used
- Python (pandas, numpy)
- Data visualization (matplotlib / seaborn)
- scikit-learn (regression modeling)
- Jupyter Notebook

## Data
This project uses two public datasets:

- **EdGap dataset (2016)** from EdGap.org, containing SAT/ACT scores and socioeconomic characteristics across school districts  
- **NCES dataset (2016–2017)** from the National Center for Education Statistics, providing additional school-level data 

## Methods
- Cleaned and standardized multiple datasets
- Merged datasets using common identifiers
- Handled missing values using imputation techniques
- Created new variables to better represent socioeconomic factors
- Performed exploratory data analysis (EDA)
- Built regression models to analyze relationships and predictive power
- Split data into training and testing sets for evaluation

## Key Findings
- Socioeconomic variables showed a measurable relationship with test performance
- Some variables were stronger predictors than others (e.g., income vs. other factors)
- Model performance suggests partial predictive capability, but not full explanation of outcomes

## Project Structure
- `education_data_preparation.ipynb` – data cleaning and preprocessing
- `education_analysis.ipynb` – EDA, modeling, and results

## What I Learned
This project strengthened my ability to work with messy real-world data, combine multiple datasets, and translate statistical analysis into meaningful insights.

## Next Steps
- Improve model performance with additional variables
- Explore non-linear models
- Investigate causal relationships vs. correlation

## Author:
Maxine Lanier
## Liscence: 
This project is open for public use.
