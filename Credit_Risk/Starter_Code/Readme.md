# Credit Risk Classification

## Overview of the Analysis

The main objective of this analysis is to develop and assess a predictive model for evaluating the creditworthiness of borrowers within the context of a peer-to-peer lending services firm. To achieve this goal, we will utilize a historical dataset of lending activities and employ various machine learning techniques.

## Results

**Machine Learning Model 1:**

- Accuracy: 18679 true positives and 558 true negatives.
- Precision: Better for healthy loans (precision 1) than high-risk loans (precision 0.87).
- Recall: Better for healthy loans (recall 1) than high-risk loans (recall 0.89).
- Support: Imbalanced data (healthy loans 18759 vs. high-risk loans 625).

**Machine Learning Model 2:**

- Accuracy: 55945 true positives and 55954 true negatives.
- Precision: Equally good for healthy and high-risk loans (precision 0.99).
- Recall: Equally good for healthy and high-risk loans (recall 0.99).
- Support: Balanced data (healthy loans 56277 vs. high-risk loans 56277).

## Summary

I recommend using 'Machine Learning Model 2' due to its balanced scores, high Accuracy, Precision, and Recall for both healthy and high-risk loans. After resampling, 'Machine Learning Model 2' outperforms 'Machine Learning Model 1' with more data points, making it more suitable for loan risk prediction and classification as healthy or high-risk loans.
