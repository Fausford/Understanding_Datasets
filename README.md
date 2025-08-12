# Understanding Datasets

## Overview

This analysis explores a synthetic medical dataset to understand its structure, contents, and data quality. The examination focuses on basic characteristics and missing data patterns.

## Dataset Characteristics

### Basic Structure

Initial steps observed the dataset dimensions: The dataset contains X rows (observations) and Y columns (variables)

Column names were obsered using a function to list main column categories

Variable types includes both numerical and categorical variables

### Data Quality Assessment

The analysis later focused on missing Values. We examined missing data using multiple approaches:

1. Column-wise missing value counts

2. Summary statistics showing NA distributions

3. Comprehensive missing data profiling

Notes: This were done without using missing data packages. We will cover them in subsequent lessons

## Statistical Summary

Key descriptive statistics for all variables including:

1. Central tendency measures (mean, median)

2. Dispersion metrics (standard deviation, range)

3. Distribution characteristics (skewness, kurtosis)

# Analysis Components

Initial Data Inspection

-Verified successful data loading

-Checked variable names and types

-Missing Data Evaluation

-Quantified missing values per variable

-Assessed patterns of missingness

-Descriptive Statistics

-Generated comprehensive numerical summaries

-Calculated distribution metrics

-Data Cleaning(partial)

-Applied basic missing data handling

-Verified cleaning results

# Usage Notes

The analysis uses standard R packages (tidyverse, skimr, psych)

All operations are reproducible with the provided code

Dataset should be placed in **appropriate** path before running