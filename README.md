ANOVA Test on Iris Dataset


- This repository demonstrates how to perform a one-way ANOVA (Analysis of Variance) test using the classic Iris dataset. The goal is to check if there are statistically significant differences between the means of different Iris species with respect to certain features (such as sepal length, petal length, etc.).

Table of Contents
- Introduction
- Requirements
- Usage
- Example Output
- License


- Introduction
   
  ANOVA is a statistical method used to compare the means of three or more samples to determine if at least one group is significantly different from the others. In this project, we use the famous Iris dataset, which includes measurements of sepal length, sepal width, petal length, and petal width for three Iris species (Setosa, Versicolor, and Virginica). We apply one-way ANOVA to check whether there are significant differences between the species for each feature in the dataset.


Requirements  
 - Python 3.x
 - Libraries:
 - pandas
 - scipy
 - sklearn

Usage
 
 - Load the Iris dataset: The script loads the Iris dataset using sklearn.datasets.

     
Perform the ANOVA test
 
 - ANOVA is performed for each feature (e.g., sepal length, petal length) across the three species.
