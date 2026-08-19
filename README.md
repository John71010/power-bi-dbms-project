# Power BI & Database Analytics Project

## Overview

This repository contains the practical work completed for four experiments using Microsoft Power BI, Power Query, DAX, MySQL, Excel, and business datasets.

The project covers data acquisition, data profiling, ETL processes, dimensional modeling, and OLAP analysis.

## Experiments

### Experiment 1 – Data Acquisition and Data Profiling

Data was acquired from multiple sources including CSV, Excel, and MySQL. Microsoft Power BI and Power Query were used to examine data structure, data types, missing values, duplicate records, and other data quality issues.

### Experiment 2 – ETL Processes using Power BI

An end-to-end ETL process was implemented using the Global Superstore dataset. Data was extracted from the Orders, Returns, and People worksheets, transformed using Power Query, and loaded into the Power BI data model.

DAX measures were also created for analytical reporting. Supporting PDF documentation and practical work are included in this folder.

### Experiment 3 – Dimensional Data Modeling

A Star Schema was designed using Fact and Dimension tables. Fact_Sales was created along with Customer, Product, Region, and Date dimensions.

Relationships were established between the fact and dimension tables, followed by analytical visualizations and DAX measures.

### Experiment 4 – OLAP Operations

OLAP operations including Slice, Dice, Drill-down, and Drill-up were performed using Microsoft Power BI.

Multidimensional analysis was conducted using filters, slicers, hierarchies, and interactive report visualizations.

## Tools and Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- MySQL Workbench
- Microsoft Excel
- CSV
- Visual Studio Code
- GitHub

## Dataset

The Global Superstore dataset was used for Experiments 2, 3, and 4.

Dataset source:

Kaggle – Global Superstore Dataset

## Project Structure

```text
POWER BI DBMS PROJECT
│
├── README.md
│
├── EXPERIMENT 1
│   ├── BI_Experiment 1.docx
│   ├── Employee_DB.xlsx
│   ├── Exp 1_BI.pbix
│   ├── Sales_Data.csv
│   └── Transactions.sql
│
├── EXPERIMENT 2
│   ├── Experiment 2.docx
│   ├── Global Superstore Dataset.xlsx
│   ├── Experiment 2_ETL.pbix
│   └── Supporting PDF files
│
├── EXPERIMENT 3
│   ├── Experiment 3.docx
│   └── Experiment 3_Star_Schema.pbix
│
└── EXPERIMENT 4
    ├── Experiment 4.docx
    └── Experiment 4_OLAP.pbix