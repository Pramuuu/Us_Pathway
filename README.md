# Us_Pathway

# Data Science Internship at Futurense Technologies  

## 🚀 Overview  
This repository contains the analysis, insights, and machine learning models developed during a Data Science internship at Futurense Technologies (June–September 2024). The primary objective was to analyze business data, build predictive models, and provide actionable insights to improve business strategies.

---

## 🎯 Goals  
- Analyze business data to uncover patterns and trends.  
- Build predictive models for customer behavior and campaign performance.  
- Optimize operations like resource allocation and customer retention.  
- Provide insights through reports and dashboards.

---

## 📁 Project Components  

### 1. **Data Collection**  
Collected datasets included:  
- **Campaign Data**: Spend, impressions, clicks, and platform details.  
- **Leads Data**: Graduation details, work experience, and lead behavior.  
- **Phone Metrics**: Call records and communication data.  
- **Application Tracker**: Lead status throughout the process.  

---

### 2. **Data Preparation**  
Key preprocessing steps:  
- **Data Cleaning**: Handled missing values and outliers.  
- **Feature Engineering**: Derived variables like customer scores.  

---

### 3. **Exploratory Data Analysis (EDA)**  
- Trends in campaign effectiveness, customer behavior, and sales data.  
- Platform-specific CTR analysis (Facebook, Google, LinkedIn).  
- Seasonal and regional performance variations.  

---

### 4. **Machine Learning Models**  

#### **Campaign Spend Prediction (CampaignML)**  
- **Objective**: Predict total campaign spend using impressions and clicks data.  
- **Best Model**: Random Forest Regressor.  
  - R²: 0.71  
  - MAE: 263.11  

#### **Lead Quality Prediction (LeadML)**  
- **Objective**: Classify leads into quality levels for prioritization.  
- **Best Model**: Random Forest Classifier.  
  - Accuracy: 85%  
  - F1-Score: 0.86  

---

### 5. **Pipeline Architecture**  
Built an automated data pipeline using **Azure Services**:  
1. **Data Extraction**: Automated data retrieval from Google Sheets.  
2. **Data Storage**: Azure Data Lake for raw and cleaned data.  
3. **Data Cleaning**: Executed in Azure Databricks using Jupyter Notebooks.  
4. **Model Execution**: Scalable ML models run on Azure Databricks.  
5. **Deployment**: Real-time predictions via Azure Web App Services.

---

### 6. **Tools and Technologies**  
- **Programming**: Python (pandas, NumPy, Scikit-learn).  
- **Visualization**: Matplotlib, Seaborn, Power BI.  
- **Cloud**: Azure Data Factory, Data Lake, Databricks.  
- **Deployment**: Flask apps integrated with Azure Blob Storage.

---

## 🔍 Key Insights  

- **Platform Performance**:  
  - Google had the highest CTR.  
  - Facebook accounted for the highest spending, while LinkedIn had the highest CPC.  

- **Seasonal Trends**:  
  - Lead generation and conversions peaked during March–April.  
  - Conversion times improved consistently over the year.  

- **Counselor Performance**:  
  - Zareen achieved the fastest lead conversions.  
  - Shashwat showed the highest average conversion time (>70 days).

---

## 🌐 Web Applications  

### 1. **CampaignML Web App**  
- **Input**: Impressions, clicks.  
- **Output**: Predicted campaign spend.  
- **Tech Stack**: Flask, Bootstrap, Azure Web App Services.  

### 2. **LeadML Web App**  
- **Input**: Lead features.  
- **Output**: Predicted lead success likelihood.  
- **Tech Stack**: Flask, Bootstrap, Azure Web App Services.  

---

## 📊 Power BI Dashboard  
Key visualizations include:  
- Lead generation and payment trends.  
- Campaign ROI analysis.  
- Counselor performance tracking.

---

## 🏆 Conclusion  
This project leveraged Azure services, machine learning, and visualization tools to automate workflows and provide actionable insights. The solutions developed have helped optimize business strategies and improve operational efficiency.  

---

## 🛠️ How to Use This Repository  
1. Clone the repository.  
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
