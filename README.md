# Ecommerce-databricks-project-
Scope of Work: ShopVista Data Modernization Project 
1. Project Overview 
  ShopVista, a rapidly growing e-commerce company, faced significant challenges in 
  managing data distributed across multiple systems and files (orders, shipments, returns, 
  and dimension tables such as customers, products, categories, brands, and dates). This 
  fragmented structure caused manual data reconciliation, delayed business reporting, and 
  limited visibility into operational performance. 
  To address these challenges, the project aims to design and implement a centralized, 
  automated data platform on Microsoft Azure, ensuring a single source of truth for all 
  business reporting and analytics.
2. Objectives 
  • Establish a unified data architecture integrating all key datasets (orders, shipments, 
   returns, and dimensions). 
  • Automate daily ingestion, transformation, and aggregation processes. 
  • Provide clean, reliable, and analytics-ready data using the Bronze → Silver → Gold 
  medallion architecture. 
  • Enable the business team to generate real-time insights through Power BI dashboards. 
3. Scope of Work 
  3.1 Data Architecture & Platform Setup 
    • Configure Azure Data Lake Storage Gen2 (ADLS) for centralized data storage. 
    • Set up Databricks as the data processing and transformation engine. 
    • Implement folder structures and access policies for Bronze, Silver, and Gold layers. 
  3.2 Data Ingestion (Bronze Layer) 
    • Automate daily ingestion pipelines to bring raw files (orders, shipments, returns) into 
    ADLS. 
    • Maintain metadata for ingestion status, source file tracking, and error handling. 
  3.3 Data Transformation & Quality (Silver Layer) 
    • Define schemas and enforce data quality checks for each dataset. 
    • Standardize and cleanse data to ensure consistency and accuracy. 
    • Handle nulls, duplicates, and referential integrity across datasets. 
  3.4 Data Integration & Modeling (Gold Layer) 
    • Create integrated fact tables (Orders, Shipments, Returns) enriched with dimension data 
    (Customers, Products, Categories, Brands, Date). 
    • Build a star schema suitable for analytical reporting. 
    • Optimize tables for Power BI consumption. 
