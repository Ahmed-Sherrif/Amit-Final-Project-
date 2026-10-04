## Extended Project Description

This project demonstrates a complete, multi-tool data analytics workflow designed to turn raw mobile device sales data into actionable business intelligence. The pipeline systematically addresses data hygiene, statistical outlier management, and executive visualization through a three-stage process:

1. **Excel (Exploratory Prep & Baseline Calculations):** 
   Performed preliminary data inspection, initial formatting, schema validation, and baseline summary metrics to establish a reliable foundation for downstream processing.

2. **Python (Data Cleansing & Outlier Detection):** 
   Utilized `Pandas` , `seaborn` , `matplotlib.pyplot` and `NumPy` to handle missing values (null imputation), execute schema transformations, and apply statistical outlier filtering (IQR/Z-score methods) to ensure high data integrity and eliminate skews.

3. **Power BI (DAX Modeling & Interactive Dashboarding):** 
   Imported the clean dataset into Power BI to construct a robust Star Schema data model. Developed complex **DAX measures** (time-intelligence functions, dynamic KPIs, regional share) and authored a dynamic, interactive dashboard featuring cross-filtering, drill-through capabilities, and executive summary viewports.
