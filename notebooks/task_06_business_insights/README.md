# Task 6 — Netflix Business Insights Report

## Overview

This project analyzes the Netflix catalog using Python to identify content distribution patterns, release-year trends, ratings, and genres. It combines exploratory data analysis, visualizations, and business insights into a final analytical report.

## Objectives

- Perform exploratory data analysis (EDA).
- Identify content trends and patterns.
- Create a multi-chart business insights dashboard.
- Develop data-driven business recommendations.
- Present the findings in a final analytical report.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset Summary

- Total records: 8,790
- Total columns: 12
- Missing values in the cleaned dataset: 0
- Exact duplicate rows: 0

## Key Findings

- Movies: 6,126 records (69.69%).
- TV Shows: 2,664 records (30.31%).
- Leading country in the current dataset: United States (3,240 records).
- Most common rating: TV-MA (3,205 records).
- Most common genre/category: International Movies (2,752 records).
- Highest release-year count: 2018 (1,146 records).

## Dashboard

The dashboard combines four visualizations:

1. Content Type Distribution
2. Content by Release Year
3. Top 5 Ratings
4. Top 5 Genres

### Dashboard File

`netflix_business_dashboard.png`

## Business Insights

- Movies make up approximately 70% of the records.
- TV-MA and TV-14 are the most frequent ratings.
- International Movies, Dramas, and Comedies are the most frequent genre categories.
- Release-year counts peak in 2018 and decline in the dataset through 2021.

## Recommendations

- Examine the balance between Movies and TV Shows when reviewing catalog composition.
- Explore geographic representation and genre distribution.
- Investigate release-year patterns before drawing conclusions about production or acquisition strategy.
- Combine catalog analysis with viewership, revenue, and audience research before making investment decisions.

## Limitations

This analysis measures catalog records rather than viewership, revenue, or audience preferences. Genre counts may overlap because titles can belong to multiple categories. Country counts may be affected by missing or transformed country information.

## Deliverables

- Completed Jupyter Notebook
- `netflix_business_dashboard.png`
- Final analytical report and business insights

## Status

Analysis and report drafted; final file verification pending.
