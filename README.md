# Strategic Coffee Sales Dashboard

![Dashboard Preview](dashboard_screenshot.png/Picture%208.png)


> Note: View the interactive dashboard file in the `Cleaned_Data` folder

---

## Project Overview

This project analyzes retail coffee sales data from **2019 to 2022** to identify trends in customer purchasing behavior and product performance. Starting with raw, unstructured data, I cleaned, structured, and analyzed the dataset entirely in Microsoft Excel.  

The final deliverable is an interactive dashboard that helps stakeholders identify seasonality patterns and high-value market opportunities.

---

## Project Workflow

The analysis followed a structured data pipeline:

---

## Data Extraction & Cleaning

- Imported raw data consisting of three separate datasets: **Orders**, **Customers**, and **Products**
- Handled missing values and standardized data formats (e.g., correcting date formats and currency)
- Converted raw ranges into Excel Tables to enable dynamic data range updates

---

## Data Modeling (XLOOKUP)

- Instead of relying on simple flat files, I used **XLOOKUP** to build a relational dataset
- Merged customer demographics (Name, Country, Loyalty Status) and product details (Roast Type, Profit Margin) into the main transaction table to create a master dataset for analysis

---

## Data Visualization & Reporting

- Built Pivot Tables to summarize key metrics:
  - Total Sales by Country  
  - Top 5 Customers  
  - Sales Over Time  
- Designed an interactive dashboard with:
  - Slicers (Roast Type, Size, Loyalty Card)  
  - Timeline filters for dynamic exploration

---

## Key Findings & Insights

### Market Concentration  
The **United States** is the dominant market, generating **₹35,638.89** in total sales.  
**Ireland** follows with **₹6,696.87**, while the **United Kingdom** contributes **₹2,798.51**, indicating strong growth potential in both non-US markets.

---

### Seasonality Trends  
Sales show consistent increases during **March and June** across multiple years, suggesting recurring demand peaks during late Q1 and early Q2.

---

### Product Performance  
**Arabica** and **Excelsa** consistently generate the highest monthly sales across most years.  
**Robusta** shows higher volatility, with sharp spikes in select months (notably during mid-year periods), indicating opportunity for targeted promotional campaigns.

---

### Loyalty & Customer Behavior  
Markets with higher overall sales volumes, particularly the **United States**, also demonstrate stronger repeat purchase patterns. Lower-performing regions present opportunities for loyalty-driven customer acquisition strategies.

---

### Business Recommendation  
- Increase inventory levels by **15–20% in February and May** to prepare for seasonal demand spikes in March and June  
- Expand targeted marketing and loyalty incentives in the **UK and Ireland** to improve market penetration  
- Focus premium product positioning around **Arabica and Excelsa**, while using promotions to stabilize demand for **Robusta**


---

## Tools Used

### Microsoft Excel

**Data Cleaning**
- Text-to-Columns  
- Remove Duplicates  

**Formulas**
- IF Statements  
- XLOOKUP  

**Analysis**
- Pivot Tables  
- Data Modeling  

**Visualization**
- Interactive Dashboard  
- Slicers  
- Timeline  

---

## How to View This Project

**Preview**  
See the dashboard image above.

**Interact**
1. Navigate to the `Cleaned_Data` folder  
2. Download `coffeeOrdersData_final.xlsx`  
3. Open the file in Microsoft Excel  
4. Use slicers and the timeline to filter and explore insights dynamically
