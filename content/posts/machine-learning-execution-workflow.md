+++
title = 'Machine Learning Execution Workflow'
date = 2024-08-02T11:53:09+05:30
draft = false
series = 'Artificial Intelligence and Machine Learning'
tags = ['AI', 'ML', 'Artificial Intelligence', 'Machine Learning', 'ML Workflow']
+++

In the last blog we tried to understand [what is Machine learning]({{< ref "posts/what-is-machine-learning.md">}}). Today we will look at how a typical workflow in applied AI/ML looks like. A typical workflow in applied Machine Learning can be broken down into following high-level steps:
- Problem Statement
- Data Collection
- Data Pre-processing
- Data Analysis & Modelling
- Evaluation

Let's look at each workflow item in a bit more detail.

## Problem Statement
Definition of a clear and concise problem statement is essential to ensure solution is focused towards solving the identified problem. It is paramount to ask questions to understand the problem being solved, some pointers for getting a desired problem statement:
- What are the required formats in which results are expected.
- Out of the 10 known problems being solved which ones are highest priority
- Can the implementation be done in a phased manner
- What will a most valued product (MVP) look like
- How the end result provide value to the user

## Data Collection
Data is attributed as the heart of any AI/ML solution, but I will go a step further and consider data as the 'blood' which flows through the veins of an AI/ML solution. Few questions to be considerd at this stage:
- What is/are the source(s) of data
- Is it public or private data source
- What is the quality of data
- Is it structured or unstructured data
- Can there be a need to generate data (may be applicable in certain situations)

## Data Pre-processing
This is an essential step as this is where steps are executed to get data to a certain quality for it is ready for consumption. Expected outcomes of this step is to:
- Removal of null values
- Identifying data elements which actually effect the outcome (for e.g. if a particular column has same value for all rows then its better to remove the column)
- Data Tranformation & data reduction
- Removing outliers

## Data Analysis & Modelling
This is where core of AI/ML execution happens and involves following:
- Supervised Learning
- Unsupervised Learning
- Applying ML algorithms
- Results in model inferred data

## Model Evaluation
This step helps in making the assessment of the model which suits our requirements and gives desired output. This involves:
- Model assessment
- Separate test and train sets
- Cross-validation
- Leave one-out cross-validation

A condensed synopsis is represented in the diagram below.

![Steps in machine learning execution workflow](/images/machine-learning-execution-workflow.png)