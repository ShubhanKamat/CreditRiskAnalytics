# Credit Risk Analysis

This project is dedicated to creating a data-driven model in Python to estimate the likelihood of default (PD) and generate credit scores for current or prospective borrowers. The credit scores are produced using a transparent, easy-to-understand, and practical scorecard.

## Project Structure

- **Analysis.ipynb**: The Jupyter Notebook containing the full analysis, including data preprocessing, model development, and scorecard creation.

## Overview
- Developed a comprehensive credit risk model using logistic regression and feature engineering techniques to predict the probability of default for loans. Performed rigorous data cleaning, feature selection (using ANOVA and chi-square tests), and transformation (Weight of Evidence encoding).
- Achieved an impressive AUROC of 0.82 and Gini coefficient of 0.64 on the test set, outperforming the default threshold approach. Optimized the probability threshold using Youden's J-statistic, striking a balance between true positive and false positive rates.
- Constructed a robust credit scorecard by mapping model coefficients to a range of 300-850, aligning with industry-standard FICO scores.
- Implemented a custom scikit-learn transformer to automate the feature binning process, enabling efficient k-fold cross-validation. Analyzed acceptance and rejection rates across various score cut-offs, recommending an optimal threshold of 489 that maximized business acceptance while mitigating risk exposure.

## Dataset
- The dataset was sourced from : https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014/data

## Following resources are helpful in understanding the importance of WoE and IV used in the analysis
- https://www.researchgate.net/publication/309194526_Credit_Risk_Analytics_Measurement_Techniques_Applications_and_Examples_in_SAS
- https://www.wiley.com/en-us/Credit+Risk+Scorecards%3A+Developing+and+Implementing+Intelligent+Credit+Scoring-p-9781119201731






