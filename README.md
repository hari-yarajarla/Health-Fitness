# FitTrack – Health & Fitness Data Analysis

## Overview
FitTrack – Health & Fitness Data Analysis is a data-driven project aimed at understanding the relationship between sleep health and various lifestyle factors such as BMI, age, occupation, physical activity, and alcohol consumption.  
The project applies Exploratory Data Analysis (EDA) techniques to extract meaningful insights from health data and visualize patterns through Power BI dashboards.

---

## Objectives
- To analyze health and fitness data and identify key patterns affecting sleep quality.  
- To determine correlations between demographic, lifestyle, and biological variables.  
- To visualize findings using Power BI for better interpretation and decision-making.  
- To create a foundation for future predictive analytics in health monitoring.

---

## Project Architecture
```
[ Sleep_health.csv Dataset ]
        ↓
[ Data Preprocessing (Python: Pandas, NumPy) ]
        ↓
[ Exploratory Data Analysis (Matplotlib, Seaborn) ]
        ↓
[ Visualization Dashboard (Power BI) ]
        ↓
[ Insights and Reports ]
```

---

## Key Insights
- Most individuals sleep between 6–8 hours per day.  
- BMI and physical activity levels show a strong correlation with sleep duration.  
- Sedentary occupations are associated with higher BMI and lower sleep quality.  
- Age groups display distinct sleep behaviors; younger adults show more irregular sleep patterns.  
- Minimal gender-based differences were observed.

---

## Technologies Used

| Category | Tools / Technologies |
|-----------|----------------------|
| Programming | Python (Jupyter Notebook) |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Visualization | Power BI |
| Dataset | Sleep_health.csv |
| Documentation | Microsoft Word, PowerPoint |

---

## Data Preprocessing
- Removed irrelevant column (“Sleep Disorder”) not required for EDA.  
- Checked for and handled missing or duplicate records.  
- Converted categorical variables (e.g., Gender, Occupation) into numeric formats.  
- Validated data consistency and cleaned anomalies.  

---

## Exploratory Data Analysis
- Histograms used to visualize sleep and activity distributions.  
- Boxplots identified outliers in BMI and activity levels.  
- Correlation heatmap generated to analyze relationships among features.  
- Power BI dashboard developed for interactive visualization and analysis.

---

## Results
- Most individuals sleep between 6–8 hours daily.  
- Strong correlation found between BMI, Age, and Physical Activity with sleep duration.  
- Dashboard effectively illustrated data patterns by gender, occupation, and age group.  

---

## Advantages
- Comprehensive exploratory analysis covering multiple health metrics.  
- Structured preprocessing and cleaning workflow for reliable results.  
- Integration of Python and Power BI for combined technical and business insights.  
- Reproducible and adaptable open-source design for future research.  

---

## Limitations
- No predictive modeling implemented; analysis limited to EDA.  
- Dropping the “Sleep Disorder” column restricted deeper insights.  
- Visual outputs were not extended into hypothesis testing or inferential statistics.

---

## Future Scope
- Apply machine learning algorithms (e.g., Random Forest, Logistic Regression) for sleep disorder prediction.  
- Incorporate real-time data from wearable fitness devices.  
- Build an interactive mobile application for personalized health insights.  
- Extend the dashboard to include diet, stress, and environmental factors.

---

## Repository Structure
```
FitTrack-Health-Fitness-Analysis/
│
├── health&fitness.ipynb                # Python Notebook for EDA
├── Sleep_health.csv                    # Dataset
├── health&fitness dashboard.pbix       # Power BI Dashboard
├── Fit track-health&fitness data Analysis.pptx  # Project Presentation
├── DOCUMENT ON HEALTH&FITNESS ANALYSIS.pdf      # Detailed Project Report
└── README.md                           # Project Overview
```

---

## Author
**Hari Brahma Chari**  
Email: [your email here]  
LinkedIn / GitHub: [your profile link here]
