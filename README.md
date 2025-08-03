# 🎓 **Education Capstone Project: Analyzing Global Female Primary Completion Rates**

**👤 Author:** ABDRAMANE MAHAMAT ADJI ZEZERTI  
**🆔 Student ID:** 25718  
**🏫 Institution:** *Adventist University of Central Africa*  
**📘 Course:** *Big Data Capstone Project*  
**👨‍🏫 Instructor:** [Eric Maniraguha](email:eric.maniraguha@auca.ac.rw)  

---

## 📚 **Project Overview**
This project analyzes **global female primary completion rates** to uncover trends, disparities, and influencing factors. It utilizes:
- **World Bank dataset:** `API_SE.PRM.CMPT.FE.ZS_DS2_en_csv_v2_20335.csv`
- **DATASET LINK:**[https://data.worldbank.org/indicator/SE.PRM.CMPT.FE.ZS?locations=1W&start=1972&end=2023&view=chart]
- **Python:** for preprocessing, exploratory data analysis (EDA), linear regression & K-Means clustering
- **Power BI:** for interactive visualization  
- **Custom trend analysis:** calculates regional average yearly growth rates

🔍 The repository ensures **reproducibility** and includes all code, visuals, and the dashboard.

### 🎯 Key Objectives:
- 🧼 Clean and preprocess data  
- 📊 Perform EDA  
- 📈 Apply **Linear Regression** for 2023 predictions  
- 🧠 Use **K-Means Clustering**  
- 📐 Custom trend analysis  
- 🖥️ Power BI dashboard creation  
- 📝 Documentation for instructor submission  

---

## 📂 **Repository Structure**

CapstoneProject/
├── data/

│   ├── API_SE.PRM.CMPT.FE.ZS_DS2_en_csv_v2_20335.csv
│   ├── cleaned_education_data.csv

├── notebooks/
│   ├── education_analysis.ipynb

├── visuals/
│   ├── dist_completion_2023.png
│   ├── trends_regions.png
│   ├── clusters_2023.png
│   ├── trend_World.png

├── powerbi/
│   ├── education_dashboard.pbix

├── docs/
│   ├── README.md
│   ├── presentation.pptx

📌 **Ensure all files are in place** before running analysis.

---

## 🛠️ **Setup Instructions**

### 🔧 Prerequisites:
- Anaconda Navigator  
- Jupyter Notebook  
- Power BI Desktop  
- Python Libraries:  
  
  pip install pandas numpy matplotlib seaborn scikit-learn
 
- Git

### 🚀 Installation:

git clone https://github.com/[amazezerti]/Education-Capstone-Project_25718.git
cd Education-Capstone-Project_25718


### 📂 Verify Dataset:
Make sure `API_SE...csv` is in the `data/` folder. If missing, download from World Bank.

### 🧪 Set Up Environment:

cd C:\Users\USER\CapstoneProject\notebooks
jupyter notebook

Open `education_analysis.ipynb` and run all cells.

Plots are saved to `visuals/`  
Cleaned data is saved to `data/cleaned_education_data.csv`

### 📊 Open Power BI:
Open `education_dashboard.pbix` or import `cleaned_education_data.csv`

📌 Ensure the `visuals/` folder exists to avoid plot-saving errors.

---

## 📈 **Project Tasks & Outputs**

### 1️⃣ Data Preprocessing  
- Removed unwanted columns, filled missing values, cleaned years  
- ✅ Output: `data/cleaned_education_data.csv`  
- 📸 Screenshot: *Insert data cleaning screenshot*

### 2️⃣ EDA  
- Histogram & trend plots for regions  
- ✅ Outputs:  
  - `dist_completion_2023.png`  
  - `trends_regions.png`  
- 📸 Screenshot: *Insert histogram & trend plot screenshots*

### 3️⃣ Linear Regression  
- Trained model using 2000–2022 data  
- ✅ Metrics (e.g., `MSE`, `R²`) printed in console  
- 📸 Screenshot: *Insert regression metric screenshot*

### 4️⃣ K-Means Clustering  
- Clustered countries into 3 groups  
- ✅ Output: `clusters_2023.png`  
- 📸 Screenshot: *Insert clustering scatter plot*

### 5️⃣ Custom Trend Analysis  
- Calculated World region growth rate  
- ✅ Output: `trend_World.png`, printed growth rate  
- 📸 Screenshot: *Insert trend plot screenshot*

### 6️⃣ Power BI Dashboard  
- ✅ Features:  
  - Line chart, histogram, clustered bar chart  
  - Geo map, slicers, DAX metric  
  - Key Influencers visual  
- 📸 Screenshot: *Insert dashboard screenshot*

📌 Power BI is central—open in Desktop to explore features.

---

## 🔍 **Key Findings**
- 📈 *Global Trends:* Increasing overall, persistent disparities  
- 🌍 *Regional Disparities:* Sub-Saharan Africa regions lag behind  
- 🧠 *Clustering Insights:* Three country groups by completion rate  
- 📉 *Predictive Modeling:* Regression reasonably accurate  
- 📊 *Growth Rate:* Calculated yearly average for “World”  


---

## 🚀 **Future Work**
- Add socio-economic datasets (GDP, literacy)  
- Try **ARIMA** for time-series forecasting  
- Power BI enhancements (tooltips, AI visuals)

---

## 📚 **References**
- 📊 World Bank Education Data  
- 🐍 Python Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- 📈 Power BI Desktop

---

## 🙌 **Thank You!**
This project delivers a comprehensive analysis using big data tools to inform **global education strategies**.  
For questions, contact **ABDRAMANE MAHAMAT ADJI ZEZERTI** or the instructor: [eric.maniraguha@auca.ac.rw]
---
