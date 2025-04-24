
# 📊 Bellabeat Case Study: How Can a Wellness Technology Company Play It Smart?
This repository presents an end-to-end case study that follows the data analysis process (Ask, Prepare, Process, Analyze, Share, and Act) to help Bellabeat — a health-focused smart device company — gain insights from smart device usage and shape their marketing strategy accordingly.

# 📌 Project Summary
## Business Task
Analyze smart device usage data to identify trends and apply insights to one Bellabeat product to inform marketing strategy.

# 🧭 Case Study Roadmap
## 1️⃣ Ask
* **Problem:** Understand how consumers use smart devices, especially fitness trackers.
* **Goal:** Apply these insights to Bellabeat products and guide their marketing strategy.
* **Stakeholders:** Urška Sršen (Chief Creative Officer), Sando Mur (Co-founder), Marketing Analytics Team.

## 2️⃣ Prepare
**Dataset Used**
* 📁 [FitBit Fitness Tracker Dataset](https://www.kaggle.com/datasets/arashnic/fitbit) (Public Domain)
* Data includes: activity, heart rate, sleep, calories, steps, and more from 30 individuals.

**Format & Credibility**
* Stored as CSVs in wide format.
* While limited in size (only 30 users), the data is credible, public, and well-documented.
* Licensing: CC0 (Public Domain)

## 3️⃣ Process
**Tools Used**
* Python (Pandas, Matplotlib, Seaborn)
* Jupyter Notebooks

**Cleaning Steps**
* Removed duplicates and null values
* Normalized time formats
* Converted data types for accurate analysis
* Merged datasets where appropriate (e.g., steps with calories)
🧹 Documented in [/notebooks/data_cleaning.ipynb](https://github.com/RyanAttia/Bellabeat-Case-Study/blob/main/notebooks/data_cleaning.ipynb)

## 4️⃣ Analyze
**Exploratory Data Analysis (EDA) Highlights**
* Positive correlation between total steps and calories burned.
* Users are more active on weekdays vs weekends.
* Most users do not meet the recommended 10,000 steps/day.
* Users who sleep more tend to be slightly more active.
📈 See charts in [/notebooks/eda.ipynb](https://github.com/RyanAttia/Bellabeat-Case-Study/blob/main/notebooks/eda.ipynb)

## 5️⃣ Share
**Visualizations**
* Heatmaps of activity correlation
* Distribution of step counts
* Sleep duration vs activity bar plots
📊 See [/notebooks/visualizations.ipynb](https://github.com/RyanAttia/Bellabeat-Case-Study/blob/main/notebooks/visualizations.ipynb) and [/images](https://github.com/RyanAttia/Bellabeat-Case-Study/tree/main/images) folder

**Audience**
* Bellabeat Executive Team
* Goal: Visual insights to support marketing strategy

## 6️⃣ Act
**High-Level Marketing Recommendations**
1. **Feature Active Usage Stories**  
   Target marketing around average active hours and how Bellabeat helps track consistent health routines.

2. **Push Notifications for Inactivity**  
   Add smart reminders via the Bellabeat app when users drop below the activity threshold.

3. **Sleep + Activity Insights**  
   Market the Leaf/Time device with bundled sleep wellness programs.

4. **Focus on Workweek Campaigns**  
   Most active days are weekdays — design campaigns around “start your week strong” challenges.
   
# 🗂️ Folder Structure

```r
Bellabeat-Case-Study/
│
├── data/
│   └── raw/               # Original Kaggle CSV files
│   └── processed/         # Cleaned datasets
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── visualizations.ipynb
│
├── images/                # Exported plots and charts
│
├── README.md              # Case study overview (this file)
└── presentation/          # Google Slides or PowerPoint file
```

# 🧩 Tools & Skills Used
* **Languages:** Python, SQL
* **Libraries:** Pandas, Matplotlib, Seaborn, NumPy
* **Tools:** Jupyter, Google Slides
* **Concepts:** Data Cleaning, EDA, Data Visualization, Business Insight Generation

# 🌐 Portfolio Integration
"In this project, I acted as a junior data analyst at Bellabeat to analyze smart device usage patterns using Fitbit data. I applied real-world data cleaning, analysis, and visualization techniques to uncover trends that helped inform a marketing strategy for one of Bellabeat’s key products."
