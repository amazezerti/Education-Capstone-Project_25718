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
   │   ├── education_long_format.csv

├── notebooks/
   │   ├── education_analysis.ipynb
   │   ├── Machine Learning_ Linear Regression.png
   │   ├── Libraries Installement.png
   │   ├── Innovative Feature_Custom Trend Analysis.png
   │   ├── Exploratory Data Analysis.png
   │   ├── Data Loading and Preprocessing.png
   │   ├── education_long_format.csv

├── visuals/
   │   ├── dist_completion_2023.png
   │   ├── trends_regions.png
   │   ├── clusters_2023.png
   │   ├── trend_World.png

├── powerbi/
   │   ├── education_dashboard.pbix
   
│   ├── README.md   

├── docs/
   │   ├── presentation.pptx

│   ├── Metadata_Indicator_API_SE.PRM.CMPT.FE.ZS_DS2_en_csv_v2_20335.csv
│   ├── Metadata_Country_API_SE.PRM.CMPT.FE.ZS_DS2_en_csv_v2_20335.csv
   

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
- 📸 Screenshot: <img width="2856" height="1832" alt="Data Loading and Preprocessing" src="https://github.com/user-attachments/assets/19d628a8-3f21-4cf9-b93e-6a22b8f70dac" />


### 2️⃣ EDA  
- Histogram & trend plots for regions  
- ✅ Outputs:  
  - `dist_completion_2023.png`  <img width="1000" height="600" alt="dist_completion_2023" src="https://github.com/user-attachments/assets/c3bb8c83-2494-4940-ac6a-ccd009fe85fa" />

  - `trends_regions.png`   <img width="800" height="550" alt="trends_regions" src="https://github.com/user-attachments/assets/28e556f0-8ed5-409c-8c33-9c37be392df1" />

- 📸 Screenshot: <img width="2880" height="1850" alt="Exploratory Data Analysis" src="https://github.com/user-attachments/assets/c224b75b-1ec1-4b03-aa34-0938116e0d13" />


### 3️⃣ Linear Regression  
- Trained model using 2000–2022 data  
- ✅ Metrics (e.g., `MSE`, `R²`) printed in console  
- 📸 Screenshot: <img width="2862" height="1822" alt="Machine Learning_ Linear Regression" src="https://github.com/user-attachments/assets/a37134fb-f64d-419b-a4ad-4eaebd656a05" />


### 4️⃣ K-Means Clustering  
- Clustered countries into 3 groups  
- ✅ Output: `clusters_2023.png`  <img width="1000" height="600" alt="clusters_2023" src="https://github.com/user-attachments/assets/0a188c53-6e97-42b0-9efe-ecaf9228a702" />

- 📸 Screenshot: 
<img width="1000" height="600" alt="clusters_2023" src="https://github.com/user-attachments/assets/3e6ef94f-1d39-4d3e-b910-c6b1d85d7200" />

### 5️⃣ Custom Trend Analysis  
- Calculated World region growth rate  
- ✅ Output: `trend_World.png`, printed growth rate  <img width="1000" height="600" alt="trend_World" src="https://github.com/user-attachments/assets/936b41ad-b618-40a4-b639-939bd955968b" />

- 📸 Screenshot:<img width="2860" height="1824" alt="Innovative Feature_Custom Trend Analysis" src="https://github.com/user-attachments/assets/1e9396d8-50a9-470d-87cc-7a2faf5ff323" />


### 6️⃣ Power BI Dashboard  
- ✅ Features:  
  - Line chart, histogram, clustered bar chart  
  - Geo map, slicers, DAX metric  
  - Key Influencers visual  
- 📸 Screenshot: <img width="3056" height="1626" alt="DASHBOARD POWERBI" src="https://github.com/user-attachments/assets/8ea01a0e-8e49-4603-a34e-33d52bce1a96" />

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
For questions, contact us or the instructor: [eric.maniraguha@auca.ac.rw]
---
