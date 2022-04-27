# Reproducibility Project for CS598 DL4H : Readmission prediction via deep contextual embedding of clinical concepts

This repository contains Jupyter notebooks replicating study described in thearticle "Readmission prediction via deep contextual embedding of clinical concepts" published in PLoS ONE 2018


## Preprocess.ipynb

Preprocessing of the EHR data that produces data andlabel files in a form:

- Data
-- foreach patient
--- list of visits
---- list of diagnosis ICD9 codes
- Label
-- for each patient
--- list of visit readmission label
