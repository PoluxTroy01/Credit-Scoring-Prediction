# Credit-Scoring-Prediction
A Logistic Regression approach to predict the probability of being a subject of loans.

## Solution
Basically to solve this problem, instead of going for good-0 and bad-1, the dependent variable was changed to the opposite. 
The change in the dependent variable (default) and the training of a single Logistic Regression model is to have a simple model that can be explained as in the real world to Financial regulators.
The independent variables will be transformed into 1s and 0s and by calculating the Weight of Evidence and Information Value we will be able to see the importance of the categories within each variable and the global weight of the variable as well.
New variables were created after the calculation of the WoE and IV.
Trained the model with all the variables and then selected the most important ones by getting their p-values, then retrained the model.
Validated the model, got the ROC & AUC score, the Gini coefficient, and the Kolmogorov-Smirnov value.

1.- Peso_Evidencia.ipynb
2.- Model-LR.ipynb
3.- Final_Model.ipynb
