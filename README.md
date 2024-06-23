# Tableau Analytics Project: Adverse Event Reporting in the Food and Cosmetics Industry

## A Case Study on Adverse Event Reporting in the Food and Cosmetics Industry

#### Link to the dashboard:
[Dashboard](https://public.tableau.com/app/profile/aiman.sahay/viz/AdverseEventReportinginFoodCosmeticsIndustry/Overview?publish=yes)

#### Link to the Project:
[Tableau Project](https://drive.google.com/drive/folders/1oHGKOkQOJPbnANG0uRKzHQquawQE64Ep?usp=sharing)

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

* **Adverse Event Analysis:** Distribution of adverse events across product categories to determine which products are most associated with adverse events.
* **Severity Analysis:** Assessment of the severity of adverse events, identifying common severe outcomes and their variance by product.
* **Demographic Analysis:** Exploration of how different demographics (age, gender) are affected by adverse events.
* **Symptom Frequency Analysis:** Identification of the most frequently reported symptoms and their variation across product categories.
* **Temporal Trends:** Analysis of trends in adverse event reporting over time, identifying any seasonal or annual patterns.
* **Reporting Delay Analysis:** Calculation of the average time lag between adverse event occurrence and report submission, and its variation by product type or severity.
* **Product Risk Analysis:** Evaluation of the risk associated with different products based on adverse event data.
* **Correlation and Clustering Analysis:** Exploration of correlations between demographics, product types, and event severity, and clustering of symptoms for deeper insights.

## Dashboard Building

### Interactive Dashboard Creation
* Developed interactive dashboards in Tableau showcasing visuals for adverse event frequency, severity, demographic distribution, and symptom analysis.
* Included filters for product type, event date, and demographic details to enable dynamic data exploration.

### Dashboard Design and Aesthetics
Focused on creating user-friendly, visually appealing dashboards that provide clear and concise insights at a glance.

### Dashboards Overview

<img width="1114" alt="2024-06-23" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/9e843773-5ba8-487d-bb58-9edcbac56405">

### Outcome Analysis

Analyzes outcomes using a severity index, product risk analysis, and outcomes by industry and adverse events.

<img width="1113" alt="2024-06-23 (1)" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/fd522953-f428-42d3-984b-2fd2d1ec29c5">

### Symptoms Analysis

Examines symptom frequency by industry, presents a word cloud of symptoms, and analyzes year-over-year trends in symptom growth.

<img width="1115" alt="2024-06-23 (2)" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/db8b82a8-55f8-40a4-92c5-5f63cb7fd99c">

### Demographics Analysis

Investigates severity by gender, age analysis by outcome, clustering analysis, and gender analysis by product role.

<img width="1114" alt="2024-06-23 (3)" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/bf253bf6-edea-4f72-8756-140be1f61a08">

### Time-Based Analysis

Studies temporal trends in event reporting, duration between event occurrence and reporting, correlations between outcomes and symptoms, and forecasts future trends.

<img width="1115" alt="2024-06-23 (4)" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/e05571d2-58db-4110-b5bd-34bde37d64f6">

### Insights

Summarizes key findings from all four dashboards, providing actionable insights for stakeholders.

<img width="1114" alt="2024-06-23 (5)" src="https://github.com/AimanSahay/Tableau---Analytics-Project-in-Food-Beverage-Industry/assets/114603096/cf848b0c-2b37-49ca-a97d-a2be1cf0a86d">

## Conclusion

This Tableau analytics project provides an in-depth examination of adverse event reporting in the food and cosmetics industries using the CAERS dataset. Through meticulous data cleaning and comprehensive analysis, we have uncovered critical insights into the patterns and trends of adverse events, their severity, demographic impacts, and temporal changes. The interactive dashboards developed in Tableau enable stakeholders to explore the data dynamically, offering valuable perspectives for enhancing product safety, guiding regulatory decisions, and improving public health outcomes. By leveraging advanced analytical techniques and powerful visualizations, this project contributes significantly to understanding and mitigating risks associated with foods, dietary supplements, and cosmetics.




