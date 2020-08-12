## Machine Learning Model Review

### model file - Logistic Regression (LOGR) Model

o Used the StandardScaler and LabelEncoder to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 0.8877, Testing Data Score: 0.8896.
o Applying GridSearchCV for model tuning and changing C values, and increasing the number of iterations 
  max_iter didn't improve scores. 

### model_1 file - SVM Model

o Used the MinMaxScaler to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 0.8455, Testing Data Score: 0.8415.
o Applying GridSearchCV for model tuning and changing C values, and changing gamma parameter didn't improve scores.  

### model_2 file - Linear Regression (LINR) Model

o Used the MinMaxScaler and LabelEncoder to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 0.6550, Testing Data Score: 0.6617.
o Applying GridSearchCV for model tuning and changing C values, and changing gamma parameter improvde scores drastically.  

### model_3 file - K Nearest Neighbor (KNN) Model

o Used the MinMaxScaler and LabelEncoder to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 0.8384, Testing Data Score: 0.8312.

### model_4 file - Random Forest (RF) Model

o Used the MinMaxScaler and LabelEncoder to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 1.0, Testing Data Score: 0.8953.
o Applying GridSearchCV for model tuning didn't improve scores.  

### model_5 file - Neural Network (NN) Model

o Used the MinMaxScaler and LabelEncoder to scale and normalize the data.
o The scores for training and testing data was :Training Data Score: 1.0, Testing Data Score: 0.8982.

## Summary and Conclusions

o Random Forest and Neural Network models returned basically identical results.
o Results for the top models were quite good given the complexity of the problem they solved.
o Logistic Regression model performed well not much worse than the other two models. 
o Linear Regression model performed the worst since this was not a linear problem.
o Hyperparameters tuning didn't help to differentiate the models significantly except for Linear Regression. 
o Hyperparameters tuning for Linear Regression made it a good model.
o The remaining two models, i.e., SVN and KNN performed slightly worse than the top three models. 
o Overall, all six models performed relatively well on this particular problem which is not an easy one.