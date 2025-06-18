# SAP-Style Inventory Data Cleanup & Power BI Prep

This project simulates a real-world data analyst workflow using a grocery inventory dataset to mimic operational SAP exports. It demonstrates skills in data extraction, cleaning, transformation, and reporting—aligned with enterprise requirements for analytics and BI integration.

---

## 🔧 What This Project Does

- 🧼 **Loads and cleans raw operational data**
- 🔄 **Standardizes column formats and handles missing values**
- 🧠 **Adds classification logic** (e.g., "Low" vs "Healthy" inventory)
- 📊 **Outputs a clean CSV ready for Power BI dashboards**

---

## 📁 File Structure

```plaintext
data project/
├── data/
│   ├── clean_inventory.csv       ← cleaned, dashboard-ready dataset
│   └── raw data/
│       └── inventory_data.csv    ← original raw inventory file
├── etl_pipeline.ipynb            ← Jupyter Notebook used to process the data
├── README.md                     ← you are here
