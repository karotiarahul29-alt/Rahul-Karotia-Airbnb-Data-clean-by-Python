#  Airbnb Data Cleaning & EDA Project (Python)

## Project Overview
This project focuses on cleaning and analyzing Airbnb Open Data using Python and its data-handling libraries.  
The goal is to build a clean, structured, and analysis-ready dataset that can be used for insights, reporting, or machine learning.

---

##  Dataset
- **Source:** Airbnb Open Data (CSV file)
- **Rows:** ~50,000 (after cleaning)
- **Columns:** Price, Room Type, Host Info, Neighbourhood, Reviews, etc.

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning Steps Performed
1. Loaded raw dataset and inspected structure  
2. Removed duplicate records using unique listing ID  
3. Handled missing values (drop/impute depending on column type)  
4. Standardized inconsistent column names  
5. Fixed incorrect data types (e.g., dates → datetime)  
6. Cleaned price & numeric fields  
7. Removed outliers using statistical methods (IQR / Z-score)  
8. Exported cleaned dataset for analysis

---

## 📊 Exploratory Data Analysis (EDA)
- Price distribution  
- Room type distribution  
- Neighbourhood-level analysis  
- Correlation heatmap  
- Host listing patterns  
- Top 10 most expensive areas  

---

## 🔍 Key Insights
- Strong variation in price across neighbourhoods  
- Entire homes/apartments dominate the listings  
- Certain hosts manage 50+ listings  
- Price is influenced by availability, location, and property type  

---

## 📁 Project Structure

