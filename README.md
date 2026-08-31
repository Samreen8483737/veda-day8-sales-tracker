# Day 8: Automated Sales Tracker & Data Management

## Project Overview
This project focuses on transitioning from static data visualization to dynamic data management. I built a lightweight, automated Sales Tracker in Google Sheets that separates raw data entry from aggregated metrics, mimicking a real-world relational database structure.

## Technical Implementations
* **Data Architecture:** Designed a two-tab structure (`Sales-Entries` and `Summary-Dashboard`) to protect summary formulas from raw data manipulation.
* **Data Integrity:** Implemented Data Validation (dropdown menus for Product Categories) to standardize inputs and prevent typographical errors from data entry users.
* **Dynamic Aggregation:** Engineered `SUMIFS` formulas to automatically calculate Daily, Weekly, and Monthly sales totals based on live, conditional date ranges.
* **Automated Calculations:** Utilized dynamic multiplication logic for continuous, error-free order total calculations as new rows are added.

## Key Takeaway
Building this tracker reinforced the importance of structural data integrity. By utilizing Data Validation and `SUMIFS`, I created a dashboard that not only automatically updates in real-time but is also resistant to standard user entry errors.
