Solved a project where we have followed each step:
Import and Understand the Dataset
Data set as attached admission_data.csv
Load the dataset with columns Test1_Score, Test2_Score, and Admission_Status.
Understand the structure and format of the data.
Perform Descriptive Statistics
Summarize the data using mean, median, standard deviation, and range for Test1_Score and Test2_Score.
Check the distribution of Admission_Status (e.g., count of 0s and 1s).
Visualize the Data
Create scatter plots for Test1_Score vs. Test2_Score colored by Admission_Status.
Create histograms for both test scores to understand their distributions.
Check for Missing or Outlier Data
Identify missing values or outliers using box plots and handle them appropriately.
Split the Dataset
Divide the dataset into training and testing sets (e.g., 70% training, 30% testing).
Feature Scaling
Normalize or standardize Test1_Score and Test2_Score to ensure proper model convergence.
Build a Logistic Regression Model
Use the training data to build a logistic regression model predicting Admission_Status based on Test1_Score and Test2_Score.
Evaluate the Model
Evaluate the model's performance on the testing set using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Visualize Model Results
Plot the decision boundary over the scatter plot of test scores.
Create an ROC curve to illustrate model performance.
Test on New Data
Use sample new data (e.g., provided test scores) to predict Admission_Status.
new_data = pd.DataFrame({
    'Test1_Score': [50, 75, 90, 30],
    'Test2_Score': [40, 80, 95, 35]
})
Evaluate whether the predictions align with expectations.
