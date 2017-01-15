---
layout: post
title:  Performance comparison of various classification algorithms for text classification
date:   2016-04-30 10:20:05
categories: projects
author: Anirudh K Muralidhar
---

### **SUMMARY**

The outcome of this project is to compare the performance of various algorithms and evaluate its performance with and without cross validation.

### **MOTIVATION**

It's obvious that machine learning has scaled great heights, but still there is no concrete reasons why we should use a particular algorithm to a particular dataset.

We take motivation from this to compare the performance of several algorithm when applied on the same dataset which gives us a better understanding of how algorithm the behaves.

### **DATASET**

To serve the purpose, we opted the [twenty newsgroup](http://qwone.com/~jason/20Newsgroups/) dataset. The reason we chose text data is because we to see which algorithm works best with text.

### **ALGORITHMS**

Following are the algorithms that we exercised for this project

1. Decision tree.
2. Random Forest classifier.
3. Naive Bayes Classifier (Multinomial)
4. Logistic regression.
5. Support Vector Machines.

{% include image.html url="/images/projects/doc_comparison/algo_comp.png" caption = "Comparison of algorithms with F-1 measure." width=900 align="center" %}

### **RESULTS**

From the overall experiment we found that support vector machine proved to be the best algorithm for this dataset. One of the main reason why SVM has worked well is because of the sparse nature of the dataset.

[Click here to download the report](https://github.com/anirudhkm/data-mining-course/blob/master/project/report.pdf) which shows all the results and inferences.

[Click here to move to code repository](https://github.com/anirudhkm/data-mining-course/tree/master/project)