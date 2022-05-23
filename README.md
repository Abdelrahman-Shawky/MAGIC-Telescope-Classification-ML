# MAGIC Gamma Telescope Classification ML
Training and test data obtained from UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/machine-learning-databases/magic/

## Problem Statement
Given the MAGIC gamma telescope dataset that is generated to simulate registration of high energy gamma particles in a ground-based atmospheric
Cherenkov gamma telescope using the imaging technique. The dataset consists of two
classes; gammas (signal) and hadrons (background). There are 12332 gamma events and 6688
hadron events.

## Objectives
- Exploring different classification models and performing tuning of their parameters.
- Exploring different techniques for evaluating classification models.

## Classification Algorithms
- Decision Tree
- AdaBoost
- Random Forests
- K-Nearest Neighor
- Naïve Bayes

## Requirements
1. Data Balancing 

    To balance the dataset, randomly put aside
  the extra readings for the gamma “g” class to make both classes equal in size.
  
2. Data Split

    Split dataset randomly so that the training set would form 70% of the dataset and
  the testing set would form 30% of it.
  
3. Classification

    Classify dataset according to given algorithms.
4. Model Parameter Tuning 

    Cross-validation to tune the parameters of classifiers. Test the models trained with
  best obtained parameter values on separate testing set.
 
## Conclusions
- Random Forests:
  - Best Performance
  - Takes Advantage of Several Decision Trees
  - Maintains a Good Fitting Model
  - Increased Computation
- AdaBoost:
  - Simpler Implementation
  - Faster Computation
  - Uses Weak Learners (Decision Stumps)
  - Could 
- Decision Tree:
  - Base for Random Forests
  - Lower Scores
  - Prone to Overfiitting
  - Requires Pruning
- KNN:
  - Lazy Learner
  - Requires Tuning
  - Relatively Low Scores
- Naïve Bayes:
  - Lowest Performance
  - Probability Based
  - Simple Intuition     
