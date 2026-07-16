# Partner-Company-Project-01-Python-Sales-Product-Analytics-

Comprehensive analysis of sales, calendar data, and product catalog for a partner company
This project develops a complete analytical workflow in Python using multiple data sources (FACT and DIM tables) to build a structured dataset for studying weekly sales, categories, products, and regions.
The notebook includes data loading, exploration, initial cleaning, and preparation for deeper analysis such as forecasting, segmentation, or dashboard creation.
xxx
## Project Structure
Code
PartnerCompanyProject_01_Python/
│
├── FACT_SALES.csv
├── DIM_CALENDAR.xlsx
├── DIM_CATEGORY.csv
├── DIM_PRODUCT.xlsx
│
├── PartnerCompanyProject_01_Python.ipynb   ← Main notebook
└── README.md           

## Datasets Used
1. FACT_SALES.csv
Contains the weekly sales history per product.
Key columns:

WEEK — Week in NN-YY format
ITEM_CODE — Product code
TOTAL_UNIT_SALES — Units sold
TOTAL_VALUE_SALES — Total sales value
TOTAL_UNIT_AVG_WEEKLY_SALES — Weekly average units sold
REGION — Sales region or area

2. DIM_CALENDAR.xlsx
Calendar table used to map weeks to actual dates:

WEEK
YEAR
MO## NTH
WEEK_NUMBER
DATE

3. DIM_CATEGORY.csv
Product category catalog:

ID_CATEGORY
CATEGORY

4. DIM_PRODUCT.xlsx
Master product catalog with descriptive attributes:

MANUFACTURER
BRAND
ITEM
ITEM_DESCRIPTION
CATEGORY
FORMAT
ATTR1, ATTR2, ATTR3

## Notebook Objective
The notebook performs:

-Loading of FACT and DIM tables
-Initial exploration of each dataset
-Validation of structure, columns, and data types
-Preparation for advanced analysis:
    ° Joining FACT + PRODUCT + CATEGORY + CALENDAR
    ° Identifying weekly trends
    ° Analysis by brand, category, and region
    ° Preparation for dashboards or predictive models

## Expected Outcomes
-Data integrity validation
-Analytical dataset ready for:
  °Sales forecasting
  °Category or brand segmentation
  °Dashboards in Power BI or Looker Studio
-Identification of weekly and regional patterns

## Technologies Used
-Python 3
-Pandas
-Jupyter Notebook
--Excel / CSV



    
