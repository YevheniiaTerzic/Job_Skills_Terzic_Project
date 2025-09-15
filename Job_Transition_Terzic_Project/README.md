# Job Transition Terzic Project

## Overview
This project explores **how professionals can transition from Data Analyst to Data Scientist**, as Data Scientist stands out with strong future potential — it’s the most in-demand role in the US, second in Europe, and offers the highest pay with room for salary growth in the EU. In this project we'll explore skill development paths and salary growth projections.

I analyze data-related roles worldwide, with a focus on Europe, to identify the most in-demand positions, what they pay, and the factors that drive salary differences. The goal is to provide actionable, data-driven insights for anyone looking to grow their career in data, especially in the European market. 

## The Questions
1. What Skills Do You Need to Transition from Data Analyst to Data Scientist?
2. What salary could get a candidate after transition?

## Tools I Used
To conduct a comprehensive analysis of the data analyst job market, I used a set of tools that supported data preparation, insightful exploration, and compelling visual storytelling:

- **Python & Libraries:**
    - **pandas:** for data cleaning and calculations.
    - **matplotlib:** for static visualizations.
    - **xgboost, shap:** for interpretable ML to uncover salary insights.
    - **ast, pathlib:** for efficient data grouping, parsing, and file handling.
- **Jupyter Notebooks:** my main workspace for combining code, visualizations, and commentary in one place.
- **Visual Studio Code:** used for editing and running Python scripts.
- **Git & GitHub:** for version control, project tracking, and public sharing.
- **AI Tools:** used to generate structured country data (EU + ISO codes), supported for debugging and brainstorming.
- **Grammarly:** used for clear, professional writing in documentation.
- **API connection:** used to convert salaries (USD → EUR) using live exchange rates for accurate regional analysis.

## Data Cleaning and Merging

This section walks through the data loading and transformation process to prepare the dataset for analysis. Key steps include:

- Load multiple yearly datasets from CSVs
- Clean the job postings dataset
- Integrate exchange rate data to convert salaries to EUR
- Merge country metadata for regional classification
- Export the cleaned dataset for further exploration

## Exploratory Data Analysis
In this section, we explore the structure and trends within the dataset, focusing on salary patterns and skill requirements for data-related roles.

The EDA is structured as follows:
- Dataset Overview
- Summary Statistics
- Analysing Salary Destributions
- Exploring Relationships (Skills vs. Salary)

**Main findings:**
- Salary Gap - Data Scientists earn ~40% more than Data Analysts, with a wider salary range indicating more specialization-driven pay differences.
- Skills Matter - More required skills correlate with higher pay.
- High-Paying Employers – certain companies, such as AVIV Group (Germany) and Palta (Cyprus), offer salaries significantly above market medians.
- Geographic Insights – Top salaries are geographically diverse, though Germany has a notable concentration of high-paying employers.

Implication for career transitions:
For **Data Analysts** aiming to move into **Data Science**, upskilling in specific technical areas is a practical route to achieving higher salaries and accessing premium employers.

## The Analysis
Here, we answer the three main questions outlined at the beginning of the readme, and the first is:

## What Skills Do You Need to Transition from Data Analyst to Data Scientist?

This section explores the skills needed to transition roles using global 2024 job postings. We will cover:

- The average number of skills required for Data Analyst and Data Scientist roles.
- Gap analysis comparing the skill sets of Data Analysts and Data Scientists.
- The most impactful skills on salary within these roles.

**Main findings:**
- On average, Data Scientists require about 6 skills per job posting, while Data Analysts require about 4.
- The common top skills for Data Analysts and Data Scientists are SQL, Python and Tableau. These skills are also the most impactful on salary. 
- To transition successfully, Data Analysts should close the skill gap with Data Scientist requirements:

![Top Data Analyst & Data Scientist Skills](Images/Venn_diagram.png)

- **Python, SQL, and Tableau** are essential for both roles.
- Excel, fundamental for Data Analysts, is less important for Data Scientists, so no need develop this skill when you are looking for the transition.
- Instead focus on learning **R, Spark, and AWS** that'll help to sucseed Data Scientist role requirement.

Also take into account that you don't need focuse on Tableau if you as a Data Analyst aleady know Power BI or Looker as powerful data visualization tools. Moreover, optionaly you can choose SAS instead of R as statistical analysis tools, Azure instead of AWS as cloud platforms, Tensorflow or Pytorch instead of Spark that are more focuced ML and deeplearning than big data processing.

## What salary could get a candidate after transition?

To support data analysts transitioning to data science roles, we build a xgboost model to estimate salary differences based on key skills we defined for transition. on this section we:

- Engineer binary skill features
- Train an XGBoost regression model
- Predict the monthly salary in EUR

**Main findings:**

## Project Summary

- **Python, SQL, and Tableau** are essential for both roles.
- Excel, fundamental for Data Analysts, is less important for Data Scientists, so no need develop this skill when you are looking for the transition.
- Instead focus on learning **R, Spark, and AWS** that'll help to sucseed Data Scientist role requirement.

Also take into account that you don't need focuse on Tableau if you as a Data Analyst aleady know Power BI or Looker as powerful data visualization tools. Moreover, optionaly you can choose SAS instead of R as statistical analysis tools, Azure instead of AWS as cloud platforms, Tensorflow or Pytorch instead of Spark that are more focuced ML and deeplearning than big data processing.

**Conclusion**
For job seekers, starting as a **Data Analyst** offers an accessible and strategic entry point into the data industry. The role is in high demand, offers consistent pay, and allows for fast upskilling through tool specialization. Over time, expanding technical capabilities and transitioning toward **Data Science** roles can open up higher-paying and more specialized career paths. The common top skills for Data Analysts and Data Scientists are SQL, Python and Tableau. These skills are also the most impactful on salary. 

**Thanks for reading — and feel free to ⭐ the project or leave feedback on GitHub if you found it helpful!**