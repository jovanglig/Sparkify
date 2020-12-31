# Sparkify
Submission for Udacity's Data Scientist Nanodegree Capstone Project.

## FILES IN REPO / DESCRIPTION

- Sparkify_final.ipynb (Python Jupyter notebook)
- Sparkify_final.html (HTML output)

*********************
## DESCRIPTION
This README concerns the Python code related to Udacity's Data Scientist Nanodegree Capstone Sparkify Project.
This repo has the code that was run in a AWS EMR cluster, in both Jupyter notebook format as well as HTML output.

The goal of this project is to predict customer churn of a fictitious music streaming platform called Sparkify. User log data was used of 22278 users to devise a model that can accurately predict churn, leveraging the Apache Spark framework and ML library to run ML pipelines on distributed data.

*********************
## MOTIVATION
I really wanted to learn how to use Spark and the Pyspark library to run ML models on distributed data and leverage cloud computing to run these models on big data. Therefore, for the final Capstone Project of Udacity's DSND I chose the Sparkify project, which allowed me to do just that. I learned how to use Spark, how to configure a cluster on AWS EMR and how to run a ML pipeline on a cluster. I am very happy with the amount of work I put in and the extra skills and knowledge I got from not only this project but from the course throughout.

Churn prediction is one of the most interesting use cases in machine learning in my opinion, and I have actually implemented machine learning models for my master thesis at a telecom company, which I did in the programming language R. It brings me great joy to now be able to do it using Python and Spark as well.



*********************
## RESULTS

The models used and their performance metrics: 

**Logistic Regression**

The accuracy on the test set is **83.33%** 
The F1 score on the test set is **80.37%** 
The areaUnderROC (AUC) on the test set is **81.02%**
The hyperparameters of the best model are: 
maximum iterations: 10
regularization parameter: 0

**Best model**:

**Random Forest**

The accuracy on the test set is **94.49%**
The F1 score on the test set is **83.74%**
The areaUnderROC (AUC) on the test set is **84.44%**
The hyperparameters of the best model are:
number of trees: 20
maximum depth: 20

**Gradient Boosted Trees**

The accuracy on the test set is **85.41%**
The F1 score on the test set is **82.73%**
The areaUnderROC (AUC)on the test set is **82.58%**
The hyperparameters of the best model are:
maximum iterations: 10
maximum depth: 5


I made a blogpost on the Medium platform about this analysis which you can find here:  https://medium.com/@jovangligorevi/finding-out-who-the-biggest-airbnb-home-owners-are-in-amsterdam-47bfdf8294f7

*********************
## LIBRARIES USED
- Pandas
- Numpy
- Pyspark
- Seaborn
- re
- matplotlib

*********************
## ACKNOWLEDGEMENTS
The code is part of an assignment for Udacity's Data Scientist Nanodegree, as such it is structured upon requirements given. 
