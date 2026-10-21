# 🏥 Healthcare Data Analysis and Insights

## 📌 Project Overview

This project analyzes healthcare data to explore patient health
profiles, medical history, hospitalization details, and healthcare
costs. Excel is used for data cleaning, transformation, analysis, pivot
tables, charts, and dashboard-style reporting.

## 🎯 Objectives

-   Clean missing and inconsistent values across the source tables.
-   Transform patient names, surgery counts, BMI categories, HbA1C
    categories, and date fields.
-   Combine customer, medical examination, and hospitalization
    information using Customer ID.
-   Analyze cancer history, smoking, transplant history, weight status,
    diabetes status, hospital tiers, state-level charges, age, and
    healthcare costs.
-   Present findings through pivot-table summaries and visualizations.

## 🧰 Tools Used

-   Microsoft Excel
-   VLOOKUP
-   Pivot Tables and Pivot Charts
-   Excel charts and slicers
-   Data cleaning and transformation

## 🗂️ Workbook Contents

The original workbook contains these main sheets:

-   **Pivot table analysis** --- pivot-table summaries for the requested
    comparisons.
-   **Health care** --- combined dataset containing customer, health,
    hospitalization, and cost fields.
-   **visualization** --- dashboard/visualization sheet.
-   **Insights** --- supporting analysis and observations.
-   **Customer Details** --- customer name data.
-   **Medical Examinations** --- health metrics and medical history.
-   **Hospitalization Details** --- hospitalization dates, tiers, and
    charges.

The supplementary workbook contains additional analysis tables and
charts: - Cancer history by smoker status - Total major surgeries and
average HbA1C by transplant history - Average charges by weight status
and diabetes status - Average charges by state and hospital tier -
Correlations between age and BMI, HbA1C, and healthcare charges -
Age-related scatter-plot data

## 🧹 Data Preparation

The project requirements include: - Reviewing `?` values and missing
values in the source tables. - Filling missing month, year, smoker,
hospital tier, and city tier values using the specified or suitable
strategies. - Splitting customer names into Title, First Name, and Last
Name. - Converting major surgery values to numeric values. - Checking
consistency in Heart Issues and smoker fields. - Categorizing BMI as
Underweight, Normal Weight, Overweight, or Obesity. - Categorizing HbA1C
as Normal, Prediabetes, or Diabetes. - Combining year, month, and date
into a formatted date field. - Calculating age as of **8 June 2023**. -
Formatting healthcare charges as US dollar currency.

## 📊 Analysis Performed

The analysis explores: 1. Cancer history distribution among smokers and
non-smokers. 2. Total major surgeries and average HbA1C for patients
with and without transplant history. 3. Healthcare charges across weight
and diabetes categories. 4. Average charges for hospital tiers across
states. 5. Relationships between age and BMI, HbA1C, and healthcare
charges.

## 🔎 Notes and Data Quality

The combined dataset in the supplied workbook contains fewer records
than the original source tables. Customer ID matching, duplicate IDs,
and unmatched records should be reviewed before treating the combined
sheet as a complete representation of all source records. Category
labels should also be standardized consistently before refreshing pivot
tables and charts.

The supplementary workbook is provided as an additional analysis
resource; it does not replace the original workbook or its existing
interactive slicers.

## ✅ Outcome

This project demonstrates an Excel-based healthcare analytics workflow,
from data preparation and table merging to summary analysis and
visualization. The results can help highlight patterns in patient health
characteristics and healthcare charges, while further data-quality
validation is important before drawing conclusions.
