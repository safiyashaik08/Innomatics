Food Delivery Data Integration and Analysis:

Project Overview
The objective of this project was to integrate fragmented data from three different sources to create a unified dataset for business intelligence. By combining order transactions,
user demographics, and restaurant metadata, I developed a master dataset that allows for deep analysis of revenue drivers and customer behavior.

Technical Process:
1. Data Extraction: I utilized Python to ingest raw data in CSV and JSON formats. To handle the SQL data, I implemented Regular Expressions (Regex) to programmatically extract restaurant details from raw INSERT statements.

2. Relational Data Merging: I performed multi-stage Left Joins to enrich the 10,000+ order records. This process ensured data consistency while connecting orders to specific user memberships and restaurant cuisines.

3. Data Cleaning: I standardized currency formats and date strings to ensure analytical accuracy, resulting in a finalized Master Dataset file.

Key Business Insights:

Market Performance Chennai emerged as the highest revenue-generating city specifically among Gold Members.

Product Analytics Mexican cuisine was identified as having the highest Average Order Value (AOV) across the platform.

Customer Loyalty The data confirms that Gold Members contribute a significantly higher percentage of total revenue compared to regular users.

Quality Correlation The highest volume of orders is concentrated in restaurants maintaining a rating between 4.1 and 4.5.

Repository Contents:

Food_Delivery_Analysis.ipynb: Full Python source code and logic.

final_food_delivery_dataset.csv: The final merged and cleaned output file.

Source Data: Original files (orders.csv, users.json, restaurants.sql).

Developed by:Shaik Safiya

Environment: Google Colab, Python, Pandas
