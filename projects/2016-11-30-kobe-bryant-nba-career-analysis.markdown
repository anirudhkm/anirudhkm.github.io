---
layout: post
title:  Kobe Bryant's NBA career analysis
date:   2016-11-30 10:20:05
categories: projects
author: Anirudh K Muralidhar
---

{% include image.html url="/images/projects/nba analysis/kobe.jpg" caption = "Kobe Bryant from NBA. Image taken from Google images" width=350 align="right" %}

### SUMMARY

The crux of this project is to analyze the hit and miss performance of [NBA](https://www.nba.com) players based on the given player's data. For this project we have the data for [Kobe Bryant](https://en.wikipedia.org/wiki/Kobe_Bryant). Since, it is a sports doamin we want to convey our analysis through visualizations and finally develop a prediction model.

By doing such analysis we will be able to compare players's performance which can help the team management. For this project, we just perform analysis for one player alone.

### MOTIVATION

Usage of data analytics in sports domain is increasing manifold, especially with the increase in franchise based tournaments. It is a well known fact that baseball teams uses intense data analysis to benefit them in all possible ways. Basketball also has started to make use of these tools available. This is why we picked baseketvball.

Also, conveying analytical results through quality visualization takes high importance in sports domain. This is why all of analytical tasks are supported with visualizations. 

### DATASET

The dataset has been obtained from Kaggle where it was originally sourced from stats.nba.com.

[Click here to move to dataset](https://www.kaggle.com/c/kobe-bryant-shot-selection)

### METHODS

We have justified on our stand on the type of visualization we choose for each analysis that we have done. Also, there are few interactive visualizations done which serves more purpose.

{% include image.html url="/images/projects/nba analysis/viz.jpg" caption = "On court visualizations from our results" width=1000 align="center" %}

The prediction model that we developed using XGBoost algorithm to predict if Kobe will make or miss a shot gave the following results.

| **Metrics**   | **Score**   |
|:-------------:|:-----------:|
|Accuracy       |68.28%       |
|Precision      |0.69         |
|Recall         |0.68         |

### RESULTS

[Click here to download report](https://github.com/anirudhkm/Kobe-s-NBA-career-analysis/blob/master/FinalReport.pdf) in order to see the complete set of results and analysis.

[Click here to download the codes](https://github.com/anirudhkm/Kobe-s-NBA-career-analysis)

Download all the code files and run the index.html file in order to experience all the visualizations.