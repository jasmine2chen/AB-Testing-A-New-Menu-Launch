# A/B Testing: Conversion Rate of A New Web Page  

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
- Hypothesis
  
  Ho : P_old >= P_new, HA : P_old < P_new

- A/B testing, perform Hypothesis Testing and calculate p-values
 - - simulation
 - - using built-in function `statsmodels.api`

- Logistic Regression

## Conclusions
The performance of the old page was found slightly outperformed (by a very slim margin) or equal to the new page as computed using two techniques: A/B testing and logistic regression. Hence, we Reject the Alternate Hypothesis that the new page results in higher conversion rate than the old page. These inferences are strictly based on data available. This analysis acknowledges its limitations due to factors not included in the data.


