# HR Dashboard Analytics

## Project Overview

HR Dashboard Analytics is an interactive business intelligence project developed using Microsoft Power BI to analyze employee data and provide a clear view of workforce composition, headcount, attrition, and employee demographics.

The project converts raw HR data stored in Excel into an interactive dashboard that allows users to explore workforce information across departments, business units, job titles, age groups, gender, and countries.

## Objective

The primary objective of this project is to transform HR data into meaningful visual insights that can help users understand workforce distribution and monitor important HR metrics.

The dashboard focuses on:

* Overall employee headcount
* Employee attrition and attrition trends
* Year-over-year headcount and attrition analysis
* Workforce distribution across departments and business units
* Employee distribution by age group and gender
* Employee distribution by job title
* Country-wise workforce analysis

## Data Source

The dataset was provided in Excel format and contained employee-level HR information.

The data was reviewed before developing the dashboard to ensure that the available fields were suitable for analysis. The dataset did not contain null or invalid values requiring removal.

## Data Preparation

The raw Excel data was imported into Power BI and prepared for analysis.

The following steps were performed:

1. Imported the HR dataset from Excel into Power BI.
2. Reviewed the available columns and their data types.
3. Verified the data for missing, invalid, and inconsistent values.
4. Ensured that date and categorical fields were correctly formatted.
5. Prepared the required fields for analysis and visualization.
6. Structured the data so that HR metrics could be calculated consistently.

## Data Modeling and Calculations

After preparing the data, the required relationships and analytical structure were established in Power BI.

DAX measures were created to calculate important HR metrics and support dynamic dashboard analysis.

The calculations were used for:

* Total Headcount
* Attrition
* Attrition Rate
* Year-over-Year Headcount
* Year-over-Year Attrition
* Other supporting HR metrics used within the dashboard

These measures allow the dashboard values to update dynamically when users interact with filters and slicers.

## Dashboard Development

The dashboard was designed with multiple pages to organize the HR analysis clearly.

### 1. Summary

The Summary page provides an overall view of the organization's workforce.

It includes:

* Key HR metrics
* Headcount overview
* Attrition analysis
* Year-over-Year Headcount trends
* Year-over-Year Attrition trends
* Interactive filters

This page is designed to provide a quick understanding of the current HR situation.

### 2. Headcount Analysis

The Headcount Analysis page provides a detailed breakdown of employee distribution.

The analysis covers:

* Headcount by Business Unit
* Headcount by Age Group
* Headcount by Gender
* Headcount by Job Title
* Headcount by Department

This allows users to examine workforce composition from multiple dimensions.

## Interactive Features

To make the dashboard easier to explore, several Power BI interactive features were implemented.

### Slicers

Interactive slicers were added for:

* Department
* Country
* Employee Full Name

These slicers allow users to filter the dashboard and examine specific employee groups.

### Synchronized Slicers

Slicer synchronization was implemented across relevant dashboard pages so that selected filters remain consistent while navigating between pages.

### Bookmarks

Bookmarks were used to create dashboard navigation and provide different viewing options.

The dashboard includes navigation for:

* Summary
* Headcount Analysis
* Light Mode
* Dark Mode

### Light and Dark Modes

Two visual themes were developed using Power BI bookmarks and selection states. Users can switch between light and dark dashboard views without changing the underlying analysis.

### Last Data Refresh

A Last Data Refresh indicator was included to communicate when the dashboard data was most recently updated.

## Dashboard Workflow

The complete development process followed this workflow:

**Excel HR Dataset
→ Data Validation
→ Data Preparation
→ Data Modeling
→ DAX Measures
→ Visual Development
→ Slicers and Filters
→ Bookmarks and Navigation
→ Light/Dark Mode
→ Final Interactive Dashboard**

## Tools and Technologies

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Cleaning
* Data Modeling
* Data Visualization
* Business Intelligence

## Skills Demonstrated

This project demonstrates practical experience in:

* HR Analytics
* Business Intelligence
* Data Preparation
* Data Transformation
* Data Modeling
* DAX
* KPI Development
* Interactive Dashboard Development
* Data Visualization
* Power BI Bookmarks
* Slicer Synchronization
* Dashboard UI Design

## Author

**Abinaya S**

B.Tech Artificial Intelligence and Data Science
