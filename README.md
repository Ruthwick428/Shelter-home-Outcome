# Shelter-home-Outcome
predictive model for predicting the outcome type of the animals from Shelter Homes
Here I used R language for data cleaning and model building.
Some of the data manipulations done are as follows.
1. missing values were imputed in the age variable by using median imputation technique
2. Performed variable level reduction on the animal breed and animal color by colapsing the levels and grouping them together.
3. Added new variables from the existing variable "Date" such as time of day, day of the week and public holidays.
Finally performed predictive analytics by building a predictive model using Xg-Boost advanced machine learning algorithm and attained 
a logloss of 0.73.

