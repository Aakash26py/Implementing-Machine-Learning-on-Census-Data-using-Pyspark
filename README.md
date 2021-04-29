

Machine Learning using PySpark

1. Load data using PySpark
2. Perform Exploratory Data Analysis (EDA) and Data Cleaning based on the following 
points:
a. Find the shape and schema of the dataset
b. Obtain insights (statistics) of different columns
c. Obtain the Unique values of Categorical Columns 
d. Check if any unwanted values are present in the data such as Null, ? or NaN
e. Remove unwanted values if present in any of the columns (numerical as well 
as categorical columns)
f. Obtain the relationship between different columns using covariance which 
shows the degree of interdependence of the two columns
g. Obtain distinct values and their counts in categorical columns.
h. Create a crosstab on two different columns (example, age & workclass)
i. Perform an “Integer Type Check” on the columns of the Spark DataFrame 
and display the columns satisfying the same
j. Obtain correlation between the above columns using pandas scatter plot
3. Data Preprocessing
Since we are going to use classification algorithms like Logistic Regression, we will have 
to convert all the categorical columns in the dataset to numerical values. We can 
achieve this using
1) Category Indexing 
In this, we assign a numerical value to each category (eg: Male: 0, Female: 1)
2) One-Hot Encoding
In this step, we will be using a combination of Category Indexing and One-Hot Encoding
a. Conversion of categorical columns into Numerical Columns
i. Category Indexing using string indexing for all categorical columns
ii. Label Indexing for income column as income_class 
iii. One Hot Encoding which generates binary columns for features
iv. Use Vector assembler to get a single vector column for features
v. Make it as an array of stages so that it can be passed to a pipeline 
4. Build the Pipeline to perform multiple tasks 
a. Pass the stages of Data Preprocessing (created in Step 3) to the pipeline to 
create an instance with the stages
b. Estimator that can fit on a DataFrame to produce a model
c. Transform the DataFrame with features to DataFrame with predictions
d. Generate a DataFrame which can hold a variety of datatypes including 
feature vectors
5. Split the dataset into two parts (80%-20%) as Train and Test Datasets
a. Check the shape of the datasets
b. Check the distribution of income class (0,1) in train and test dataset
6. Build the following Classifiers
a. Logistic Regression
b. Decision Tree
c. Random Forest
d. Gradient Boosted Tree
e. Naïve Bayes
Common Tasks for all the Classifiers:
• Train and Evaluate the Model
• Print ROC metrics & model accuracy
• Tune the Hyperparameters and print the improved accuracy