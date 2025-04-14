# Sales Analytics Dashboard

![Sales](https://img.shields.io/badge/Power_BI-E_commerce_Sales)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📊 Overview

An interactive Power BI dashboard designed to monitor a company’s business performance and generate insights for strategic decision-making. It provides:

- A comprehensive overview of business performance  
- Actionable insights to guide market expansion and product strategy

## 🔄 Data Model

![image](https://github.com/user-attachments/assets/be8c5a16-84e3-4d31-b0b6-4a08be9a7a48)

### ⭐ Star Schema Implementation

The dashboard is powered by a star schema data model consisting of:

#### Fact Table
- **orders**: Contains sales order information (category, market, customer ID, country, order date, ship date, etc.)

#### Dimension Tables
- **people**: Customer demographic information  
- **returns**: Returned order IDs  
- **organization**: Healthcare facility and department data  
- **calendar**: Date dimension for time-based analysis  

#### DAX Calculations
The model includes several DAX measures and time intelligence functions to create KPIs and calculated metrics used throughout the dashboard.

## 🧠 Design Thinking

This dashboard was developed using the Design Thinking process: **Empathize**, **Define POV**, **Ideate**, **Prototype**, and **Review**.

### Empathize
![image](https://github.com/user-attachments/assets/ec57a8a4-dfd0-44e9-a6db-f8bda17282f3)

### Define POV
![image](https://github.com/user-attachments/assets/98acb48e-f9d1-4f1f-9fdd-6873d98ee2f0)

### Ideate
![image](https://github.com/user-attachments/assets/5df326d6-e998-44d8-86cb-30c7a0f1d320)

---

## 🔍 Dashboard Features

### 📌 Executive View

Provides a high-level summary for decision-makers, comparing current performance against the previous month:

- **Commercial performance**: Sales, Orders, Profit  
- **Operational performance**: Return rate, Average delivery time  

Key insights:
- APAC and EU are the leading regions in sales  
- Profit margin is ~11%, with a downward trend  
- Despite a drop in orders, sales increased — indicating higher-value products were sold  
- Technology and Furniture are top-performing categories  
- ~2% of products are returned, and delivery averages ~4 days, reflecting relatively efficient operations  

![Executive View](https://github.com/user-attachments/assets/f6007ab4-d0a5-4d3e-afb2-022063c33ca3)

### 📦 Product Breakdown

Analyzes product performance by comparing metrics with the previous month and year, highlighting Month-over-Month (MoM) growth by category.

Features include:
- Identifying top-performing categories and products  
- Simulating the impact of price changes on profits  
- Adjusting sales targets based on past performance

![Market Breakdown](https://github.com/user-attachments/assets/6aa337b8-cb6d-42f3-b19d-bcca9c5ac5ab)


### 🌍 Market Breakdown

A detailed view of profits across markets. While sales volume is important, this view helps identify high-potential and profitable markets that deserve strategic focus.

![Product Breakdown](https://github.com/user-attachments/assets/ab60eadf-6838-4d47-a427-3cf0cccebd3a)

## 📁 Data Source

This project uses sample e-commerce sales data provided by **Unigap**.
