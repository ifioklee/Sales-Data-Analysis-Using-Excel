# Sales-Data-Analysis-Using-Excel

# Project Overview
This repository contains an ongoing analysis of a sales dataset aimed at answering questions related to sales performance, customer and product insights, as well as discount and pricing analysis. It also seeks to derive relevant insights that will be visualized through various charts and presented in an interactive dashboard.

## Project Goal

The goal of this project is to find answers related to the following key business questions:

### Sales Performance Analysis
- Which sales representative generated the highest total sales?  
- What is the total revenue generated per region?  
- What is the trend of sales over different months?

### Customer & Product Insights
- What is the most popular product category based on quantity sold?  
- How does the customer type (New vs. Returning) affect sales performance?  
- Which payment method is most commonly used?

### Discount & Pricing Analysis
- What is the average discount given per product category?  
- How does the percentage discount impact the total sales amount?

# Features

### 1. Chart Visualizations for Showing Patterns
- Various charts were created to visually represent patterns, trends, and relationships observed in the dataset.  
- These visualizations provide a clear understanding of key metrics and how they change over time or across categories.

### 2. Dashboard Overview
- An interactive dashboard was developed to present an overview of the insights and patterns identified during the analytical process.  
- The dashboard integrates multiple charts relevant to answering questions relating the goalof the analysis.

### 3. Pivot Tables for Chart Creation
- Pivot tables were generated to summarize, aggregate, and organize the dataset into meaningful dimensions.  
- These pivot tables served as the data foundation for building the various chart visualizations used in the dashboard.

### 4. Cleaned Dataset as Analytical Foundation
- The raw dataset was cleaned and transformed to remove inconsistencies, duplicates, and errors.  
- This cleaned dataset formed the basis for all subsequent pivot table generation, chart visualizations, mathematical computations, and dashboard construction.

- ## Interactive Excel Dashboard

The dashboard provides a comprehensive view of key sales insights, enabling data-driven decision-making and performance tracking.

### Insights Displayed

1. **Sales by Region**  
   Visualizes total sales distribution across different regions.

2. **Sales Trend Over Time**  
   Tracks monthly or quarterly sales performance trends.

3. **Sales by Product Category**  
   Highlights top-performing product categories based on sales.

4. **Sales Performance by Sales Representative**  
   Compares individual sales representatives’ performance.

5. **Sales by Customer Type**  
   Differentiates between new and returning customers to assess loyalty impact.

6. **Payment Method Breakdown**  
   Shows the proportion of transactions made via different payment methods.

7. **Sales by Channel (Online vs. Retail)**  
   Analyzes the contribution of online and retail channels to overall sales.

8. **Average Discount by Product Category**  
   Analyzes the contribution of online and retail channels to overall sales.

# Data

# Project Structure

### Raw Dataset
The original dataset used for this analysis can be found here:  
[🔗 View Raw Dataset](https://github.com/ifioklee/Sales-Data-Analysis-Using-Excel/tree/main/Orignal%20DataSet)

### Completed Analysis
This folder contains the cleaned data, pivot tables, and final Excel analysis files:  
[🔗 View Completed Analysis](https://github.com/ifioklee/Sales-Data-Analysis-Using-Excel/tree/main/Completed%20Analysis)

### Visualization
All chart visualizations and the interactive dashboard are available here:  
[🔗 View Visualization Files](https://github.com/ifioklee/Sales-Data-Analysis-Using-Excel/tree/main/Visualization)

### README.md Project verview and instructions
You can explore the complete project documentation here:  
[🔗 View README File](https://github.com/ifioklee/Sales-Data-Analysis-Using-Excel/blob/main/README.md)

## Technical Details

This project uses **Microsoft Excel** for data exploration, chart visualization, and dashboard creation.

### Data Preparation and Exploration
The data exploration process began by duplicating the **original dataset** into a new worksheet.  
This step ensured that the raw data remained intact, allowing for comparison between the original and the transformed data used for analysis.

The duplicated sheet was converted into an **Excel Table** for easier referencing and consistency in calculations.  
A new column named **"Month"** was added, and the month of each sale was extracted from the **"Sales_Date"** column using the `TEXT` function.  
This populated the Month column for time-based analysis.

Once the dataset was confirmed complete (with all necessary fields and calculations), several **Pivot Tables** were created to generate key insights and visualizations.

---

### 📊 Pivot Tables and Chart Visualizations

| Sheet Name | Pivot Table Fields | Visualization Type | Description |
|-------------|--------------------|--------------------|--------------|
| **Total Quantity Sold By Sales Rep** | `Sales_Rep`, `Quantity_Sold` | 3-D Clustered Column Chart | Shows total quantity sold per sales representative. |
| **Total Revenue By Region** | `Region`, `Sales_Amount` | 3-D Clustered Column Chart | Displays total revenue generated by each region. |
| **Total Sales By Month** | `Month`, `Sales_Amount` | Clustered Column Chart | Highlights monthly sales trends over time. |
| **Product Category By Quantity Sold** | `Product_Category`, `Quantity_Sold` | Pie Chart | Visualizes the most popular product categories by quantity sold. |
| **Sales By Customer Type** | `Customer_Type`, `Sales_Amount` | Clustered Column Chart | Compares sales performance between new and returning customers. |
| **Sales Amount By Payment Method** | `Payment_Method`, `Sales_Amount` | Donut Pie Chart | Shows the most commonly used payment methods. |
| **Average Discount By Product Category** | `Product_Category`, Average of `Discount` | Clustered Column Chart | Displays the average discount given per product category. |
| **Total Sales By Sales Channel** | `Sales_Channel`, `Sales_Amount` | Clustered Column Chart | Compares total sales across different sales channels. |

---

### 🧮 Dashboard Creation
A new sheet named **"Dashboard"** was created to combine all the visualizations into an **interactive Excel dashboard**.  
This dashboard presents key insights at a glance, integrating all charts generated from the pivot tables.

To enhance interactivity, **three slicers** were added and connected to all pivot tables:
- `Product_ID`
- `Month`
- `Sales_Rep`
- `Region`

These slicers allow users to dynamically filter and analyze the data from multiple perspectives.

---

### 🧠 Tools and Functions Used
- **Excel Functions:** `TEXT`, `AVERAGE`, `SUM`,   
- **Features Used:** Excel Tables, Pivot Tables, Slicers, Charts, and Dashboards  
- **Chart Types:** Clustered Column, 3-D Clustered Column, Pie, and Donut Charts  

---

This structured approach ensured that the analytical process from data cleaning to dashboard visualization was transparent, reproducible, and easy to interpret.


# Results and Insights 

# Future Work

# References and Resources

