# MachineLearningProject
# "Pizza Price Prediction using Machine Learning"
** A Machine Learning model  that predicts prices based on  Various Features **

# Definition:
Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.

The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly.

# How to use this repo:
This repo is just for the introduction to Machine Learning. This repo consists of Ipython notebooks which will help you to analyse that what is going on each step. Graphs are also there so that you can check the performance of the the algorithm that that has been discussed in the notebook

# Requirements:
Python 3.X
Anaconda
Note: Make sure the kernel of Ipython is installed for Python3

# Getting Started
To understand the basis of Machine Learning, we must understand that there are 4 simple steps involved in the process:

Train Data Set
Choosing the Algorithm
Applying ML algorithm to train the system
Test Data Set
# Aim: To predict the pizza price
Pre-requiste Knowledge
Price price follows a linear relationship with several parameters like diameter, quantity of cheese, veg or non veg, pizza toppings. Therefore Simple Linear Regression can be applied to estimate the price of the pizza.

Train Data Set: sample_data.csv containing columns like cost, diameter, toppings etc

# How It works
CSV file is read using pandas
Train Data is chosen
A modeler is generated using Linear Regression
Cost are predicted with the random pizza size
Linear Regression take two input parameters: X and y. X being the independent quantity and y being the dependent quantity because linear regression take the form of straight line whose equation is given by ``` y = mx+c ```, y=dependent, x=independent, m=slope of the line and c being the y-intercept.

In our pizza price prediction system X=['size','pizza toppings'..etc] and y=['cost']
