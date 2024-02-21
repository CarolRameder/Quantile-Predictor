# Quantile-Predictor

The data in imputation_test.csv consists of data on household electricity consumption.

The variables are as follows:
- hh-id: unique household id
- year: 2010 and 2011
- month: 4-8
- zipcode: anonymized zipcode in which home is located
- mozip: location variable derived from the interaction of zipcode with year and month. proxies for local humidity/temperature
- lusage: log(kwh) log of monthly electricity consumption
- lusage1-6: log(kwh) for April - September of 2009 (ie pre-sample period)
- children: household has children
- hhsize2-5plus: household size
- income2-9: income categories <$20k, $20-30k, $30-40k, $40-50k, $50-75k, $75-100k, $100-125k, >$125k
- owner: resident owns home
- size: size of the residence (in sqft)

Note: 
household electricity usage is based on billing records
household demographics were purchased from a third party data aggregator


Objective:

The aim of this mini-project is to develop a machine learning project to impute the missing values of one variable (size) based on the other data available.

1. Develop an algorithm to impute the missing values of `size`.
2. Provide quantitative measures of the quality of the imputation.
3. Quantify the degree of confidence for each imputation.
