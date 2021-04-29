<h4>Data Desciption</h4>:
<ul>
<li><b>age</b>: continuous</li
<li>workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked</li>
<li><b>fnlwgt</b>: continuous.</li>
<li><b>education</b>: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 
9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool</li>
<li><b>education-num</b>: continuous</li>
<li><b>marital-status</b>: Married-civ-spouse, Divorced, Never-married, Separated, Widowed,
Married-spouse-absent, Married-AF-spouse</li>
<li><b>occupation</b>: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Profspecialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, 
Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces</li>
<li><b>relationship</b>: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried</li>
<li><b>race</b>: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black</li>
<li><b>sex</b>: Female, Male</li>
<li><b>capital-gain</b>: continuous</li>
<li><b>capital-loss</b>: continuous</li>
<li><b>hours-per-week</b>: continuous</li>
<li><b>native-country</b>: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, 
Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, 
Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, 
Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, 
Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, 
Holand-Netherlands</li>
<li><b>income</b>: >50K, <=50K</li>
</ul>

<h4>Task Performed</h4>
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