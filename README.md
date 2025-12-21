# Phase 1 Project Description

# Turbulence Motors Aviation Data Analysis

> **Author**: William Nyawir

## Project Overview
Turbulence Motors aims to identify aircraft makes with the lowest accident and injury risk to support safer decisions for business operations and personal aviation use.

### Business Problem
Finding the safest aircraft with the lowest risk.

## Key Objectives
- Identify aircraft makes with the highest and lowest accident frequency
- Compare accident severity using fatal and non-fatal injury data
- Support aircraft selection decisions using historical safety trends

## Key Visualizations

### Top 10 Aircraft Makes with the Most Accidents
<img src="Images/top makes with most accidents.png" />

### Top makes with highest fatal injuries
<img src="images/top makes with highest fatal injuries.pngtop makes with highest fatal injuries.png" />

### Weather conditions with most accidents
<img src="images/weather with most accidents.png" />

## The Data
The dataset was obtained from the National Transportation Safety Board (NTSB) and contains aviation accident records from 1962 to 2023.

For this analysis:
- Only data from the last 20 years was used to reflect modern aviation standards
- The focus was on accident severity and aircraft characteristics
- The dataset includes over 90,000 accident records

## Methodology
1. Data loading and initial inspection to understand structure and completeness
2. Data cleaning by handling missing values and standardizing column formats
3. Filtering the dataset to include only airplanes and recent accident records
4. Feature selection focusing on aircraft characteristics and injury severity
5. Aggregation and grouping to compare accident frequency across aircraft makes
6. Visualization of key findings using charts for easier interpretation

## Key Findings
- A small number of aircraft makes account for a disproportionately high number of accidents
- Aircraft with higher accident frequency also tend to have higher fatal injury counts
- Some aircraft makes consistently show lower accident records, indicating lower operational risk

## Recommendations
- Prioritize aircraft makes with lower historical accident frequency
- Apply stricter safety monitoring and maintenance checks to higher-risk aircraft
- Use accident history alongside operational factors such as flight hours and maintenance records

## Limitations
- Accident counts do not account for aircraft usage or total flight hours
- Some aircraft may appear safer due to lower exposure rather than better safety
- Results should be used as a decision-support tool, not a standalone measure

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Tableau

## Evidence
For more information, visit:
-  [Jupyter Notebook](./student.ipynb)
-  [Tableau Dashboard](./aviation_data_visualisation.twbx)
-  [Presentation](./presentation.pptx)
