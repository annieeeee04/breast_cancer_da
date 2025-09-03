# Breast Cancer Data Analysis
## Overview

This project explores diagnostic breast cancer data to identify key tumor features that distinguish malignant from benign cases. Using statistical analysis and visualization in R, it highlights the strong predictive power of tumor size metrics in cancer diagnosis.

## Methods

* Data Exploration: Summarized tumor size (radius, area, perimeter) across diagnosis groups.

* Correlation Analysis: Generated full correlation matrices and heatmaps to reveal feature relationships.

* Group Comparison: Compared malignant vs. benign correlations and distributions.

## Statistical Testing:

* Pearson correlation between tumor size and diagnosis (r ≈ 0.73).

* Welch’s t-test confirming significant mean size differences (p < 2.2e-16).

## Key Findings

* Malignant tumors have significantly larger mean radius (≈17.5) than benign tumors (≈12.1).

* Tumor radius, area, and perimeter are highly correlated with malignancy.

* Correlation structures differ between malignant and benign groups, suggesting unique tumor morphology patterns.

## Tools

R: dplyr, ggplot2, corrplot

Techniques: Correlation analysis, hypothesis testing, data visualization

Impact

The results confirm that tumor morphology metrics are strong predictors of malignancy, providing a foundation for future predictive modeling and early cancer detection research.
