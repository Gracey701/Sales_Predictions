# Sales_Predictions
### Author: Grace Seo
## Business Problem
Objective of project is to explore the sales data and observe the correlations between the features and sales of the items sold.
## Methods
- Multiple graphs and plots were implemented to further understand the relationships between the differing features of the sold teams and the sales. 
- Using a heatmap gave a general understanding of what features correlated positively or negatively with sales.
  - See figure 1
- Those with an absolute value of around 0.5 or higher with item outlet sales are more correlated than those that are lower.
- From here, 2 different models were built (linear regression and decision tree) to be used to predict sales, comparing the results with the actual sales. 
- With the predicted and actual sales, metric values were calculated to determine the better model. Linear regression models predict the relationship between the independent and dependent variables. 
- Decision tree models predict the target variable based on varying variables. With the decision tree model, further edits were required to give the most optimal results based on the r^2 values from differing depths.
  - See figure 2
- Different calculative values were produced for both models: MAE, MSE, RMSE, and R^2
- Lower MAE, MSE, and RMSE indicate a more efficient model whereas a higher or closer to a value of 1 for R^2 is better as they are representative of a more accurate model.
- Based on the overall values of the regression metrics resulted, a more optimal model can be chosen over the other.
## Results
### Figure 1 
![sales heatmap](https://user-images.githubusercontent.com/113087687/196758743-8b61a605-074d-4215-90b3-5b9cf62bfab0.png)

Heatmap showing the correlation strengths between each features. The crossover of the vertical and horizontal features lists the correlation with the absolute values closer to 1 being stronger and lower numbers closer to 0 do not have as much correlation.
### Figure 2
![r^2 tree](https://user-images.githubusercontent.com/113087687/196762046-f1f8c73d-4a8e-4f41-94ed-f3f7f512c19a.png)

The orange line represents the training datas r^2 whereas the blue line represents the testing data r^2 values. They both slightly increase till the x-value of 5, but then the testing values start to decrease, creating a fork with the training data. This means the most optimal x-value to choose would be 5 as it would be more valid and any further would lead to more prediction errors. 
## Recommendations
Based on the results, a decision tree model of depth 5 is the better model to use for future predictions of sales and item MRP seems to have the most influence on sales.
