Bellabeat Fitbit Case Study
This repository documents an end-to-end data analysis project using public Fitbit data. The goal is to explore user behavior trends and provide actionable insights that support Bellabeat’s product design and data-driven marketing strategy.

📌 Project Objective
Analyze trends in the use of non-Bellabeat smart devices (like Fitbit) to uncover patterns in user behavior and preferences.
These insights will be applied to one of Bellabeat’s products to improve customer experience and inform promotional campaigns that align with the actual habits of the target audience.

📂 Folder Structure
pgsql
نسخ
تحرير
bellabeat-fitbit-case-study/
│
├── raw_data/
│   └── mturkfitbit_export_3.12.16-5.12.16/
│       Original CSV exports, organized by collection date.
│
├── bellabeat_preparing/
│   ├── preparing.ipynb
│   ├── appended_data/
│   ├── after_convert/
│   └── final_preparing_data/
│       • Merged and transformed datasets ready for processing.
│
├── bellabeat_processing/
│   ├── processing.ipynb
│   ├── data_after_standardization_and_type_change/
│   ├── data_after_removing_nulls_and_duplicates/
│   ├── data_after_removing_outliers/
│   ├── final_prepared_data/
│   └── validation_scripts/
│       • Each folder documents a stage of cleaning and validation.
│
├── bellabeat_analysis/
│   ├── analysis.ipynb
│   └── final_prepared_data/
│       • Cleaned input files used for analysis.
│
├── presentations/
│   ├── bellabeat_case_study.pptx         # Detailed documentation
│   └── bellabeat_stakeholder.pptx        # Executive summary for stakeholders
│
└── README.md
🔍 Project Workflow
1. Preparing Phase
Merged datasets with the same schema.

Restructured minute-level data (wide to long format).

Saved standardized CSVs.

2. Processing Phase
Standardized formats (dates, types, columns).

Removed duplicates and nulls.

Removed unrealistic outliers.

Validated all steps with helper scripts.

Produced clean datasets for analysis.

3. Analysis Phase
Conducted exploratory data analysis (EDA).

Analyzed trends by time, activity type, and demographics.

Generated charts and visual insights.

4. Share Phase
Created two presentation decks:

Full case study documentation.

Summary for business stakeholders with insights and marketing recommendations.

🎯 Key Outcomes
Identified peak activity times, preferred activity types, and user engagement habits.

Discovered gaps in device auto-sync usage and health-tracking behavior.

Proposed specific product and marketing strategies based on real user trends.
