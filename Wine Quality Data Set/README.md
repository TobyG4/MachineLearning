README

Project to predict quality of wine from physicochemical inputs.

Using physicochemical inputs:
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol 

What is the problem?
We will try to predict the output "Quality", score is between 0-10.

Why does the problem need to be solve?
Useful for wine makers to help know factors are important in creating a good quqlity tasting wine, they could alter the process to achieve better tasting wine.

How would I solve the problem? (manually)
Taste various wines (same grapes different process), and note the qualiy of the wine. Then try to see which factors the good wines have in common, and which factors the bad wines have in common. 

Data:
From the UCL Machine Learning Database https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/ , red and white vinho verde wine samples, from the north of Portugal.

Data Set Characteristics: Multivariate

Number of Instances: red wine - 1599; white wine - 4898

Number of Attributes: 12 (11 input,1 output)

Missing Attribute Values: None


Likely that there is correlation between some of the attributes, so will look at removing some attributes when fitting model. 
	




