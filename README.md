# Predict the test's score of students using regression techniques


The objective is to predict the score of students at their test using information about students such as school the attend, the type of school (public/private), class, teaching method, gender and score they obtained at the pre-test.

There is a strong linear relationship between the score obtained at the pre-test and the score obtained at the final test. Still, adding other variables results were improved considerably.

Different models and regressors have been tried.
A simple linear regression obtained a MAE of 3.56 and a RMSE of 4.39.
Using more sophisticated model and more predictors better results have been obtained. The best model found is a KNN regressor which obtained a MAE error of 2.57 and a RMSE of 3.29.

These can be considered good results since the score has a 0-100 range
