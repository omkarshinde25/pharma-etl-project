# Pharma ETL and Data Cleaning Project

This project demonstrates data cleaning, correction, transformation, and visualization of a Pharmaceutical Products Dataset.  
The implementation is done using Power BI with ETL concepts, simulating practical data analyst and BI developer workflows.

---

## Project Preview
![Pharma ETL Power BI](Screenshot%202025-09-26%20200632.png)

---

## Project Structure
Pharma-ETL-Project/  
│── Pharma ETL Internal.pbix   - Power BI ETL transformations  
│── pharma_data_cleaning_transformation_questions.pdf   - Practice-based tasks  
│── data/   - Raw and cleaned datasets
│── README.md   - Project documentation  

---

## Data Cleaning and Transformation Tasks
1. Remove duplicate rows based on Product_ID  
2. Handle missing values in Expiry_Date  
3. Standardize Supplier names  
4. Convert Order_Date and Expiry_Date into Date format  
5. Create Total_Sales = Unit_Price × Quantity  
6. Split Strength into Strength_Value and Strength_Unit  
7. Replace outlier Unit_Price (>400) with category average  
8. Correct inconsistent Form entries  
9. Mark products as Expired or Valid  
10. Group by Category and calculate Average Unit_Price  
11. Fix inconsistent country names  
12. Normalize Popularity_% between 0–100  
13. Calculate Remaining_Shelf_Life in days  
14. Extract Yearly Sales from Order_Date  
15. Categorize products as High Demand (>70%) or Low Demand  
16. Correct negative or zero Quantity values  
17. Merge supplier details with Supplier_Country  
18. Pivot Form as columns with Quantity values  
19. Unpivot for Power BI star-schema modeling  
20. Create Revenue_Category as Low (<5000), Medium (5000–20000), High (>20000)  

---

## Features
- End-to-end ETL pipeline simulation  
- Data cleaning and standardization including duplicates, nulls, and outliers  
- Transformation-ready dataset for BI reporting  
- Interactive Power BI dashboards with insights  

---

## Tools and Technologies
- Power BI for ETL and Visualization  
- SQL and Python for conceptual ETL logic  
- Excel or CSV as raw data source  

---

## Power BI Dashboard Highlights
- Sales trends across categories  
- High vs Low demand products  
- Supplier and manufacturing country distribution  
- Expired vs valid product tracking  
- Revenue segmentation (Low, Medium, High)  

---

## How to Use
1. Clone this repository  
   git clone https://github.com/omkarshinde25/pharma-etl-project.git  
2. Open Pharma ETL Internal.pbix in Power BI Desktop  
3. Explore the applied ETL transformations and dashboards  
4. Use the practice questions PDF to replicate tasks in SQL or Python  

---
