# Covid19 Analytics

# 🦠 Covid19 Data Analytics on Azure

## 📘 Project Overview
This project demonstrates a complete **data analytics pipeline** for analyzing COVID-19 data using **Microsoft Azure** and **Power BI**.  
The goal is to extract raw data and process it through Azure services and visualize key insights through interactive dashboards.

<img width="1514" height="488" alt="Image" src="https://github.com/user-attachments/assets/07ca2c7a-3801-4fe6-a806-f87f2f4814b1" />


---

## 🧩 Architecture Overview
The workflow consists of three main stages:

1. **Raw Data Source (Covid19)**
   - Add raw COVID-19 datasets (cases, deaths, recoveries,......)
   - Data stored in Azure Blob Storage or Azure SQL Database
  


2. **ETL & Data Processing**
   - Use **Azure Synapse Analytics** for data transformation (ETL)
   - Clean, filter, and aggregate data to create the dataset `COVID_details`
     
<img width="1483" height="591" alt="Image" src="https://github.com/user-attachments/assets/7585795a-e322-490a-bd15-b8a2f6d07b14" />

3. **Visualization (Power BI)**
   - Connect Power BI to Azure Synapse
   - Build KPIs, charts, and dashboards for COVID-19 insights

---

## 🧠 Technologies Used
- **Azure Synapse Analytics**
- **Azure SQL Database**
- **Power BI**
- **SQL**
- **ETL Pipelines**

---

## ⚙️ Steps Implemented
1. Imported COVID-19 raw data into Azure.
2. Designed ETL pipeline to clean and load the data into `COVID_details`.
3. Created analytical KPIs such as:
   - Total Cases
   - Recovery Rate
   - Death Rate
   - Active Cases
4. Built a Power BI dashboard and steps :
 - Download the powerbi desktop.
 - click on Get-Data. Choose synapse analytics.
   
<img width="1392" height="814" alt="Image" src="https://github.com/user-attachments/assets/e815f3cc-55f2-47bf-8fb4-5c4992f85f32" />

 - Enter the endpoint of your synapse workspace.

<img width="1608" height="528" alt="Image" src="https://github.com/user-attachments/assets/f0aee195-1388-41c3-b7d3-959605e47235" />



 - Enter the username of your dedicated sql server and the password.
   
<img width="1436" height="740" alt="Image" src="https://github.com/user-attachments/assets/f9d0163e-b711-4a87-b35f-c5f9b01eb2fd" />

 - The data in synapse analytics is correctly loaded in PowerBI.
   
<img width="1275" height="826" alt="Image" src="https://github.com/user-attachments/assets/0a7968ab-83c5-497f-8bf9-14bc9be9f0b2" />


---

## 📊 Dashboard Preview

<img width="1184" height="670" alt="Image" src="https://github.com/user-attachments/assets/09ca3565-738d-4cde-b509-c63d8528869f" />

---


