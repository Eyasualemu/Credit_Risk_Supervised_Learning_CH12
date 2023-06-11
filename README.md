Supervised_Learning _CH12
Credit_Risk # Technology 
 These are the technologies the user can use to run the solution -- Jupyter notebook  -- Python -- Github -- To download the solution file. It's saved in githun as public
Test Data 
lending_data.csv
 # Contributors 
 The solution is developed by Eyasu Alemu LinkdIn account -- https://www.linkedin.com/in/eyasu-a-684854112 Email -- Bekaqa01@gmail.com Phone Number -- 202 344 0733


Using the starter code file and the provided csv complete the following steps.
	Split the Data into Training and Testing Sets
	Create a Logistic Regression Model with the Original Data
	Predict a Logistic Regression Model with Resampled Training Data
	Write a Credit Risk Analysis Report

1.	Split the Data into Training and Testing Sets
	After the csv file converted to the data frame, Create the labels set (`y`) from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns
	Check the balance of the label’s variable (`y`) by using the `value counts` function.
	Split the data into training and testing datasets by using `train_test_split`.
 ![image](https://github.com/Eyasualemu/Credit_Risk_Supervised_Learning_CH12/assets/44585226/c3570eec-bb18-48ea-8e1c-913c2832afb6)



2.	Create a Logistic Regression Model with the Original Data
	Fit a logistic regression model by using the training data (`X_train` and `y_train`).
 ![image](https://github.com/Eyasualemu/Credit_Risk_Supervised_Learning_CH12/assets/44585226/e5f62e8e-9aba-4e12-9017-3192f2afd95b)

	Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
	Evaluate the model’s performance by doing the following:

o	Calculate the accuracy score of the model.
o	Generate a confusion matrix.
o	Print the classification report.
 
![image](https://github.com/Eyasualemu/Credit_Risk_Supervised_Learning_CH12/assets/44585226/aa9b3dc8-2303-4963-9407-a5265dce4ee1)

3.	Predict a Logistic Regression Model with Resampled Training Data
	Use the `RandomOverSampler` module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points. 
	Use the `LogisticRegression` classifier and the resampled data to fit the model and make predictions.
	Evaluate the model’s performance by doing the following:

o	Calculate the accuracy score of the model.
o	Generate a confusion matrix.
o	Print the classification report.
![image](https://github.com/Eyasualemu/Credit_Risk_Supervised_Learning_CH12/assets/44585226/5030d0d3-6c60-463d-a5cb-313ff096b1bf)

 



  
  
