# CCDATSCL - Data Science and Analytics

## Table of Contents
- [CCDATSCL - Data Science and Analytics](#ccdatscl---data-science-and-analytics)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Course Description](#course-description)
    - [Course Objectives:](#course-objectives)
  - [Introduction](#introduction)
  - [Learning Outcomes](#learning-outcomes)
  - [Course Outline](#course-outline)
  - [Repository Structure](#repository-structure)
  - [Disclaimer / Acknowledgment](#disclaimer--acknowledgment)

## Overview
Data Science is an interdisciplinary field that uses scientific methods, algorithms, and systems to extract meaningful insights and knowledge from structured and unstructured data. This course offers a practical introduction to data science, covering its fundamental concepts, techniques, and tools. Data science is transforming industries such as healthcare, finance, technology, and more, making it essential for anyone interested in analytics, AI, or data-driven decision-making. By the end of this course, learners will understand how to apply data science techniques to solve real-world problems, from data preprocessing and exploratory analysis to statistical testing and predictive modeling.

## Course Description
This course is designed for individuals who are new to data science but have a basic understanding of programming and statistics. It provides both theoretical knowledge and practical skills, emphasizing hands-on experience with data manipulation, visualization, statistical analysis, and machine learning. Using Python and popular libraries like Pandas, matplotlib, seaborn, and scikit-learn, students will learn to work with real-world datasets and build analytical solutions.

### Course Objectives:
- **Master data manipulation**: Use Python and Pandas for data discovery, cleaning, and transformation.
- **Learn data visualization techniques**: Create meaningful visualizations using matplotlib and seaborn.
- **Explore statistical analysis**: Apply hypothesis testing, ANOVA, and correlation analysis.
- **Hands-on implementation**: Build end-to-end data science pipelines, from raw data ingestion to predictive modeling.

## Introduction
Data Science is fundamentally about extracting actionable knowledge from data through a combination of domain expertise, programming skills, and statistical reasoning. With the exponential growth of data across every industry, data science has become indispensable in transforming raw information into informed decisions.

From basic descriptive statistics to advanced machine learning models, the data science workflow follows a structured pipeline: data collection, cleaning, exploration, analysis, modeling, and interpretation. This course takes learners through each stage of this pipeline with practical exercises and a capstone project.

## Learning Outcomes
Upon completing this course, learners will be able to:
- Identify effective statistical analysis techniques to implement given particular demands of inference on available data.
- Prepare data for analysis, including data cleaning, manipulation and dealing with missing data
- Apply data manipulation, analysis and visualization using Python, R, and a variety of external libraries and packages for data science.

## Course Outline

| Topic | Course Materials | Description |
|---|---|---|
| **Data Discovery, Structuring, and Cleaning** | [Exercise 1](https://github.com/gabcsx/CCDATSCL/tree/main/Excercises/Exercise_1) | Working with the NYC Airbnb dataset to practice data discovery, structuring, cleaning, and exploratory analysis using Pandas. |
| **Exploratory Data Analysis (EDA)** | [Exercise 3](https://github.com/gabcsx/CCDATSCL/tree/main/Excercises/Exercise_3) | Performing summary statistics, distribution analysis, and data quality assessment on the Pokémon dataset. |
| **Data Visualization and Interpretation** | [Exercise 4](https://github.com/gabcsx/CCDATSCL/tree/main/Excercises/Exercise_4) | Creating and interpreting visualizations using real-world COVID-19 data with matplotlib and seaborn. |
| **Statistical Hypothesis Testing (ANOVA)** | [Exercise 5](https://github.com/gabcsx/CCDATSCL/tree/main/Excercises/Exercise_5) | Applying one-way ANOVA to evaluate teaching method effectiveness, including hypothesis formulation and interpretation. |
| **Midterm Exam** | [Exam](https://github.com/gabcsx/CCDATSCL/tree/main/Exam) | Comprehensive exam covering Pandas operations, groupby aggregation, filtering, statistical summaries, and data visualization. |
| **End-to-End Data Science Project** | [Project](https://github.com/gabcsx/CCDATSCL/tree/main/Project) | Final project analyzing Apple Health data — covering ETL pipeline development, EDA, statistical testing, and predictive modeling with Linear Regression and Random Forest. |

## Repository Structure

This repository is organized into the following folders:

- **`Exam/`**: Contains the midterm exam notebook, which tests the learner's understanding of data manipulation, aggregation, statistical summaries, and data visualization using Pandas.
- **`Excercises/`**: Provides coding exercises and practical assignments that reinforce core data science concepts. Includes Jupyter notebooks and datasets (CSV format) spanning data cleaning, EDA, visualization, and statistical testing.
- **`Project/`**: Contains the capstone project for the course — an end-to-end data science analysis of Apple Health data. This folder includes the main analysis notebook, an ETL pipeline module (`src/`), raw and processed datasets (`data/`), auto-generated visualizations (`figures/`), a data quality report (`reports/`), and the research paper in IEEE format (PDF).

```
CCDATSCL/
├── README.md
├── Exam/
│   └── CCDATSCL_EXAM.ipynb
├── Excercises/
│   ├── Exercise_1/
│   │   ├── Exercise1.ipynb
│   │   ├── cleaned_airbnb.csv
│   │   ├── avg_price_per_neighborhood.csv
│   │   └── validation_report.csv
│   ├── Exercise_3/
│   │   └── Exercise3.ipynb
│   ├── Exercise_4/
│   │   └── Exercise4.ipynb
│   └── Exercise_5/
│       └── Exercise5.ipynb
└── Project/
    ├── README.md
    ├── AppleHealth_Storyboard_Project.ipynb
    ├── Modeling_the_Relationship_Between_Daily_Activity_Metrics_and_Apple_Health_Active_Energy.pdf
    ├── data/
    │   ├── raw/
    │   └── processed/
    ├── figures/
    ├── reports/
    └── src/
        ├── __init__.py
        └── apple_health_pipeline.py
```

## Disclaimer / Acknowledgment
Please note that the materials and links provided throughout this course are for educational purposes only.
I do not own any of the content or external resources linked. These materials are intended to support the learning process and should be used in accordance with copyright laws and fair use policies.
All rights to external content and resources belong to their respective owners.

[Back to Top](#ccdatscl---data-science-and-analytics)
