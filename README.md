## US Traffic Accidents Analysis & Risk Pattern Identification

**Master’s Course Project | MS in Business Analytics | Summer Semester**

---

### Project Overview
This project analyzes large-scale U.S. traffic accident data to identify severity drivers, temporal trends, and spatial high-risk zones. The goal is to generate actionable insights that can support policymakers, urban planners, and emergency response teams in reducing accident severity and improving road safety.

The analysis uses a 500K-sample from the US Accidents Dataset (2016–2023) and combines exploratory data analysis, machine learning classification, and spatial clustering techniques.

---

###  Business Problem
Road traffic accidents pose a major public safety and economic challenge in the United States, resulting in tens of thousands of fatalities and hundreds of billions of dollars in annual costs. Accurately predicting accident severity and identifying high-risk locations and time periods enables:
- Better infrastructure planning
- Optimized emergency response allocation
- Data-driven transportation safety policies

---

###  Dataset
- **Source:** US Accidents Dataset (Kaggle)
- **Coverage:** 49 U.S. states (2016–2023)
- **Original Size:** ~7 million records
- **Working Sample:** ~500,000 accidents
- **Target Variable:** Accident Severity (Levels 1–4)

---

### Methodology

#### Exploratory Data Analysis
- Temporal analysis (hour of day, weekday vs weekend, seasonality)
- Geographic drill-downs (state, county, city, street-level)
- Infrastructure impact analysis (traffic signals, junctions, crossings)
- Weather and light condition analysis

#### Feature Engineering
- Datetime conversion from accident start time
- Hour, day, month, weekday/weekend, and seasonal indicators
- Ordinal encoding of light levels using twilight variables
- Binary encoding of road infrastructure features

#### Modeling
- **Random Forest Classifier** for severity prediction
- Compared against baseline models
- Feature importance analysis to identify key severity drivers

#### Spatial Analysis
- **K-Means clustering** to identify accident hotspots
- Geographic visualization of high-risk zones
- Calendar-based temporal risk visualization

---

###  Key Techniques & Tools
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Random Forest Classification
- K-Means Clustering
- Jupyter Notebook

---

### Key Insights
- Severity Level 2 accidents dominate (~77–80%)
- Peak accident periods align with weekday commute hours (6–9 AM, 3–6 PM)
- Fall season shows the highest accident volume
- Adverse weather conditions increase severity risk
- Urban counties such as Los Angeles and Miami-Dade exhibit strong hotspot clustering
- Infrastructure elements like traffic signals, junctions, and crossings significantly influence severity

---

###  Business Impact & Applications
- Targeted enforcement during high-risk commuter hours
- Weather-responsive traffic control strategies
- Data-driven infrastructure redesign at high-risk intersections
- Optimized ambulance and emergency service placement
- Proactive safety planning using predictive analytics

---

###  Repository Contents
- **AccidentAnalysis.ipynb** – EDA, feature engineering, modeling
- **Project.ipynb** – Spatial analysis and clustering
- **Project Report (PDF)** – Full methodology and findings
- **Presentation (PPT)** – Executive-level summary and insights

---

###  Note
This project was completed as part of the MS in Business Analytics program. It is intended to demonstrate applied data analytics, machine learning, and business-oriented problem solving using real-world data.
