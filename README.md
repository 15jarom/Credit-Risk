# Credit Risk Analysis Report

## Overview of the Analysis

Credit risk poses a classification problem that’s inherently imbalanced. The reason is that healthy loans easily outnumber risky loans. For this analysis, we use various techniques to train and evaluate models with imbalanced classes. Our dataset includes historical lending activity from a peer-to-peer lending services company that we used to build two models that can identify the creditworthiness of borrowers.

The main components of the data used are: Loan size, Interest rate (%), Borrower Income, Debt to income ratio, and Total Debt.
Our prediction will be whether or not the borrower is going to default, with a binary (Yes or No) decision. 

## Results

Our main model is Logistic Regression, which was chosen because it gives a good output for Yes or No answers based on independent variables. We started with the standard algorithm and raw data, which yielded a model with a 94.4% accurate output. While good, we wanted more.

Next we addressed the imbalance in the data that was mentioned at the beginning of the report by oversampling our defaulted borrowers so we would have more to go off of while running the algorithm. 
This resulted in an astounding 99.6% accuracy!

## Summary

Out of the total 19384 borrowers that we tested the model against, out second model correctly identified 19291 correct (that was the 99.59%), but 91 (0.4%) were identified as people who would default but ended up not doing so. 
So that leaves only 2/19384 (0.01%) that were missed, resulting in a very precise mechanism for predicting risk.

Any company that is looking to implement a screening for poential borrowers could use this model to great effect! 

