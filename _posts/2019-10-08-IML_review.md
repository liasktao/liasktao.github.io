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

## Research challenges and opportunities
Major research challenges, which may pave the way for further research opportunities, include
### Wide and easy adoption of machine learning techniques
Leverage interactive visualization to
1. achieve interactive model recommendation, which is to select the appropriate learning models for a given task and requirement
2. systematically explore the multi-dimensional parameter space to greatly reduce the search space of model parameters
### Scalability
Visualizing models with complex structures and large numbers of components is challenging, especially when the models handle tens of thousands of data items (for instance, ResNet-101 with a training dataset of millions of images). It is usually difficult to develop an appropriate visual summarization or abstraction to support model analysis and prediction understanding tasks. Accordingly, visualization researchers desire to design and develop scalable visualizations to simultaneously convey the model structure, prediction results, and the raw data, as well as to link them together, for a comprehensive analysis of the learning process and results.
### Explainability for data scientists and practitioners
Trade-off exists between predictive performance and explainability of models. One interesting venue is to study how to leverage the self-explainable machine learning models such as decision trees to illustrate the working mechanism and predictions of the ensemble models. This enables the practitioners to better understand the model predictions and select the appropriate models
and parameters for their tasks.
### Monitoring and debugging the online training/testing process of machine learning models
In real-world applications, the training process of many machine learning models is very time-consuming, which can sometimes take up from hours to days. Thus, it is desired to monitor the online training process and find the potential issue(s) that may lead to an unsatisfactory training process. One possible solution is to leverage progressive visual analytics techniques to integrate experts into the analysis loop. To achieve this, machine learning models are expected to produce semantically meaningful partial results in the training/testing process. By leveraging interactive visualizations, experts explore and analyze the system generated partial results, compare newly incoming results with previous ones, as well as perform analysis without having to wait for the entire training process to be completed.
### Improving data quality
In ML, data and model are equally important. To improve data quality, it is necessary to leverage interactive visualization for better illustrating the data distribution, identifying potential errors, and minimizing the workload of domain experts who verify the data. For example, interactive visualization can be leveraged to tightly combine user-guided methods with system-guided methods during the verification process.
