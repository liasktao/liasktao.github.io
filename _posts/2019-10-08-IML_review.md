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
* EuroVis,
* IEEE PacificVis. 
Titles and abstracts of the papers are exhaustively checked to find candidates. Then, full texts of uncertain candidates are browsed to finalize the selection. As a result, a total of 99 papers are selected for review.

![_config.yml]({{ site.baseurl }}/images/IML.png)

Models used in evaluation
* neural networks (primary)
* naive Bayes
* K-nearest neighbors
* logistic regression
* random forest
For all models, the data is split into 60/20/20 train/validation/test sets and 5-fold cross-validation is used.

Code and datasets used in the paper are available at: [https://github.com/mitmedialab/vizml](https://github.com/mitmedialab/vizml)

## Evaluation
The neural network consistently outperforms the baseline models and model performance generally progresses as NB< KNN < LR ≈ RF < NN.

Benchmarking with crowdsourced effectiveness

![_config.yml]({{ site.baseurl }}/images/VizML2.png)

## Discussion
Limitations:
* VizML is biased towards the Plotly dataset
* Plotly and crowdsource users are not experts in data visualization
* The paper was only focused on a subset of the tasks in a visualization recommendation pipeline

Future work:
* a need for more diverse training data from other tools (e.g., Many Eyes and Tableau)
* objective measures of visualization effectiveness

