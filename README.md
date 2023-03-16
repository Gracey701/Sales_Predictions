# Sales_Predictions
### Author: Grace Seo
## Business Problem
Objective of project is to explore the sales data and observe the correlations between the features and sales of the items sold.
## Methods
- Multiple graphs and plots were implemented to further understand the relationships between the differing features of the sold teams and the sales. 
- Using a heatmap gave a general understanding of what features correlated positively or negatively with sales as shown in figure 1 below.
- Those with an absolute value of around 0.5 or higher with item outlet sales are more correlated than those that are lower.
- From here, 2 different models were built (linear regression and decision tree) to be used to predict sales, comparing the results with the actual sales. 
- With the predicted and actual sales, metric values were calculated to determine the better model. Linear regression models predict the relationship between the independent and dependent variables. 
- Decision tree models predict the target variable based on varying variables. With the decision tree model, further edits were required to give the most optimal results based on the r^2 values from differing depths shown in figure 2 below.
- Different calculative values were produced for both models: MAE, MSE, RMSE, and R^2
- Lower MAE, MSE, and RMSE indicate a more efficient model whereas a higher or closer to a value of 1 for R^2 is better as they are representative of a more accurate model.
- Based on the overall values of the regression metrics resulted, a more optimal model can be chosen over the other.
## Results
### Figure 1 
![sales heatmap](https://user-images.githubusercontent.com/113087687/196758743-8b61a605-074d-4215-90b3-5b9cf62bfab0.png)
### Figure 2
![r^2 tree](https://user-images.githubusercontent.com/113087687/196762046-f1f8c73d-4a8e-4f41-94ed-f3f7f512c19a.png)
## Recommendations
Based on the results, a decision tree model of depth 5 is the better model to use for future predictions of sales and item MRP seems to have the most influence on sales.
