# Bellabeat Fitbit Case Study

This repository documents an end-to-end data analysis project using public Fitbit data.  
The goal is to uncover trends in user behavior and generate actionable insights that support Bellabeat’s **product development** and **marketing strategy**.

---

## 📌 Project Objective

The aim of this case study is to analyze trends in the use of non-Bellabeat smart devices (such as Fitbit) in order to gain insights into user behavior and preferences.  
These insights will be used to:

- Enhance Bellabeat’s product features  
- Personalize the user experience  
- Design marketing campaigns that align with actual user habits

---

## 📁 Folder Structure

```
bellabeat-fitbit-case-study/
│
├── raw_data/
│   └── mturkfitbit_export_3.12.16-5.12.16/
│       Original CSV exports from two periods (Mar–May 2016)
│
├── bellabeat_preparing/
│   ├── preparing.ipynb
│   ├── appended_data/
│   ├── after_convert/
│   └── final_preparing_data/
│       Merged and transformed datasets ready for processing
│
├── bellabeat_processing/
│   ├── processing.ipynb
│   ├── data_after_standardization_and_type_change/
│   ├── data_after_removing_nulls_and_duplicates/
│   ├── data_after_removing_outliers/
│   ├── final_prepared_data/
│   └── validation_scripts/
│       Helper scripts to verify cleaning results
│
├── bellabeat_analysis/
│   ├── analysis.ipynb
│   └── final_prepared_data/
│       Datasets used for charts and trend exploration
│
├── presentations/
│   ├── bellabeat_case_study.pptx
│   └── bellabeat_stakeholder.pptx
│       PowerPoint summaries for technical and executive audiences
│
└── README.md
```

---

## 🔄 Project Workflow

### 1. Preparing Phase
- Combined datasets with the same schema
- Transformed wide-to-long format for time-based data
- Created clean, unified CSVs for further processing

### 2. Processing Phase
- Converted dates and types
- Removed duplicate and null values
- Eliminated outliers (e.g., >50,000 steps/day, unrealistic weight)
- Validated each step to ensure clean, reliable data

### 3. Analysis Phase
- Performed Exploratory Data Analysis (EDA)
- Analyzed:
  - Activity levels by hour and day
  - Calories burned, steps taken, and sleep quality
  - Manual vs. automatic logging habits
- Generated graphs and dashboards

### 4. Share Phase
- Created two presentations:
  - `bellabeat_case_study.pptx`: full methodology and insights
  - `bellabeat_stakeholder.pptx`: key findings for business impact

---

## 🎯 Key Insights & Outcomes

- **Peak Activity Time**: Users are most active between 3–7 PM
- **Preferred Intensity**: Light-intensity activity (like walking) dominates
- **Manual Logging**: 64.8% still log weight manually – automation is underused
- **BMI Profile**: Average BMI is 24.81 (upper-normal range) – opportunity for weight-tracking features
- **Weekend Drop-off**: Sunday and late evenings show lowest engagement

---

## ✅ How to Reproduce the Project

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/bellabeat-fitbit-case-study.git
cd bellabeat-fitbit-case-study
```

### 2. Run the Preparation Notebook
```bash
Open bellabeat_preparing/preparing.ipynb
```

### 3. Run the Processing Notebook
```bash
Open bellabeat_processing/processing.ipynb
```

### 4. Explore the Analysis
```bash
Open bellabeat_analysis/analysis.ipynb
```

### 5. View the Presentations
```bash
Open presentations/bellabeat_case_study.pptx or bellabeat_stakeholder.pptx
```

---

## 📈 Project Goal Summary

This project aims to translate raw smart device data into meaningful insights by:

- Identifying real user habits
- Informing product design
- Driving Bellabeat’s marketing decisions with data

---

## 🚀 Future Enhancements

- Integrate demographic/external sources for deeper segmentation
- Build interactive dashboards using Power BI or Tableau
- Publish case findings in a portfolio or blog

---

## 💬 Contact

For questions or collaboration, feel free to reach out or fork this repository and build upon it!
