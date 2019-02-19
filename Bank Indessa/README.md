# Bank Indessa from Hackerearth Machine Learning Challenge #1

## Problem Statement

The Bank Indessa has not done well in last 3 quarters. Their NPAs (Non Performing Assets) have reached all time high. It is starting to lose confidence of its investors. As a result, it’s stock has fallen by 20% in the previous quarter alone.

After careful analysis, it was found that the majority of NPA was contributed by loan defaulters. With the messy data collected over all the years, this bank has decided to use machine learning to figure out a way to find these defaulters and devise a plan to reduce them.

This bank uses a pool of investors to sanction their loans. For example: If any customer has applied for a loan of $20000, along with bank, the investors perform a due diligence on the requested loan application. Keep this in mind while understanding data.

In this challenge, you will help this bank by predicting the probability that a member will default.

Competition Link: https://www.hackerearth.com/challenges/competitive/machine-learning-challenge-one/

## My Solution

After feature engineering, I used Random Forest Classifier, K Nearest Neighbours, SGD Classifier, AdaBoost Classifier, Bagging Classifier, ExtraTree Classifier, GradientBoosting Classifier, Ridge Classifier and Passive AggressiveClassifier. All of them are from scikit-learn package. Then, I used a neural network to ensemble prediction from these 9 models.

You can checkout one of the main file at [4. Ensemble Models+Feature Engineering.ipynb](https://github.com/jincongho/Competitive-Machine-Learning/tree/master/Bank%20Indessa/4.%20Ensemble%20Models%20%2B%20Feature%20Engineering.ipynb) and ensemble at [5. Ensemble with ANN.ipynb](https://github.com/jincongho/Competitive-Machine-Learning/tree/master/Bank%20Indessa/5.%20Ensemble%20with%20ANN.ipynb).

## Performance

I was ranked 97 out of 3367 contestant (top 3%). 

![Image of Ranking](https://github.com/jincongho/Competitive-Machine-Learning/raw/master/Bank%20Indessa/rank.png)