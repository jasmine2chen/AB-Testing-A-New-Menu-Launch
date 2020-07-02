# A/B Testing: A New Web Page  

## Background
An e-commerce company has developed a new web page to try to increase the number of users who "convert," meaning the number of users who decide to pay for the company's products.

As a data analyst, my role is to analyze the results of the experiment to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decisions.

## Datasets
- `ab_data.csv` contains information on user_id, timestamp, treatment or control group, landing_page and converted or not. 
- `countries.csv` contains a list of countries where the used are based off  

## Data Wrangling
- I handled records with missing or duplicates values
- I removed records where the landing_page and converted columns don't align

## Analysis
- A/B testing, perform Hypothesis Testing and calculate p-values
 -- simulation
 -- using built-in function `statsmodels.api`

- Logistic Regression


