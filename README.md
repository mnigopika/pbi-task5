# 🏥 Healthcare Data Cleaning & Analysis \| Power BI

A Power BI project focused on preparing a healthcare dataset for
reliable analysis. The dataset contains **55,500 patient admission
records** and 15 fields covering patient details, medical conditions,
hospital information, billing, insurance, medication, and test results.

## 📌 Project Overview

The goal of this project is to use **Power BI and Power Query** to
inspect, clean, and structure healthcare data so it is easier to analyze
and use in reports or dashboards.

## 🧰 Tools Used

-   **Microsoft Power BI Desktop** --- data preparation and reporting
-   **Power Query Editor** --- data cleaning and transformation
-   **CSV** --- source dataset

## 📂 Dataset Details

The source dataset includes these fields:

  -----------------------------------------------------------------------
  Category                            Example fields
  ----------------------------------- -----------------------------------
  Patient details                     Name, Age, Gender, Blood Type

  Medical information                 Medical Condition, Medication, Test
                                      Results

  Admission details                   Date of Admission, Discharge Date,
                                      Admission Type

  Hospital and care                   Doctor, Hospital, Room Number

  Financial information               Billing Amount, Insurance Provider
  -----------------------------------------------------------------------

**Dataset size:** 55,500 rows × 15 columns.

## 🧹 Data Cleaning in Power BI

Data cleaning was carried out in **Power Query Editor** to prepare the
source data for analysis. The workflow can include:

-   Reviewing column names and the structure of the dataset.
-   Checking for missing or blank values.
-   Setting appropriate data types for numeric, text, and date columns.
-   Preparing admission and discharge dates as date fields.
-   Checking text fields for inconsistent formatting.
-   Reviewing the data for duplicate records and unexpected values.
-   Applying the transformations and loading the prepared data into
    Power BI.

> **Note:** Keep only the cleaning steps above that you actually
> performed in your Power Query workflow. Do not describe duplicates as
> removed unless you removed them.

## 🔎 Key Fields for Analysis

-   Patient age and gender
-   Medical condition and blood type
-   Admission type and length of stay (using admission and discharge
    dates)
-   Hospital and doctor
-   Insurance provider and billing amount
-   Medication and test results

## 🎯 Project Objectives

-   Improve the consistency and usability of the dataset.
-   Prepare healthcare data for visual analysis.
-   Make patient, admission, and billing information easier to explore.
-   Build a foundation for healthcare reporting in Power BI.

## 📈 Possible Dashboard Insights

After cleaning, the data can be used to explore:

-   Patient count by medical condition
-   Admissions by type and date
-   Billing amount by hospital or insurance provider
-   Patient distribution by age group and gender
-   Test results and medication patterns
-   Length of stay based on admission and discharge dates

*These are possible analysis ideas; include them as completed results
only if they appear in your Power BI report.*

## 📁 Project Files

-   `hcpbi.pbix` --- Power BI project file
-   `healthcare_dataset.csv` --- source dataset

## 🚀 How to View the Project

1.  Download or clone this repository.
2.  Open `hcpbi.pbix` using **Power BI Desktop**.
3.  If Power BI asks for the source file, point it to
    `healthcare_dataset.csv`.
4.  Select **Refresh** if required to load the data and view the report.

## 💡 Learning Outcome

This project demonstrates practical experience with importing a CSV
dataset, using Power Query for data cleaning and transformation, and
preparing healthcare data for analysis in Power BI.

------------------------------------------------------------------------

**Project:** Healthcare Data Cleaning using Power BI\
**Focus:** Data preparation, data quality checks, and reporting
readiness

