# 🔄 Proyecto 2 – ETL & EDA con KNIME

Este flujo de trabajo fue desarrollado como parte del **Proyecto 2 del programa de formación en IA y Ciencia de Datos (IMPÈLIA)**.  
Se utilizó la herramienta **KNIME** para realizar procesos de limpieza, transformación y análisis exploratorio de datos (ETL & EDA)  
sobre un conjunto de datos inmobiliarios reales de Barcelona (Fotocasa).

📌 **Objetivo**  
Preparar un dataset estructurado y limpio, listo para su uso en procesos posteriores de machine learning y visualización (Power BI).

---

## 🧠 Características del flujo de trabajo

- Eliminación de duplicados, valores inconsistentes y nulos
- Imputación lógica de valores faltantes con la mediana o categoría "Unknown"
- Transformación de tipos de datos y redondeo numérico
- Agrupaciones por vecindario para inferir valores desconocidos
- Detección y tratamiento de outliers con filtros condicionales
- Sustitución lógica de valores erróneos mediante reglas (Rule Engine)
- Revisión estadística antes y después de cada paso

🗂️ Archivo KNIME: `Project_2_ETL.knwf`  
📄 Documentación detallada: `Documentacion_ETL_EDA.pdf`  
📁 Carpeta: `/ETL_KNIME/`

---

🔧 Este flujo de trabajo se complementa con la visualización final del proyecto en Power BI, disponible en la carpeta `/PowerBI/ → Final Project`.
