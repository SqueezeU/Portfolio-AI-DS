## 🧩 Project 2 – ETL & EDA with KNIME

This workflow was developed as part of **Project 2** during my AI and Data Science training at **IMPÈLIA**.  
The **KNIME** tool was used to perform data cleaning, transformation, and exploratory analysis (ETL & EDA)  
on a real estate dataset from Barcelona (Fotocasa).

---

### 🎯 Objective

Prepare a clean, structured dataset ready for further machine learning and visualization processes (Power BI).

---

### 🔧 Workflow Overview

![KNIME Workflow](../Images/KNIME%20Workflow.png)

*Visual representation of the complete data processing pipeline*

---

### 🌸 Workflow Features

- Removal of duplicates, inconsistent values, and nulls  
- Logical imputation of missing values using median or the "Unknown" category  
- Type conversions and numeric rounding  
- Neighborhood-based grouping to infer unknown values  
- Detection and treatment of outliers using conditional filters  
- Replacement of erroneous values using rules (Rule Engine)  
- Manual review of outliers before and after each phase

---

📎 **KNIME file:** `Project_2_ETL.knwf`  
📄 **Detailed documentation:** `Documentacion_ETL_EDA.pdf`  
📂 **Folder:** `/ETL_KNIME/`

---

This workflow is complemented by the final Power BI dashboard,  
> available in the [`PowerBI`](https://github.com/SqueezeU/Portfolio-AI-DS/tree/main/PowerBI) folder.
