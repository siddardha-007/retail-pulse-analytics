# Online Retail Data Analysis

## Project Overview

An end-to-end data analysis project using Python and Pandas to explore the UCI Online Retail II dataset. The project examines transaction quality, sales performance, product trends, country-level performance, and customer purchasing behavior.

## Objectives

- Load and inspect a large retail dataset.
- Identify missing values, duplicate records, and unusual transactions.
- Develop transparent data-cleaning rules.
- Calculate sales metrics and analyze trends over time.
- Identify high-performing products and countries.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Communicate findings through visualizations and business recommendations.

## Technology Stack

- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- Seaborn

## Project Structure

- `data/`: Raw and processed datasets
- `notebooks/`: Loading, cleaning, feature engineering, and analysis
- `outputs/figures/`: Generated visualizations
- `outputs/reports/`: Final analysis reports

## Dataset

UCI Online Retail II dataset.

Source: https://archive.ics.uci.edu/dataset/502/online+retail+ii

The dataset contains retail transactions spanning December 2009 to December 2011.

## Current Progress

- Loaded and combined the Excel sheets.
- Inspected data types and missing values.
- Removed exact duplicate rows from the working dataset.
- Investigated negative quantities, zero prices, and cancellation-style invoice numbers.
- Created transaction flags and an initial positive-value sales dataset.
- Validated the initial sales metrics.

## Data Handling Notes

Exact duplicate rows were removed from the working dataset. Transaction exclusions are being evaluated separately so that cancellations, returns, and accounting adjustments are not silently treated as invalid records.

## Future Work

- Feature engineering and monthly sales trends
- Product and country performance analysis
- Customer RFM segmentation
- Visualizations and business recommendations
