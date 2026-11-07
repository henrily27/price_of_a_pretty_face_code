# The Price of a Pretty Face: Does Attractiveness Pay When Controlling for Intelligence?

**Author:** Henri Ly (@henrily27)  
**Context:** STAT 386 – Data Acquisition & Regression  

## Project Overview
This repository contains the code and analysis for a labor economics regression study investigating the "beauty premium." The project isolates the financial impact of physical attractiveness on annual income by controlling for confounding variables such as cognitive ability (IQ), height, BMI, waist circumference, and sex. 

## Data Source
The analysis utilizes the **Wisconsin Longitudinal Study (WLS) Version 2026_v1**. This dataset tracks a 1957 cohort of Wisconsin high school graduates, combining:
* Administrative high school Henmon-Nelson IQ scores
* Physical body measurements (height, BMI, waist)
* Later-in-life annual wages (log-transformed for analysis)
* Independent panel ratings of 1957 yearbook photographs

## Key Findings
* **The Beauty Premium:** Each 1-unit increase in attractiveness (on a 1–10 scale) correlates with a ~4.32% increase in annual income.
* **Intelligence Factor:** IQ remains a massive driver of earnings, yielding a ~1.22% salary increase per point.
* **Sex Disparity:** In this 1957 cohort, women earned approximately 56.7% less than men, though the percentage return on IQ remained similar across sexes.

## Repository Contents
* **Data Cleaning & Modeling:** R scripts utilizing `haven`, `dplyr`, and `labelled` to process the raw 425 MB Stata (`.dta`) WLS archive into a clean dataset of 2,990 complete observations.
* **Interactive Blog:** An HTML/CSS/JS-powered blog post featuring a predictor module that estimates age-54 inflation-adjusted salaries based on user-inputted physical and cognitive metrics.

## Ethical Considerations
* **Local Processing:** Per WLS terms of use, raw participant records must be processed locally and are strictly prohibited from being uploaded to external AI platforms to protect participant confidentiality.
* **Anonymity:** No attempts should be made to de-anonymize graduates, and findings carry historical caveats specific to a 1957 Midwestern demographic.
