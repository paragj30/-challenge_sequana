# -challenge_sequana
This challenge contains exploratory data analysis (EDA), feature selection, outliers detection, feature engineering like standardization, dimensionality reduction, and model training, and Hyperparameter tunning, and testing best ML model.
Here data size is 5091x506 (rowsXcolumns). Most of the feature attributes follows non-linearity behavior. It has been observed that, lots of outliers are present in the data. And that had been detected by using Z_score, IQR outlier detection techniques.
To avoid the data leakage problem. I splitted the data right at the begining between df_train & df_test.
Since there is not categorical data present in the dataset. So I need not to perform OneHotEncoding Task.
Standardization on the data so that they are in same range.
Here, By using I trained the couple of Machine Learing (ML) algoriths like LinearRegression, KNN, DecisionTreeRegressor, RandomForestRegressor, AdaBoost, SVM etc. Then I evaluate them using validation data like X_train & y_train. Also, I performed Hyperparameter tunning for each ML algorithm.
KNN, RandomForestRegressor, SVM giving me almost same r2_score. Hence I evluated them using X_test & y_train data. Eventually SVM gives better root mean squared error (RMSE), Mean squared Error(MSE) and R2_score.
