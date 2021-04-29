<h4>Implemnting Machine Learning using PySpark</h4>
<ol>
<li>Load data using PySpark</li>
<li>Data Preprocessing</li>
<li>Build the Pipeline to perform multiple tasks </li>
<ol>
<li>Pass the stages of Data Preprocessing (created in Step 3) to the pipeline to 
create an instance with the stages</li>
<li>Estimator that can fit on a DataFrame to produce a model</li>
<li>Transform the DataFrame with features to DataFrame with predictions</li>
<li>Generate a DataFrame which can hold a variety of datatypes including 
feature vectors</li>
</ol>
<li>Split the dataset into two parts (80%-20%) as Train and Test Datasets</li>
<ol>
<li>Check the shape of the datasets</li>
<li>Check the distribution of income class (0,1) in train and test dataset</li>
</ol>
<li>Build the following Classifiers</li>
<ol>
<li>.Logistic Regression</li>
<li>Decision Tree</li>
<li>Random Forest</li>
<li>Gradient Boosted Tree</li>
<li>Naïve Bayes</li>
</ol>
Common Tasks for all the Classifiers:
<ul>
<li>.Train and Evaluate the Model </li>
<li>Print ROC metrics & model accuracy</li>
<li>Tune the Hyperparameters and print the improved accuracy</li>
</ul>
</ol>