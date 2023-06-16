# US-Car-DataSet-

The following is a Random tree and a logistic regression of the student car survey data collected from NIU. 

* The clean dataset consisted of 205 observations and had 45 variables (questions).
* The target variable was the variable  "standard or Luxury"  which meant if the student had/wanted a luxury car or a standard (normal) car.
* The target variable was heavily skewed towards the standard side. 174 (85%) of the observations were classified as standard while 31 (15%) were classified as Luxury. This caused all kinds of issues in terms of building a model that correctly predicted luxury and resulted in the creation of a random forest model to increase model accuracy.
* I left descriptive interpretations of both the feature importance and Coefficients in the ipynb file.
