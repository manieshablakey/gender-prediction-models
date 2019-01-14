This notebook uses the Student Alcohol Consumption dataset from Kaggle. It contains demographic, social and academic information relating to students in a maths course at two secondary schools in Portugal. Data is provided for a total of 33 features related to each student, including gender. The objective of this notebook is to build and evaluate two machine learning models to predict the gender of a student.

Preliminary analyses of all the study features is initially conducted and presented in graphical form.

A Decision Tree model is built and the output image of the Decision Tree is given. All features, except gender, as used as input features. Accuracy score and evaluation measures from the confusion matrix are also listed. The model is then used to make basic predictions using 2 observations. One is an observation from the training dataset and the other is a made-up observation (unrelated to the student dataset). Prediction probabilites are also calculated.

GridSearchCV is then used to formulate the best fitted Decision Tree model. Predictions are made using the same observations detailed above. Prediction probabilities are also calculated.

Next, a Logistic Regression model is built, using all features, except gender, as input features. Accuracy score and evaluation measures from the confusion matrix are also listed. Predictions are made using the same observations detailed above.

GridSearchCV is the used to formulate the best fitted Logistic Regression model. Again, predictions are made using the same observationa deailed above.



