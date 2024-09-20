This repository contains code used for a project I completed as part of the MSc Data Analytics from UCD for the module "Data Programming with R". I received an A+ grade for this module.

In this project I was tasked with finding an interesting data set to perform exploratory data analysis on and then subsequently (using your exploratory analysis) perform some machine learning techniques on the data set. I chose the German Credit Data as my data set, which is available from the UCI (University of California Irvine) machine learning data repository via the following link https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/german.data.

The data-set was compiled by Professor Hans Hofmann from the institute of Statistics and Econometrics at the University of Hamburg and contains information on 1,000 German borrowers collected between 1973 and 1975. The data set classifies borrowers as having “good” or “bad” credit ratings and also provides 20 additional variables for each credit customer e.g. duration of loan, customer’s credit history, purpose and amount of the loan etc. Further information regarding this data set can be found via this link
https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29.

My analysis consisted of a portfolio overview to gain a better understanding of the characteristics of the 1,000 customers in the data set. I then leverage this initial analysis to inform the machine learning techniques applied to the data to classify customers into "Good" and "Bad" credit ratings. I fitted both Logistic Regression and Decision Tree models to the German Credit data and found that the Logistic Regression performed slightly better achieving 75% accuracy over the Decision Tree which achieved 73.5% accuracy. 
