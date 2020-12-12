# SD03Q06---Curnue-Task

1) SOCIAL NETWORK ADS - RANDOM FOREST CLASSIFICATION

    The Dataset contains information about users on a Social Networking site and using that info as Features for our ML model,we try to predict that whether a particular user     after clicking on a ad on the Social networking site goes on to buy a particular product or not. Now the work of the social network here is to gather information as to       whether the user bought the product or not.The dependent variable in this case is Purchased which is 1 if user purchases the car and 0 otherwise.
    The following features will be considered as the independent variables…
    1)Age
    2)Estimated Salary
    3)UserId
    4)Gender

    Splitting the dataset into the Training set and Test set using ModelSelection and divide the data into 75% data for training and 25% for testing data.
    Now, applying Feature Scaling because to get accurate prediction. For this StandardScalar is used.

    Fitting Random Forest Classification to the Training set with some parameters like n_estimators, criterion as entropy and random state as 0. Predict the Test set with         random forest model classifier and displaying the results in confusion matrix.

    Since the classifier has been fit to the Dataset we can predict the Outcomes of the test set. So when we run this we get an accuracy of about 91% which is a great             achievement for our classifier. With this we end our predictions with data visualization, which helps us visualize the accuracy and the errors of our model.
    
    
2) DIABETES DATABASE - LOGISTIC REGRESSION

    The datasets include data from 768 women with several medical predictor variables and one target variable. The classification goal is to predict whether or not the           patients in the dataset have diabetes or not. The dependent variable in this case is Outcome which is 1 if user has diabetes and 0 otherwise.
    Then the following features will be considered as the independent variables
    1)Pregnancies
    2)Glucose
    3)Blood Pressure
    4)Skin Thickness
    5)Insulin
    6)BMI
    7)Diabetes Pedigree Function
    8)Age 
    9)Outcome

    We divided the data into X and y data frames. X has eight input features and y is a single output for the prediction we want to make — whether or not the patients have       diabetes or not. We then split them each into training and testing data. To split the data into test and train we will use the train_test_split function from sklearn. We     have split the dataset in a 75:25 ratio.

    To apply Logistic Regression model to classify we call the model using LogisticRegression () function. First, we will train our dataset in Logistic Regression model on       (X_train, y_train) and we will use (X_test, y_test) to evaluate the model generated. Then We build the Logistic Regression model and predict for X_test and compare           prediction to the y_test.

    There we get accuracy of 80% precise classifier using Logistic Regression. To understand the evaluation in more depth we used confusion matrix metric.
