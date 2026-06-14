# Retail-Credit-Risk-Modeling-Probability-of-Default-PD-Estimation-and-Borrower-Risk-Analytics

Overview

This project develops a Probability of Default (PD) model to assess the likelihood of borrower default using demographic, financial, and loan-level information.

The objective is to support credit risk assessment by identifying high-risk borrowers, improving default detection, and understanding the major factors driving credit risk.

Business Problem

Financial institutions need to evaluate borrower creditworthiness before loan approval to reduce default losses and improve portfolio quality.

This project aims to:

1. Estimate borrower default probability
2. Identify key risk drivers
3. Improve borrower risk classification
4. Support better credit underwriting decisions
5. Monitor model stability using PSI

Project Flow
1. Data Preprocessing
Missing value treatment
Outlier handling using IQR capping
Multicollinearity check using VIF
Feature standardization

3. Borrower Risk Profiling

Exploratory analysis to understand default behavior across borrower segments.

3. PD Model Development

Built a logistic regression model to estimate:

PD=P(Default=1∣X)

4. Model Evaluation

Performance measured using:

ROC-AUC
Gini Coefficient
KS Statistic
Calibration Curve

5. Threshold Optimization

Optimized the decision threshold using KS-maximization for better default capture.

6. Risk Driver Analysis

Interpreted borrower risk factors using standardized odds ratios.

7. Stability Monitoring

Measured model stability using Population Stability Index (PSI).

Key Insights:

1. Borrowers with higher loan burden relative to income showed significantly higher default risk.
2. Lower loan grades were strong indicators of elevated credit risk.
3. Borrowers living in rented accommodation exhibited higher default propensity compared to homeowners.
4. Threshold optimization improved default detection from 54% to 70%, increasing risk capture.
5. Model remained stable with minimal population drift
