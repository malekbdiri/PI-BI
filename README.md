# PI-BI
PBI-report
# Power BI Report: Power Pioneer Data

## 📌 Project Overview

This Power BI report is a comprehensive data visualization project designed to help analyze, visualize, and derive insights from a variety of datasets. The report is structured to ensure clarity, performance, and scalability, making it suitable for business analysis, sales tracking, inventory management, and other analytical purposes.

## 📊 Key Features

* **Interactive Dashboards:** Multi-page dashboards with slicers for dynamic data filtering.
* **Data Connections:** Securely connected to a SQL Server database (`DW_supplychain`).
* **Custom Visualizations:** Enhanced data storytelling using DAX and M scripts.
* **Clustering Analysis:** Machine learning-based clustering (KMeans, DBSCAN, Agglomerative) for product segmentation.
* **Star and Snowflake Schema:** Optimized data model for efficient analysis.

## 🚀 Usage Instructions

1. **Loading the Report:**

   * Open the `.pbix` file in Power BI Desktop.
   * Refresh data connections if required.

2. **Data Sources:**

   * SQL Server Database: `DW_supplychain`
   * Local CSV files (e.g., `clustering_results.csv`).

3. **Interacting with Dashboards:**

   * Use slicers for dynamic filtering.
   * Hover over visuals for detailed tooltips.

## ⚡ Development Setup

* **Git Version Control:**

  * Use Git LFS for `.pbix` files.
  * Track DAX and M scripts in a separate `scripts` folder.

* **Python Integration:**

  * Install `matplotlib` and `seaborn` in the Python environment used by Power BI.
  * Ensure the Python environment path is correctly set in Power BI settings.

* **Deployment (GitHub):**

  * Set up GitHub Actions for CI/CD (optional).
  * Push updates using:

    ```bash
    git push origin master
    ```

## 🚦 Best Practices

* Maintain a single source of truth for the data model.
* Use descriptive names for measures, columns, and visuals.
* Regularly clean up unused visuals and queries.
* Optimize DAX scripts for performance.

## 📌 License

This project is for educational and personal use. Commercial use requires explicit permission.

