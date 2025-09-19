# Pharma ETL and Data Cleaning Project

This project demonstrates data cleaning, correction, transformation, and visualization of a Pharmaceutical Products Dataset.  
The work is implemented in Power BI with ETL concepts, and tasks are based on practical data analyst exercises.

## Project Structure
Pharma-ETL-Project/
│── Pharma ETL Internal.pbix   # Power BI dashboard and transformations
│── pharma_data_cleaning_transformation_questions.pdf  # Practice questions
│── data/                      # (Optional) Raw and cleaned datasets
│── README.md                  # Project documentation

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
10. Group by Category → Average Unit_Price  
11. Fix inconsistent country names  
12. Normalize Popularity_% between 0–100  
13. Calculate Remaining_Shelf_Life (days)  
14. Extract Yearly Sales from Order_Date  
15. Categorize products: High Demand (>70%) / Low Demand  
16. Correct negative or zero Quantity  
17. Merge supplier details with Supplier_Country  
18. Pivot Form as columns with Quantity values  
19. Unpivot for Power BI modeling  
20. Create Revenue_Category → Low (<5000), Medium (5000–20000), High (>20000)  

## Features
- End-to-end ETL pipeline simulation  
- Cleaning and standardization (duplicates, nulls, outliers)  
- Transformation for effective Power BI modeling  
- Visualization-ready dataset for dashboards  

## Tools and Technologies
- Power BI (ETL and Visualization)  
- SQL/Python (conceptual ETL logic)  
- Excel/CSV (dataset source)  

## Power BI Dashboard
The Power BI report provides insights into:  
- Sales trends  
- Demand categories  
- Supplier and country distribution  
- Expired vs valid products  
- Revenue categorization  

## How to Use
1. Clone the repository:
   git clone https://github.com/omkarshinde25/pharma-etl-project/tree/main
2. Open Pharma ETL Internal.pbix in Power BI Desktop  
3. Review the applied transformations and visuals  
4. Use the PDF file for practice with SQL/Python  

## Author
Omkar Shinde – Data Analyst / BI Developer  
LinkedIn: https://www.linkedin.com/in/omkarshinde25  
GitHub: https://github.com/omkarshinde25  


