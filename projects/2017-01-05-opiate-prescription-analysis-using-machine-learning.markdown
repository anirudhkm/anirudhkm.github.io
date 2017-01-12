---
layout: post
title:  Opiate/Opioid prescription analysis using machine learning
date:   2017-01-05 10:20:05
categories: projects
author: Anirudh K Muralidhar
---

{% include image.html url="/images/projects/opiate/usa.png" width=300 align="right" %}

### SUMMARY

The whole idea of this project is to develop a prediction model to predict if a given doctor is an opiate prescriber or not based on their non-opiate drug prescription pattern. Also, we find the top ten features that influences the prediction.

### MOTIVATION

Machine learning in medical domain has played a pivotal role and its usage seems to increase manifold. This is the reason behind our interest to work on medical data.

From the data it is evident that the number of opiate causalities is quite alarming. Center for Disease and Control and Prevention (CDC) states that over 28000 people died because of opiate overdose in the year 2014. This trend continues and requires high attention, several researches are looking for solutions on this and we would like to see how Machine Learning can help in providing a possible solution.

### DATASET

The dataset has been obtained from Kaggle where it was originally sourced from cms.gov. We have 25,000 data points for our analysis.
[Click here to move to dataset](https://www.kaggle.com/apryor6/us-opiate-prescriptions)

### ALGORITHMS

1. Decision tree.
2. Decision tree with bagging and boosting wrapper.
3. Logistic regression.

These are the algorithms that are implemented and the results are compared.

### RESULTS

Comparison of all the above algorithms are done and the results are published in the paper below.
[Click here to download the paper](https://drive.google.com/open?id=0B9nEIkjMSZbjWEh1MzYySjRNbmM)