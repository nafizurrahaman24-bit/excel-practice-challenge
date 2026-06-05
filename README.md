# excel-practice-challenge
Solutions for Excel Practice Challenge with PivotTable analyses on sales pipeline data.
# B2B Sales Pipeline Analysis

## Project Overview

This project analyzes a B2B sales pipeline dataset from a fictitious computer hardware company. The dataset contains information on sales opportunities, products, sales agents, sales teams, and deal outcomes. The objective is to evaluate sales performance, identify areas for improvement, and generate business insights using Microsoft Excel.


## Dataset Description

The workbook contains the following sheets:

### 1. Sales Pipeline

Contains detailed information on sales opportunities, including:

* Opportunity ID
* Sales Agent
* Account
* Product
* Engage Date
* Close Date
* Deal Stage
* Close Value

### 2. Sales Team

Contains information about:

* Sales Agent
* Manager
* Regional Office

### 3. Products

Contains product-related information used for product performance analysis.

### 4. Accounts

Contains customer account information.

## Business Questions Addressed

### Analysis 1: How is each sales team performing compared to the rest?

Performance was evaluated using:

* Number of Won Deals
* Total Revenue Generated

Sales teams were defined as manager-led teams, where each manager supervises a group of sales agents.

Key Deliverables:

* Team performance ranking
* Revenue comparison
* Won-deal comparison
* Team performance visualization

### Analysis 2: Are any sales agents lagging behind?

Individual sales agents were evaluated based on:

* Number of Won Deals
* Revenue Generated

Key Deliverables:

* Bottom-performing sales agents
* Revenue ranking
* Performance comparison chart
* Identification of potential coaching opportunities

### Analysis 3: Are there any quarter-over-quarter trends?

Quarterly sales performance was analyzed using:

* Revenue by Quarter
* Won Deals by Quarter
* Quarter-over-Quarter (QoQ) Growth

Key Deliverables:

* Quarterly trend analysis
* Revenue trend chart
* Deal volume trend chart
* QoQ growth calculation

QoQ Growth Formula:

(Current Quarter Revenue − Previous Quarter Revenue) ÷ Previous Quarter Revenue × 100

### Analysis 4: Do any products have better win rates?

Product performance was evaluated using:

Win Rate = Won Deals ÷ Total Opportunities

Key Deliverables:

* Product win-rate comparison
* Product ranking
* High-performing product identification
* Low-performing product identification

## Excel Techniques Used

### Data Preparation

* XLOOKUP / VLOOKUP
* Data Filtering
* Data Cleaning
* Calculated Fields

### Analysis Tools

* Pivot Tables
* Pivot Charts
* Sorting and Filtering
* Percentage Calculations

### Visualizations

* Clustered Column Charts
* Bar Charts
* Line Charts

## Key Metrics

### Sales Performance

* Won Deals
* Revenue Generated
* Average Deal Value

### Agent Performance

* Revenue per Agent
* Won Deals per Agent

### Team Performance

* Revenue by Team
* Won Deals by Team

### Product Performance

* Win Rate
* Product Revenue

### Time-Series Performance

* Quarterly Revenue
* Quarterly Won Deals
* QoQ Growth

## Business Value

This analysis helps management:

* Identify top-performing sales teams
* Detect underperforming sales agents
* Understand quarterly sales trends
* Evaluate product effectiveness
* Improve sales strategy and resource allocation

## Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Excel Formulas (XLOOKUP, VLOOKUP, IF, Percentage Calculations)

## Author
Nafizur Rahaman

Prepared as part of a Business Analytics and Sales Performance Analysis project using Microsoft Excel.
