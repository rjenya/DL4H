# Reproducibility Project for CS598 DL4H : Readmission prediction via deep contextual embedding of clinical concepts

This repository contains Jupyter notebooks replicating study described in thearticle "Readmission prediction via deep contextual embedding of clinical concepts" published in PLoS ONE 2018


## Preprocess.ipynb

Preprocessing of the EHR data that produces data andlabel files in a form:

- Data
  - foreach patient
    - list of visits
      - list of diagnosis ICD9 codes
- Label
  - for each patient
    - list of visit readmission labels

## CONTENT.ipynb

Replication of the model implementation. The goal of the replicated deep neural network model is to predict hospital readmission risk based on EHR data. 

## Baseline_GRU.ipynb

Baseline readmission prediction model. Uses vanilla GRU deep neural network model with one-hot embedding.

## Baseline_EmbGRU.ipynb

Baseline readmission prediction model. Uses bi-derectional GRU deep neural network model with preceding embedding layer.

## Baseline_RETAIN.ipynb

Baseline readmission prediction model. Uses RETAIN deep neural network model - RNN model with attention mechanism

## Baseline_Word2VecLR.ipynb

Baseline readmission prediction model. Uses Word2Vec model to create visit embeddings with following LogisticRegression for readmission prediction.
