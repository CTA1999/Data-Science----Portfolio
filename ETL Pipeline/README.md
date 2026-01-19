# ETL Pipeline for Housing Data

This project implements an **end-to-end ETL (Extract, Transform, Load) pipeline** to prepare raw housing data for machine learning modeling. The pipeline ensures data quality, consistency, and reproducibility by systematically handling missing values, feature encoding, and scaling.

---

## Overview

The ETL pipeline follows these steps:

1. **Extract** – Load raw datasets and separate target variable.
2. **Transform** – Handle missing values, encode categorical features, and scale numerical features.
3. **Load** – Output a clean, model-ready feature matrix for downstream ML tasks.
