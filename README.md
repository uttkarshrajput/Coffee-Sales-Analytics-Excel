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

## Data Modeling (VLOOKUP)

- Instead of relying on simple flat files, I used **VLOOKUP** to build a relational dataset
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

**Market Concentration**  
The United States is the dominant market, generating over **90% of total revenue ($9,654)**. In contrast, the UK and Ireland markets are significantly under-tapped opportunities.

**Seasonality Trends**  
Sales consistently spike in **March and June** across multiple years.

**Recommendation**  
Inventory stocking should be increased by **15% in February and May** to meet this recurring demand surge.

**Product Preferences**  
Arabica and Excelsa beans are the top sellers.

**Loyalty Analysis**  
While Loyalty Card holders show higher retention, the **Robusta** coffee type has the lowest loyalty usage, indicating a need for a targeted marketing campaign for this segment.

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
