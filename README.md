# 🛍️ Store 1: Customer Loyalty Data Preparation & Segmentation  

## 📌 Introduction
Store 1 is preparing to launch a **Customer Loyalty Program** and requires a clean, structured, and reliable customer database to design personalized marketing campaigns.  
This project focuses on **data cleaning, transformation, and preparation** to enable effective customer segmentation, KPI tracking, and targeted marketing strategies.

---

## 📂 Dataset
The dataset is provided as a **Python list of lists**, simulating raw customer records.

Each record contains:
- `usuario_id` – unique customer ID  
- `usuario_nombre` – customer name (inconsistent formatting)  
- `usuario_edad` – customer age (requires validation)  
- `categorias_fav_low` – list of favorite product categories (e.g., ELECTRÓNICA, LIBROS, DEPORTE)  
- `gasto_por_categoria` – spending amounts per category  

Example record:
```python
['32415', ' mike_reed ', 32.0, ['ELECTRÓNICA', 'DEPORTE', 'LIBROS'], [894, 213, 173]]
## ⚙️ Methodology  

### Part 1 – Data Preparation (Sprint 1)  
- Trimmed whitespace and standardized customer names  
- Normalized case formatting  
- Validated and corrected inconsistent ages  
- Calculated total spend per customer  
- Matched categories with spending amounts for consistency  
- Corrected typos and other data inconsistencies  
- Prepared structured dataset for further analysis  

### Part 2 – Customer Segmentation (Sprint 2)  
- Explored customer demographics and purchase behavior  
- Analyzed spending patterns across categories  
- Segmented customers by age group, product preferences, and total spending  
- Identified actionable insights for loyalty marketing campaigns  

---

## 📊 Key Deliverables  
- Cleaned and standardized customer dataset  
- Calculated total spend per user and per category  
- Dataset structured for segmentation by demographics and purchase behavior  
- Actionable insights to guide Loyalty Program strategy  

---

## ✅ Conclusion  
This project demonstrates:  
- Python skills in list, string, and data structure processing  
- Data cleaning & preprocessing for business‑ready datasets  
- Segmentation analysis to support targeted marketing  
- Preparation of high‑quality data for KPI analysis and decision‑making  

---

## 💻 Tech Stack  
- Python  
- Pandas (for segmentation)  
- Jupyter Notebook  

---

## 📈 Next Steps  
- Perform deeper segmentation analysis on cleaned dataset  
- Calculate advanced KPIs (e.g., lifetime value, category profitability)  
- Use insights to optimize loyalty program campaigns  

---

## 🤝 Contact  
Created by **[Your Name]**  
🔗 [LinkedIn](#) | 🌐 [Portfolio](#)
