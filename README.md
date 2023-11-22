# Liver Cirrhosis Patient Survival Prediction
DS6040 Bayesian Machine Learning - Final Project

## Motivation
Liver cirrhosis is a life-threatening condition that affects millions of
individuals worldwide, presenting a significant public health challenge. This chronic
liver disease is characterized by the progressive scarring of the liver tissue, which
ultimately leads to liver failure if left untreated. Among the critical aspects of liver
cirrhosis is the unpredictability of patient survival, which depends on a myriad of
factors, including disease severity, comorbidities, treatment regimens, and individual
patient characteristics.

## Goals
Our goals for this project are to
1) The primary objective of this project is to create a robust survival classification
model for liver cirrhosis patients. We aim to categorize patients’ survival status
into distinct survival groups: C(censored), CL(censored due to liver tx), and
D(death).
2) Evaluate the posterior probability distributions of the regression parameters
for the predictor variables obtained from a Mayo Clinic study on primary biliary
cirrhosis (PBC) of the liver carried out from 1974 to 1984.
3) Evaluate the model predictions and the uncertainties in these predictions.

## Data 
The data are from Kaggle. There are 1 response variable, and 19 predictor
variables originally, some of which might be dropped depending on their relevance to
our analysis.
https://www.kaggle.com/datasets/joebeachcapital/cirrhosis-patient-survival-prediction

## Approach
We propose to use robust Bayesian Regression with HMC sampling and
will evaluate
1) the prediction of response - the survival status of a patient.
2) Handle missing data in the dataset.
3) the choice of priors and sampling.
4) Build another model and evaluate the models using mean squared error
analysis.
