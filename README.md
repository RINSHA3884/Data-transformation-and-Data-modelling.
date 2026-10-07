# Data-transformation-and-Data-modelling.# Power BI Data Analysis Assignment

## 📌 Project Overview

This project demonstrates the use of **Microsoft Power BI** and **Power Query** for importing, transforming, cleaning, merging, analyzing, and modeling sales data.

The assignment covers the complete data preparation and modeling workflow, from importing raw CSV files to creating relationships between tables for analysis.

## 📂 Data Sources

The project uses the following datasets:

* **List of Orders**
* **Order Details**
* **Sales Target**

## 🔄 Data Import

The datasets were imported into Power BI and processed using **Power Query Editor**.

The following tasks were completed:

* Imported the List of Orders data into Power BI.
* Opened the data in Power Query Editor.
* Imported `Order Details.csv`.
* Imported `Sales Target.csv`.

## 🛠️ Data Transformation

The following transformations were performed using Power Query:

* Restricted the **List of Orders** table to the first **500 rows**.
* Changed **Order Date** to the **Date** data type.
* Changed **Amount** and **Target** to **Fixed Decimal Number**.
* Converted **Customer Name** to **Proper Case**.
* Merged **City** and **State** into a new **Location** column using the format:
  `City, State`
* Created a custom **Profit Margin** column using:
  `Profit / Amount`
* Created a conditional **Profit Status** column based on Profit values.

## 🔗 Data Merging

The **List of Orders** and **Order Details** tables were merged using **Order ID**.

A new combined table named **Orders Data** was created from the merged data.

## 🧹 Data Cleaning

Data cleaning activities included:

* Handling missing data.
* Identifying and handling duplicate records.
* Checking data types and maintaining consistency across columns.

## 📊 Sorting and Filtering

Sorting and filtering techniques were applied to analyze the data.

Examples include:

* Sorting orders by **Order Date** in descending order.
* Filtering orders by **State**.
* Filtering data by **Category** for category-level analysis.

## 📈 Grouping and Aggregation

Grouping and aggregation techniques were used to summarize the data and obtain meaningful insights.

The analysis included:

* Grouping data by relevant categories.
* Calculating counts.
* Calculating totals and other required aggregations.

## 🧩 Data Modeling

Relationships between the tables were created in **Power BI Model View**.

### Relationships

* **Order Details → List of Orders**

  * Relationship based on **Order ID**
  * Many-to-one relationship

* **Order Details ↔ Sales Target**

  * Relationship based on **Category**
  * Many-to-many relationship
  * Cross-filter direction: **Single**
  * Relationship: **Active**

The model was reviewed to ensure the required relationships were correctly established.

## 🧰 Tools Used

* **Microsoft Power BI Desktop**
* **Power Query Editor**
* **DAX**
* **CSV datasets**

## 🎯 Learning Outcomes

Through this assignment, I practiced:

* Importing data into Power BI
* Data transformation using Power Query
* Data cleaning
* Creating custom and conditional columns
* Merging tables
* Sorting and filtering data
* Grouping and aggregating data
* Creating DAX calculations
* Building relationships between tables
* Understanding Power BI data modeling

## 📁 Repository Contents

This repository contains the files and resources related to the Power BI assignment, including the datasets, Power BI report, and supporting documentation.

## 👩‍💻 Author

**Rinsha Sharin**

BCA – Data Analytics
