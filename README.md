# Naive Bayes Classifier

**` Author : Alhasan Gamal Mahmoud `**

**` Date   : 21 - 04 - 2022 `**

**In this Script, I will develop a python program that is able to Understand `Naive Bayes consept` and implementation it with different Case Study**
<br>


<img src="https://miro.medium.com/max/1400/1*PFTMCvOIPChMEcgtVS0RBQ.jpeg">


### What is a classifier?

A classifier is a machine learning model that is used to discriminate different objects based on certain features.

### Principle of Naive Bayes Classifier:

A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.


## Types of Naive Bayes Classifier:

### Multinomial Naive Bayes:

This is mostly used for document classification problem, i.e whether a document belongs to the category of sports, politics, technology etc. The features/predictors used by the classifier are the frequency of the words present in the document.

### Bernoulli Naive Bayes:

This is similar to the multinomial naive bayes but the predictors are boolean variables. The parameters that we use to predict the class variable take up only values yes or no, for example if a word occurs in the text or not.

### Gaussian Naive Bayes:

When the predictors take up a continuous value and are not discrete, we assume that these values are sampled from a gaussian distribution.

<img src="https://miro.medium.com/max/844/1*AYsUOvPkgxe3j1tEj2lQbg.gif">

<br>
Since the way the values are present in the dataset changes, the formula for conditional probability changes to,

