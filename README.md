# <font color=#5779c1> # Suprise_Housing_Advanced_Regression</font>

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market.

Required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.


## <font color=#5779c1> This case study mainly divided in to 3 phases : </font>
- Data understanding and exploration
- Data Visualisation and preparation
- Model building and evaluation(Linear, Ridge and Lasso Regression)


## <font color=#5779c1> Technologies Used</font>
1. pyplot from matplotlib
2. seaborn
3. GridSearchCV, train_test_split(model_selection), StandardScaler(preprocessing), LinearRegression, Ridge, Lasso(linear_model),
   r2_score, mean_squared_error(metrics), metrics from sklearn
   
## <font color=#5779c1> Conclusions</font>
The performance metrics of three different regression techniques - Linear Regression, Ridge Regression, and Lasso Regression.
- R2 Score (Train): Linear Regression has the highest R2 score (0.958938), followed by Ridge Regression (0.930574), and then Lasso Regression (0.950662), indicating that Linear Regression performs slightly better than Ridge and Lasso in terms of explaining the variability in the training data.
- R2 Score (Test): Ridge Regression has the highest R2 score (0.857320) on the test data, followed by Linear Regression (0.724097), and then Lasso Regression (0.702000), indicating that Ridge Regression performs better than Linear and Lasso in terms of generalization to unseen data.
- RSS (Train): Linear Regression has the lowest Residual Sum of Squares (RSS) on the training data (6.849184), followed by Ridge Regression (11.580304), and then Lasso Regression (8.229623), indicating that Linear Regression has the lowest residual errors on the training data.
- RSS (Test): Ridge Regression has the lowest RSS on the test data (9.405945), followed by Lasso Regression (19.645095), and then Linear Regression (18.188384), indicating that Ridge Regression has the lowest residual errors on the test data.
- MSE (Train): Linear Regression has the lowest Mean Squared Error (MSE) on the training data (0.081904), followed by Ridge Regression (0.106499), and then Lasso Regression (0.089779), indicating that Linear Regression has the lowest average squared error on the training data.
- MSE (Test): Ridge Regression has the lowest MSE on the test data (0.146543), followed by Linear Regression (0.203779), and then Lasso Regression (0.211782), indicating that Ridge Regression has the lowest average squared error on the test data.

**The top five predictive variable for Lasso model are:**</br>
PoolQC_Gd, Condition2_PosN, MSZoning_FV, MSZoning_RH, MSZoning_RL

**The top five predictive variable for Ridge Model are:**</br>
OverallQual_9, OverallCond_3, PoolQC_Gd, Neighborhood_Crawfor, Neighborhood_NridgHt
