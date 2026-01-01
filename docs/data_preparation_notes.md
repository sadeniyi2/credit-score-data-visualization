# Data Preparation Notes

This document outlines the preprocessing steps applied before performing
data visualization and exploratory analysis.

---

## Column Standardization
All column names were converted to lowercase and spaces were replaced with
underscores to maintain consistency.

---

## Text Cleaning
Categorical string columns were cleaned by trimming leading and trailing
whitespace to avoid inconsistencies during analysis.

---

## Duplicate Removal
Duplicate rows were identified and removed to prevent biased visual results.

---

## Numeric Conversion
Relevant numeric columns were explicitly converted to numeric data types.
Invalid values were coerced into missing values.

---

## Missing Data Inspection
The dataset was checked for missing values across all columns to assess
overall data quality before visualization.

---

## Clean Data Export
After preprocessing, the cleaned dataset was exported as a CSV file to
ensure reproducibility and reuse.
