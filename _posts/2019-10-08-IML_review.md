---
layout: post
title: (JOV2019) Recent research advances on interactive machine learning
---

## Problem statment and background
Interactive machine learning (IML) is an iterative learning process that tightly couples a human with a machine learner, which is widely used by researchers and practitioners to effectively solve a wide variety of real-world application problems. Although recent years have witnessed the proliferation of IML in the field of visual analytics, most recent surveys either focus on a specific area of IML or aim to summarize a visualization field that is too generic for IML. In this paper, recent literatures on IML are systematically reviewed and classified into a task-oriented taxonomy.

## Methods
Existing works on IML are reviewed from the visual analytics community, where interactive visualizations empower users to iteratively steer machine learning models. Related papers from 2015 to 2018 are selected from the following journals or conferences:
* IEEE TVCG
* IEEE VAST
* IEEE InfoVis
* EuroVis
* IEEE PacificVis. 
Titles and abstracts of the papers are exhaustively checked to find candidates. Then, full texts of uncertain candidates are browsed to finalize the selection. As a result, a total of 99 papers are selected for review.

The task-oriented taxonomy is shown below.
![_config.yml]({{ site.baseurl }}/images/IML.PNG)

## Evaluation
The neural network consistently outperforms the baseline models and model performance generally progresses as NB< KNN < LR ≈ RF < NN.

Benchmarking with crowdsourced effectiveness

![_config.yml]({{ site.baseurl }}/images/VizML2.png)

This review focuses on tasks less covered by the existing surveys, including visual pattern mining, interactive anomaly detection, interactive information retrieval, and visual topic analysis.

## Research challenges and opportunities
Major research challenges, which may pave the way for further research opportunities, include
### Wide and easy adoption of machine learning techniques
### Scalability
### Explainability for data scientists and practitioners
### Monitoring and debugging the online training/testing process of machine learning models
### Improving data quality
