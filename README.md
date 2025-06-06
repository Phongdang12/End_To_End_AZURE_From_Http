# 🚀 Azure Data Pipeline Project – From API to Insights

## 🔍 Overview

This project demonstrates a complete modern data pipeline that extracts raw data from external APIs, ingests it into Azure Data Lake Storage Gen2, and transforms it using Azure Databricks for advanced analytics and reporting.

🔗 Built on **Azure Cloud Services**, this pipeline ensures scalable, secure, and cost-efficient data processing with a clear separation of data layers (Bronze, Silver, Gold) using the **Medallion architecture**.

---

## 📚 Architecture


[External API] <br>
↓ <br>
[Azure Data Factory / Azure Function] <br>
↓ <br>
[Azure Data Lake Storage Gen2 (Bronze)] <br>
↓ <br>
[Azure Databricks Notebook – ETL Processing] <br>
↓ <br>
[Delta Lake – Silver & Gold Layers] <br>
↓ <br>
[Power BI / Azure Synapse Analytics (Optional)]

---

## 🧱 Components

- 🔗 **API Connector** – Connects and extracts raw data from RESTful API endpoints.
- 💾 **Azure Data Lake Gen2** – Stores raw (Bronze), cleaned (Silver), and aggregated (Gold) data.
- 🧠 **Azure Databricks** – Transforms and cleans data using PySpark in scalable notebooks.
- 💼 **Delta Lake** – Enables ACID transactions, schema enforcement, and time travel.
- 📊 **Power BI / Synapse Analytics** – Optional: connect to Gold layer for visualization.

---

## 📐 Data Layering Strategy (Medallion Architecture)

- **Bronze** – Raw data ingested from the API (no transformation).
- **Silver** – Cleaned and validated data, with proper schema and formatting.
- **Gold** – Business-ready datasets, aggregated or joined as needed.

---

## ✨ Author

📸 Your Name – <phong.danghandsomek@hcmut.edu.vn>

---

## 🤝 Contribution

💬 Feel free to fork, improve, and contribute!
