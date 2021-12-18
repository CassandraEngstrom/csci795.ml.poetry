# Insights from machine classification, clustering, and generation of poetry 
Seminar in Machine Learning CSCI 795 - Fall 2021 - Professor Anita Raja - Hunter College

Written in Python3/numpy/pandas/scikit-learn

## DATASET: 
poems.csv 

## FILE 1: Engstrom.Poetry_Classification_Clustering_NetworkVisualization

* Part one: vectorization of poetry samples 
* Part two: classification of poetry based on era, author, and subject (using KNN, gNB, RF, SVM, MLR)
* Part three: unsupervised clustering of samples (using KM, SC, DBSCAN)
* Part four: create similarity matrix comparing each sample; convert poetry samples into graph using jaccard distances; visualize network

## FILE 2: Engstrom.CharacterBasedRNN_PoetryGeneration

NOTE: each model set to be trained on 112500 iterations (modify this in while loop)

* Part one: defining fxns, hyperparameters
* Part two: training model with Adagrad
* Part three: training model with Adam
* Part four: training model with AMSGrad 
* Part five: plotting loss for each optimization algorithm 

