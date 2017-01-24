---
layout: post
title:  Analysis of baseball data for performance measure and prediction
date:   2015-11-30 10:20:05
categories: projects
author: Anirudh K Muralidhar
---

### **SUMMARY**

The idea of this project is to analyze the Lahman's baseball dataset to understand the performance of a team and to see their performance trend.

{% include image.html url="/images/projects/doc_comparison/flow.png" caption = "Comparison of algorithms with F-1 measure." width=300 align="left" %}

### **MOTIVATION**

Sabermetrics is the analysis of baseball data and it's usage has increased manifold in recent years. With this we analyze the performance of team and players based on several metrics and produce results and inferences.

### **DATASET**

For these analysis we primarily use [Lahman's database](http://www.seanlahman.com/baseball-archive/statistics/) and [retrosheet](http://www.retrosheet.org/) which gives in detail match by match data.

### **METRICS**

In order to measure the performance of a player have used metrics such as At Bats, Hits, Batting average, On Base Percentage and more.

Similarly, we have pitching metrics such as Earned Run, Opposition Batting Average, Save, Wins and more.

With these metrics we compare players performance in order to pick the best and extend this to the performance of a team as well.

### **RESULTS**

[Click here to download report](https://github.com/anirudhkm/sabermetrics-I590/blob/master/report.pdf) for the complete comparison of players and teams and the inferences derived.

[Click here to move to code repository](https://github.com/anirudhkm/sabermetrics-I590) which is written in R and Python for crawling data.