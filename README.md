# A Curious Adventure in Data: Warehouse & Analytics Project

##✨ Welcome, Fellow Explorer!

So you want to look at data, eh? Not just look at it—really understand it!
It’s like nature’s own puzzle: raw, messy numbers over here… clean, shining insights over there.
And in between? That’s where the fun is.

In this project, I took a pile of data—like two different jars of assorted nuts and bolts—and built a tidy, organized workshop where you can actually build something with them.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 🏗️ How It’s Organized: The Medallion Layers

Imagine you’re panning for gold:


### Bronze Layer — The Raw Ore

Here’s where the data lands exactly as it comes—no polish, no changes.

Like scribbles in a lab notebook: sometimes messy, but always true to the source.

In this project: CSV files → SQL Server, as-is.



### Silver Layer — Refining the Ingots

Now we clean, straighten, and make sense of things.

Remove the dirt, fix what’s broken, and put everything in the same “language.”

Ready for the next step? You bet.


### Gold Layer — The Polished Gems
Here’s where we shape the data into something useful.

I built a star schema—like constellations! A bright fact table in the middle, dimension tables sparkling around it.

Now the business can ask questions, and the data answers.

---


## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making. 

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.
---
## 🌟 About Me

Hello! I’m Ankit Malik.
I like to build data pipelines so that clean, useful information flows where it’s needed.
I transform, organize, and protect data so others can ask great questions and get clear answers.
---

### 🚀 What I Do:

Designing systems that handle data at scale.

Turning raw data into structured insight.

Making sure data stays trustworthy, from source to dashboard.

Teaming up with smart people to solve real puzzles.

---

Let's stay in touch! Feel free to connect with me on Linkedin:

www.linkedin.com/in/ankitmalik81680



