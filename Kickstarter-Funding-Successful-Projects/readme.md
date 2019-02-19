# Funding Successful Project from Hackerearth Machine Learning Challenge #2

## Problem Statement


Kickstarter is a community of more than 10 million people comprising of creative, tech enthusiasts who help in bringing creative project to life. Till now, more than $3 billion dollars have been contributed by the members in fuelling creative projects. The projects can be literally anything – a device, a game, an app, a film etc.

Kickstarter works on all or nothing basis i.e if a project doesn’t meet it goal, the project owner gets nothing. For example: if a projects’s goal is $500. Even if it gets funded till $499, the project won’t be a success.

Recently, kickstarter released its public data repository to allow researchers and enthusiasts like us to help them solve a problem. Will a project get fully funded ?

In this challenge, you have to predict if a project will get successfully funded or not.

Competition Link: https://www.hackerearth.com/challenges/competitive/machine-learning-challenge-2/

## My Solution

I've done significant preprocessing and feature extraction in this project. Most importantly, I used Bag-of-words and also topic modelling to extract information from plain text, such as the description used in each project. Then, I train two models using XGBoost and LGB. Finally, ensemble them with simple average of predicted probability. Some challenges in this project includes, topic modelling and also using sparse data structure to represent bag-of-words.

## Performance

I was ranked 36 out of 4591 contestant (top 1%). 

![Image of Ranking](https://github.com/jincongho/Competitive-Machine-Learning/raw/master/Kickstarter-Funding-Successful-Projects/rank.png)