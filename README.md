# Regression
Here we have a step-by-step implementation of a linear regression model using the Iris dataset. 
1. Loading the dataset
We started by loading the Iris dataset using the Seaborn library, which provides the load_dataset('iris') function. This dataset contains information about different types of irises, including petal length and width.

2. Viewing the data
We have displayed the first few rows of the dataset to familiarize ourselves with the structure and data types used.

3. Selection of variables
We selected only two variables relevant to our linear regression model: 'petal_length' as the independent variable and 'petal_width' as the dependent variable.

4. Splitting the data set
We split the data into training and test sets using the train_test_split function in the sklearn.model_selection library. We allocated 60% of the data to training and 40% to testing to evaluate model performance.

5. Preparing data for the model
We rescaled the training and test data to be compatible with the linear regression model using numpy.array.reshape(-1,1).

6. Training the model
We created a linear regression object using LinearRegression() and trained it using the training data with fit(X_train, y_train).

7. Calculating predictions
We calculated model predictions for the training and test data using the predict() method.

8. Viewing the results
We visualized the results by displaying the training and test data together with the model predictions, using scatterplots.

