# Supervised Classification Algorithm using Python on Kickstarter Dataset

## Research Question: Predicting whether a currently "Live" project will Succeed or Fail based on the projects which were previously "Successful" or "Failure

# Description of the data set:
In this project, the data set used is the Kickstarter data set,extracted from Kaggel website. Kickstarter is a funding platform for creative projects. Everything on kickstarter is a project. A project is a work with a clear goal that the creator wants to bring into life. Lets take a look at the attributes of the kickstarter data set.

### Here are the steps involved:
 * Data extraction
 * Data Cleaning
 * Data manipulation
 * Exploratory Data Analysis
 * Predictive Analysis
 
 ### KNN Classification Algorithm
 
 * The training and testing data have feature variables which should be independent of each other and the taget variable which is dependent on the feature variable.
 * The feature variables taken are : usd_pledged_amount,backers,goal_amount,project_year
 * The target variable for training data are the observations whose project state is "Successful" or "Failure" and for the testing data it is the observations whose project state is "Live"
 * After splitting the data, we run the KNN model on the data
 * After the prediction, the result is an array of live projects which are labelled as successful or failed. 
 * So, all the live projects are predicted to be successful or failure.
 * The accuracy obtained is 94% using the KNN algorithm.
 * Apart from the KNN algorithm,Logistic Regression model has also been tested for the same training and testing data.
 * The accuracy obtained is 83% using the Logistic regression. 
 
 
 In summary, based on the feature variables taken, the KNN model gives better accuracy when compared to the Logistic Regression model.
 



