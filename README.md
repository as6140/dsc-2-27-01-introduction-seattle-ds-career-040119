
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 27 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Distance Metrics and k-Nearest Neighbors

k-Nearest Neighbors (kNN) is a very powerful machine learning technique, but to be able to define "nearest" we need to start by digging into some of the most common distance metrics used in machine learning.

### Distance Metrics

There are a range of ways of calculating the distance between points in an n-dimensional space. We kick off the section by introducing three ways of calculating the distance between points - Manhattan, Euclidean and (the more generalized) Minkowski distance. 

### k-Nearest Neighbors

Once we have a way to calculate distance betweeen points, now we can start to use k-Nearest Neighbors (kNN) to predict values - whether for regression (pick the average of the neighboring values) or classification (pick the most popular category of the neighbors). We introduce the concept of kNN and then help you to write a kNN classifier from scratch.

### Confusion Matrices

For classifiers, confusion matrices can be a powerful tool for evaluating model performance - especially in cases where false positives have a different impact than false negatives (detecting cancer, providing credit, etc). In this lesson we run you through the construction of confusion matrices for both binary and multi-categorical classifiers.

### Evaluation Metrics

In the next lesson, we then provide an overview of a range of evaluation metrics that can be used for classifiers such as precision and recall, accuracy and F1-score, and how to think about the right evaluation metrics to use for a given class of problem.

### Finding the Best Value for k

Earlier in the section, we introduced the use of kNN for classification (and regression), but we didn't spend a lot of time thinking about how to optimize k (should it be the nearest 2 points? the nearest 200?). In this lesson we show how selection of k can impact over/underfitting and how to plot results for a range of values of k and pick the optimal value for a given problem and data set.

### kNN with Scikit-learn

After introducing the key elements of kNN, we then take some time to run your through the usage of the optimized kNN model built right into Scikit-learn.



## Summary

In this section, you'll learn how to build your first classifier using kNN and some of the evaluation metrics for determining optimal model fit for classifiers. You'll also learn about distance metrics that will come in handy later in the course when looking at a number of other machine learning techniques.

