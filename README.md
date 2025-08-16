
# 🚔 Police Traffic Stop Analysis

This project analyzes the **Stanford Open Policing dataset** using Python and Pandas.  
The goal is to explore patterns in traffic stops, arrest rates, and searches,  
and to investigate potential bias based on gender and time of day.

## 📊 Project Workflow
1. Data Cleaning:
   - Handled missing values (`driver_gender`).
   - Dropped irrelevant columns (`county_name`, `state`).
   - Combined date & time into datetime index.

2. Exploratory Data Analysis (EDA):
   - Violation distribution by gender.
   - Search rate comparison (male vs female).
   - Frisk analysis.
   - Hourly arrest rate trends.

3. Visualization:
   - Bar charts for gender-based violations and search rates.
   - Line chart for hourly arrest rate.

## ✅ Key Insights
- Speeding is the most common violation across genders.
- Male drivers are searched at a higher rate than females.
- Arrest rates peak during late-night hours.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

## 📂 Files
- `police_analysis.ipynb` → Full Jupyter Notebook
- Dataset: [Stanford Open Policing Project](https://openpolicing.stanford.edu)

## 📌 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/police-traffic-stop-analysis.git
