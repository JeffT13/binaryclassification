# binaryclassification

This is a project done for DS-GA 1001 on the MAGIC Telescopic Dataset

Collaborators: Jeffrey Tumminia

Goal: Build a c;assifier for identifying gamma rays from noisy simulated data.

Learning Objective: Compare and constrast different supervised classification algorithms in effectiveness and efficiency.

Challenges:

- Difficult classification dataset
- Low computational capacity
- Limited subject matter knowledge in feature analysis

Procedure:

#### DataView

1) process csv dataset, create stratified training/val/test sets 

#### FeatureAnalysis

2) Compare relevance and information gain of features using DT, Univariate ROC and Correlation Matrix

#### FeatureEngineering

3) Build non-linear combinations of features and perform feature analysis on new features

#### Baseline Models

4) Build DT, DF, LR , SVM, Grad Boost and KNN Models as baselines for comparison

#### CrossVal & Parameter Tuning

5) Perform XVal tuning for DT, RF, and LR

#### Tuned+Voter

6) Show performace of tuned DT and LR + Build a voting classifier to improve overall classification.


See paper for more details: 