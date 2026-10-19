# Netflix Data Analysis Using Python Internship

**Intern:** Yash Lawaniya  
**Internship Period:** 29 September 2026 – 29 October 2026  
**Mode:** Remote / Flexible Working Hours

## 1. Project Overview

This repository contains the work completed for the Data Analysis Using Python internship at Auspify Technologies. The project focuses on analyzing a Netflix titles dataset using Python, Pandas, and data visualization libraries.

The internship task guide contains six tasks, of which interns are required to complete any four. This project includes analysis and reporting work across the assigned tasks, with the final deliverables subject to verification.

## 2. Project Objectives

- Clean and prepare the Netflix dataset for analysis.
- Explore content types, release-year trends, countries, ratings, and genres.
- Create meaningful charts and visualizations.
- Identify patterns and develop data-driven business insights.
- Document findings, limitations, and recommendations.

## 3. Internship Task List

1. **Task 1 — Netflix Data Cleaning & Preparation** (Easy)
2. **Task 2 — Content Type Analysis Dashboard** (Easy)
3. **Task 3 — Country-Wise Netflix Content Analysis** (Medium)
4. **Task 4 — Trend Analysis by Release Year** (Medium)
5. **Task 5 — Content Rating & Genre Analysis** (Advanced)
6. **Task 6 — Netflix Business Insights Report** (Advanced)

The project has focused on Tasks 2–6. Task-level completion and deliverables should be confirmed against the notebooks, exported charts, and submission checklist.

## 4. Repository Structure

```text
Auspfiy_Data_Analysis_Using_Python/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── docs/
│
├── notebooks/
│   ├── task_01_data_cleaning/
│   ├── task_02_content_type_analysis/
│   ├── task_03_country_wise_analysis/
│   ├── task_04_release_year_trends/
│   ├── task_05_rating_genre_analysis/
│   └── task_06_business_insights/
│
├── reports/
│   └── figures/
│
├── screenshots/
│
├── src/
│
├── submission/
│   └── submission checklist.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

_Note: This structure describes the intended organization of the repository. Individual files and exported deliverables should be checked in their respective folders._

## 5. Dataset

The project uses a Netflix titles dataset containing information about movies and TV shows, including:

- Content type and title
- Director and country
- Date added and release year
- Content rating and duration
- Genres or categories

The cleaned dataset is intended to be stored in `data/processed/`. The original input dataset should remain unchanged in `data/raw/`.

## 6. Tools and Technologies

- **Python** — data analysis and processing
- **Pandas** — data cleaning, manipulation, and aggregation
- **NumPy** — numerical operations where required
- **Matplotlib** — static charts and visualizations
- **Seaborn** — statistical visualization where required
- **Plotly** — interactive visualizations
- **Jupyter Notebook** — analysis notebooks
- **Git and GitHub** — version control and repository management

## 7. Analysis and Key Findings

The analysis explored content distribution, country-wise counts, release-year trends, ratings, and genres.

Key results from the current analysis include:

- **Content type:** 6,126 movies (69.69%) and 2,664 TV shows (30.31%) among 8,790 records.
- **Release-year trend:** 2018 had the highest record count in the analyzed release-year distribution, with 1,146 titles.
- **Content ratings:** TV-MA and TV-14 were the most frequent rating categories.
- **Genres:** International Movies, Dramas, and Comedies were among the most frequent categories.
- **Country-wise analysis:** The United States and India were among the leading countries by recorded content count.

These findings describe the dataset's catalog distribution. They should not be interpreted as direct measures of viewership, revenue, or audience preferences.

## 8. Visualizations and Deliverables

The project includes or is intended to include the following deliverables:

- Content type bar chart and pie chart
- Country-wise content ranking chart
- Release-year trend chart
- Rating distribution chart
- Top genres chart
- Rating comparison by content type
- Interactive rating visualization
- Combined Netflix business insights dashboard
- Jupyter notebooks containing analysis and code
- Screenshots documenting completed tasks
- Written findings and final analytical report

Exported chart images are organized in `reports/figures/` and/or their relevant task folders, depending on the existing project organization.

## 9. How to Run the Project

1. Open the repository folder in Visual Studio Code.
2. Install Python and the VS Code Python and Jupyter extensions.
3. Open a terminal in the project root.
4. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

5. Open the relevant task notebook inside `notebooks/`.
6. Confirm that the dataset paths match the actual files in `data/raw/` or `data/processed/`.
7. Select the correct Python kernel.
8. Run the notebook cells from top to bottom.

## 10. Data Limitations

- Catalog counts do not represent actual viewing figures, revenue, or audience engagement.
- Genre counts may overlap because a title can belong to multiple categories.
- Country analysis may be affected by missing or unavailable country information.
- Release-year patterns describe the dataset's recorded titles and do not necessarily reflect the dates when titles were added to Netflix.
- Findings depend on the completeness and consistency of the available dataset.

## 11. Conclusion

This project applies Python-based data analysis and visualization techniques to explore Netflix's content catalog. The work demonstrates data exploration, aggregation, visualization, and business insight generation.

The analysis provides a starting point for further investigation. Additional viewership, engagement, and revenue data would be needed to draw stronger conclusions about content performance and audience behavior.

## 12. Submission Status

The repository is being prepared for final internship submission. Before submission, the notebooks should be executed from top to bottom, required screenshots and deliverables should be verified, and the submission checklist should be completed.

**Internship Deadline:** 29 October 2026
