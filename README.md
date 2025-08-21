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
