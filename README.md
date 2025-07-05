# Machine Learning Journey

## Supervised Learning

### Linear Regression
Predicting values based on one or more dependent features

#### Evaluation Metrics

- MAE (Mean Absolute Error) 
$$MAE=\frac{1}{n}\sum_{i=1}^n|x_i-x|$$
- MSE (Mean Squared Error)
$$MSE=\frac{1}{n}\sum_{i=1}^n|x_i-x|^2$$
- RMSE (Root Mean Squared Error)
$$RMSE=\sqrt{\frac{1}{n}\sum_{i=1}^n|x_i-x|^2}$$

### Logistic Regression

A method for classification

#### Evaluation Metrics

|Confusion Matrix|Predicted No|Predicted Yes|
|      :--:      |    :--:    |     :--:    |
|Actual No       |TN          |FP           |
|Actual Yes      |FN          |TP           |

- $\text{Accuracy}=\frac{TP+TN}{Total}$

- $\text{Precision}=\frac{TP}{TP+FP}$

- $\text{Recall}=\frac{TP}{TP+FN}$

- $\text{F1-Score}=\frac{2*Precision*Recall}{Precision+Recall}$

- $\text{Specificity}=\frac{TN}{TN+FP}$

### Classification
### KNN
### Decision Trees/Random Forests
### SVM
### Recommender Systems