
# Bellabeat Fitbit Case Study

This repository documents an end-to-end data analysis project using public Fitbit data.  
The goal is to uncover trends in user behavior and generate actionable insights that support Bellabeat’s **product development** and **marketing strategy**.

---

## 📌 Project Objective

The aim of this case study is to analyze trends in the use of non-Bellabeat smart devices (such as Fitbit) in order to gain insights into user behavior and preferences.  
These insights were used to:

- Enhance Bellabeat’s product features  
- Personalize the user experience  
- Design marketing campaigns that align with actual user habits

---

## 📁 Project File Structure

This repository includes the **core notebooks and presentations only**.  
To keep the repo lightweight, all large datasets and intermediate folders are hosted externally (see Drive link below).

```
bellabeat-fitbit-case-study/
│
├── bellabeat_preparing/
│   └── preparing.ipynb
│
├── bellabeat_processing/
│   └── processing.ipynb
│
├── bellabeat_analysis/
│   └── analysing.ipynb
│
├── presentations/
│   ├── Bellabeat Case Study.pptx
│   └── Bellabeat Stakeholder.pptx
│
└── README.md
```

📂 For all data files, intermediate folders, and cleaning steps, access the full project files on Google Drive:  
➡️ [Google Drive – Full Data & Project Structure](https://drive.google.com/drive/folders/17b1w0YfQfEh5DNPYm_6umOAU4d-WnfGz?usp=sharing)

---

## 🔄 Project Workflow

### 1. Preparing Phase
- Merged datasets with same structure
- Transformed wide-to-long format for time-based data
- Output: clean, unified CSVs

### 2. Processing Phase
- Fixed date/time and data types
- Removed nulls, duplicates, and outliers
- Validated the final datasets for analysis

### 3. Analysis Phase
- Explored trends in:
  - Calories burned
  - Steps
  - Sleep
  - Manual vs. automatic logs
- Identified usage patterns over hours/days

### 4. Share Phase
- Two PowerPoint presentations created:
  - Full case documentation
  - Stakeholder-ready summary

---

## 🎯 Key Insights

- **Peak Activity**: 3–7 PM on weekdays
- **Light Activity** dominates user behavior
- **Manual Logs**: 64.8% log weight manually
- **Average BMI**: 24.81 — slightly high → opportunity for weight tracking
- **Engagement drops**: Weekends and evenings

---

## ✅ How to Reproduce

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/bellabeat-fitbit-case-study.git
cd bellabeat-fitbit-case-study
```

### 2. Run Jupyter Notebooks
- `bellabeat_preparing/preparing.ipynb`
- `bellabeat_processing/processing.ipynb`
- `bellabeat_analysis/analysing.ipynb`

### 3. View Presentations
- `presentations/Bellabeat Case Study.pptx`
- `presentations/Bellabeat Stakeholder.pptx`

---

## 📈 Project Goal Summary

Transform raw wearable device data into business-relevant insights:

- Understand real user behavior  
- Inform product feature design  
- Support data-backed marketing strategies  

---

## 📂 Access All Files

Full data files, intermediate outputs, and validation folders are available here:  
➡️ [Google Drive – Full Project Files](https://drive.google.com/drive/folders/17b1w0YfQfEh5DNPYm_6umOAU4d-WnfGz?usp=sharing)

---

## 🚀 Next Steps

- Build interactive dashboards (Power BI / Tableau)  

---

## 💬 Contact

Feel free to reach out or fork the repo for further exploration.
