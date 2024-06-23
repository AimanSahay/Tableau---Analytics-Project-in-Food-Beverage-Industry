# Tableau Analytics Project: Adverse Event Reporting in the Food and Cosmetics Industry

## A Case Study on Adverse Event Reporting in the Food and Cosmetics Industry

## Background
The CAERS database, a vital tool for the FDA, comprises adverse event and product complaint reports related to foods, dietary supplements, and cosmetics. This dataset, spanning from 2004 to the second quarter of 2017, provides detailed records coded using the Medical Dictionary for Regulatory Activities (MedDRA) terminology. This standardization ensures consistent reporting across various products, capturing essential data such as product roles, brand names, industry codes, patient demographics, adverse outcomes, and coded symptoms.

## Objective
The analysis of the CAERS dataset aims to uncover comprehensive insights into adverse events associated with foods, dietary supplements, and cosmetics. By identifying patterns and trends, we strive to enhance product safety surveillance, inform regulatory policies, and improve public health outcomes. Key areas of focus include the distribution of adverse events across product categories, demographic characteristics of affected individuals, and the severity and types of reported symptoms and outcomes.

## Data Source
The analysis is based on the "CAERS_ASCII_2004_2017Q2.csv", a comprehensive collection of reports submitted to the FDA regarding adverse events and product complaints.

## Data Preparation

Data cleaning was performed in Python using Pandas, ensuring the dataset was prepared for advanced analysis in Tableau. Key steps included:

* **Identifying Missing Values:** Detected and documented missing values across various columns.
* **Standardizing Age:** Converted the age column, which was present in different formats, to a standard format in years.
* **Standardizing Data Types:** Ensured consistent data types for date fields.
* **Imputing Missing Values:** Imputed missing values in the age column by grouping the data by industry type and calculating the mean age within each group.
* **Removing Outliers:** Identified and removed outliers using the Interquartile Range (IQR) method.
* **Exploding Symptoms:** Split the symptoms column and exploded the dataset so that each symptom could be analyzed individually for each adverse event.
* **Categorizing Outcomes and Ages:** Converted outcomes and ages into meaningful categories for more insightful analysis.

## Analytical Focus Areas

* Adverse Event Analysis: Distribution of adverse events across product categories to determine which products are most associated with adverse events.
Severity Analysis: Assessment of the severity of adverse events, identifying common severe outcomes and their variance by product.
Demographic Analysis: Exploration of how different demographics (age, gender) are affected by adverse events.
Symptom Frequency Analysis: Identification of the most frequently reported symptoms and their variation across product categories.
Geographical Distribution: Examination of the geographical spread of reports to identify regional patterns.
Temporal Trends: Analysis of trends in adverse event reporting over time, identifying any seasonal or annual patterns.
Reporting Delay Analysis: Calculation of the average time lag between adverse event occurrence and report submission, and its variation by product type or severity.
Product Risk Analysis: Evaluation of the risk associated with different products based on adverse event data.
Correlation and Clustering Analysis: Exploration of correlations between demographics, product types, and event severity, and clustering of symptoms for deeper insights.
Part 2: Dashboard Building
Interactive Dashboard Creation

Developed interactive dashboards in Tableau showcasing visuals for adverse event frequency, severity, demographic distribution, and symptom analysis.
Included filters for product type, event date, and demographic details to enable dynamic data exploration.
Dashboard Design and Aesthetics

Focused on creating user-friendly, visually appealing dashboards that provide clear and concise insights at a glance.
Dashboards Overview
Outcome Analysis

Analyzes outcomes using a severity index, product risk analysis, and outcomes by industry and adverse events.
Symptoms Analysis

Examines symptom frequency by industry, presents a word cloud of symptoms, and analyzes year-over-year trends in symptom growth.
Demographics Analysis

Investigates severity by gender, age analysis by outcome, clustering analysis, and gender analysis by product role.
Time-Based Analysis

Studies temporal trends in event reporting, duration between event occurrence and reporting, correlations between outcomes and symptoms, and forecasts future trends.
Insights

Summarizes key findings from all four dashboards, providing actionable insights for stakeholders.
This project leverages Tableau's advanced analytical capabilities to deliver a comprehensive understanding of adverse events in the food and cosmetics industries, aiming to enhance product safety and public health.




