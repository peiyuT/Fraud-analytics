# Fraud-analytics
Card transaction Fraud 


The goal of the project is to build and test different machine learning algorithms based on card transaction data between January 1, 2010 and December 31, 2010 and find out the optimal model to predict future fraud.

To build and select an optimal supervised fraud model based on the card transaction data, we first cleaned the data, and then built 269 variables incorporating amount information, card information and transaction location information. We used feature selection methods to reduce the number of variables to 20. We split the card transaction data and used the data in November and December 2010 as out out-of-time data. 75% of the transactions from January to October 2010 were randomly selected to be used as training data and the remaining 25% used as testing data. After that, we built four supervised fraud models using four different types of machine learning algorithms: Logistic Regression, Neural Nets, Random Forests, and Boosting Trees, and found that Random Forests outperforms the rest three.

We concluded that Random Forest is superior to the rest three models we built. At 3% population cut-off, the result is FDR@3% of 99.0% for the training dataset and FDR@3% of 85.3% for the testing dataset. For the OOT dataset, we got FDR@3% of 39.1%.
