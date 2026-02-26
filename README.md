# Data Wrangling with GDP, Energy, and ScimEn Data

## Project Overview
This project demonstrates **data wrangling and cleaning** using three real-world datasets:
1. **Energy Indicators** – Energy Supply and Renewable metrics.  
2. **World Bank GDP** – GDP data from 1960–2015.  
3. **ScimEn** – Country ranking based on journal citations.  

The main goal was to merge these datasets, clean inconsistencies, and extract insights for the **top 15 countries by ScimEn rank**.

---

## Tasks Performed
- Cleaned and standardized country names.  
- Converted missing values and handled invalid entries.  
- Adjusted units (e.g., converting Energy Supply).  
- Extracted GDP data for the **last 10 years (2006–2015)**.  
- Merged the datasets on `Country`.  
- Selected the **top 15 countries** based on rank.  
- Ensured the final DataFrame has **15 rows × 20 columns** in the correct order.  

---

## Final Dataset
- **Rows**: 15 countries  
- **Columns**: 20  
- Structure includes:
  - Rank, Documents, Citable Documents, Citations, H-index  
  - Energy Supply & Renewable metrics  
  - GDP for 2006–2015  

---

## Key Learning Outcomes
- Handling messy data with Pandas.  
- Renaming, dropping, and standardizing columns.  
- Dealing with missing and inconsistent data.  
- Merging multiple datasets from different sources.  
- Following **PEP8 documentation** and adding **Markdown intuition** in Jupyter notebooks.  

---
