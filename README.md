# 🛒 Store 1: Preparing Customer Data for Loyalty Program Analytics  

## 📌 Introduction
Store 1 is preparing to launch a **Customer Loyalty Program** and requires a clean, structured, and reliable customer database to design personalized marketing campaigns.  
This project focuses on **data cleaning, transformation, and preparation**, enabling future customer segmentation and KPI analysis.  

---

## 📂 Dataset
A sample dataset was provided in the form of a **Python list of lists**. Each entry represents a customer profile with the following fields:

- `usuario_id` → unique customer ID  
- `usuario_nombre` → customer name (inconsistent formatting)  
- `usuario_edad` → age (numeric, requires validation)  
- `categorias_fav_low` → list of favorite product categories (e.g., ELECTRÓNICA, LIBROS)  
- `gasto_por_categoria` → list of spending amounts per category  

Example entry:  
```python
['32415', ' mike_reed ', 32.0, ['ELECTRÓNICA', 'DEPORTE', 'LIBROS'], [894, 213, 173]]

⚙️ Methodology

The project includes the following key steps:

Data Cleaning

Trimmed whitespace and standardized customer names

Normalized case formatting

Validated and corrected inconsistent ages

Data Transformation

Calculated total spend per customer

Matched categories with spending amounts for consistency

Validation & Error Handling

Checked for mismatches between categories and spending lists

Verified that all customers had valid IDs, names, and numeric ages

Business Readiness

Prepared dataset to enable customer segmentation

Structured data for future KPI analysis (average spend, category preferences, etc.)

📊 Key Deliverables

Cleaned and standardized customer dataset

Calculated total spend per user

Dataset structured for segmentation by age, spending, and category

Prepared foundation for Loyalty Program marketing analytics

✅ Conclusion

This project demonstrates:

Python skills in list and string processing

Data cleaning and preprocessing for business-ready datasets

Preparation for customer segmentation and KPI analysis

By ensuring high-quality data, Store 1 can confidently design targeted campaigns and optimize their Customer Loyalty Program.

💻 Tech Stack

Python

Jupyter Notebook

📈 Next Steps

In the next sprint, the cleaned dataset will be used for:

Customer segmentation analysis

KPI calculations (spending by category, lifetime value, etc.)

Insights to guide loyalty program strategies

🤝 Contact

Created by [Your Name]
🔗 LinkedIn
 | Portfolio
