# Naive-Bayes-vs-KNN-Comparision-of-two-Bayesian-Classifiers


### Objective:
Bayesian classifiers performance comparision-Two different Bayesian classifiers are trained to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

### Dataset:
Source: kaggle- https://www.kaggle.com/uciml/pima-indians-diabetes-database <br />
The dataset consists of several medical predictor variables and one target label, "Outcome". Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. 

### Data Analysis:

![image](https://user-images.githubusercontent.com/24207916/140412850-b9260fb7-ebeb-4a39-9279-220b830c747a.png)

![image](https://user-images.githubusercontent.com/24207916/140412893-d71c9f11-bfa6-4709-b8c5-cd28650af8f7.png)

![image](https://user-images.githubusercontent.com/24207916/140412924-d6b07946-86f4-43d6-8820-cf66fdaf488c.png)


### Observations:
•	From correlation data above we can see that some of the features are slightly dependent of each other.<br />
•	As observed in the pairplot not all univariate distribution of the features with respect to Outcome (i.e. P(X/Outcome)) is a good approximation of Gaussian distribution.<br />
•	And for some of the features, likelihoods for each class i.e. P(xi/Outcome=0) ~ P(xi/Outcome=1) appears to be very similar. (In cases where P(xi/Outcome=0) ~ P(xi/Outcome=1) Naïve Bayes might not classify to its best)<br />
From above observations KNN classification might perform better than Naïve Bayes Classification for this small data set.<br /> 

### Results Comparision:

![image](https://user-images.githubusercontent.com/24207916/140413488-f6acb680-cac3-4dfa-a9b1-e6849a384c56.png)

The results confirm the observations made above.<br />
K nearest neighbors makes no assumptions of the dataset and give good results for datasets with small size as computational complexity won’t be a hindrance.<br />

Note: See iPython notebooks for Exploratory data analysis and implementation of Naïve Bayes & KNN models

