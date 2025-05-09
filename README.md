# Spark-Based Big Data Analytics with MySQL and ECharts

## **Abstract**
This project presents a comprehensive **big data processing pipeline** leveraging **Apache Spark** for distributed computation, **MySQL** for structured data storage, and **ECharts** for interactive visualization. The system is designed to process heterogeneous datasets (e.g., transaction logs, demographic metadata) and extract actionable insights through temporal-spatial analysis, product categorization, and market trend modeling. Key contributions include:
- **Distributed ETL Pipeline**: Spark-based data cleaning, transformation, and aggregation.
- **Geospatial and Temporal Analysis**: Regional performance metrics and time-series trend extraction.
- **Scalable Architecture**: Modular backend (Flask) and frontend (ECharts) for real-time data exploration.

## **Core Components**
|Module|Technology/Methodology|Description|
|------|----------------------|-----------|
|**Data Ingestion**|HDFS + Spark|Distributed storage and parallel processing of large-scale CSV datasets.|
|**ETL Pipeline**|PySpark (RDD/DataFrame APIs)|Schema alignment, missing value imputation, and UTF-8 encoding optimization.|
|**Data Storage**|MySQL 8.0 (UTF-8mb4)|Structured storage of aggregated metrics (e.g., annual trends, product stats).|
|**Backend API**|Flask (RESTful)|Dynamic data fetching and preprocessing via JSON endpoints.|
|**Frontend UI**|ECharts + HTML5/CSS3|Interactive dashboards for geospatial maps, bar charts, and word clouds.|

## **Methodological Highlights**
1. **Distributed Data Cleaning**
   - Merged multi-source CSV files using Spark.
   - Removed redundant columns (e.g., IDs) and standardized geographic abbreviations.
   - Applied imputation and deduplication strategies for missing/noisy data.

2. **Temporal-Spatial Correlation Analysis**
   - Calculated annual/monthly sales, profit, and return rates.
   - Analyzed regional performance (e.g., coastal vs. inland provinces).

3. **Product and Customer Segmentation**
   - Grouped products by category/subcategory for profitability analysis.
   - Identified customer composition patterns (e.g., individual vs. bulk buyers).