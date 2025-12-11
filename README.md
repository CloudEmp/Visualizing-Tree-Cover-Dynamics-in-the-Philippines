<div align="center">

# 🌳 **Visualizing Tree Cover Dynamics in the Philippines**
### *A Provincial Assessment of Tree Cover Loss (2001–2023)*

</div>

---

## 📌 Overview
This repository contains the final Data Visualization project that examines tree cover loss across Philippine provinces from 2001 to 2023. Using Tableau and Tableau Prep, the project integrates multiple datasets and a provincial shapefile to build a complete dashboard that visualizes spatial patterns, provincial rankings, statistical summaries, and temporal trends in tree cover change. The dashboard combines choropleth maps, bar charts, scatter plots, line charts, and exploratory data analysis views to help users better understand the distribution and behavior of tree cover loss across the country.

---

## 📊 Dashboard Features

### 🗺️ Choropleth Maps
- Percent tree cover loss by province  
- Total tree cover loss across provinces  
- Annual tree cover loss visualization  

### 📈 Statistical Visualizations
- Sorted bar charts for total and percent loss  
- Scatter plots showing density and percent loss relationships  
- Time series chart of national and hotspot province trends  
- Combined EDA dashboard with descriptive statistics, histograms, scatter plots, and annual loss data  

### 🧩 Data Integration
- Region and island group classification  
- Geographic mapping using a Philippine provincial shapefile  

---

## 📂 Datasets Used
**Dataset.csv**  
Tree cover extent, gains, and annual loss from 2001 to 2023  

**Islands.csv**  
Region and island group classifications for all provinces  

**GADM41 Shapefile**  
Geographic boundary data used for mapping provinces in Tableau  

---

## 🛠️ Tools and Technologies
- Tableau  
- Tableau Prep  

---

## ⚙️ Setup Instructions

Follow the steps below to open and run the dashboard using the files in this repository.

### 1. Download or Clone the Repository
You may either  
- click **Code → Download ZIP** and extract the folder, or  
- run:

### 2. Keep the Folder Structure Intact
Ensure the following structure remains unchanged


Do not rename or move the **data** folder, as Tableau uses these paths when loading data sources.

### 3. Open the Tableau Workbook
1. Launch **Tableau Desktop**  
2. Open:


### 4. Verify Data Connections
Tableau will automatically connect to the CSV files and shapefile if the folder structure is unchanged.  
If Tableau asks you to locate a data source:
- Browse to the `data` folder  
- Select the correct CSV or shapefile component  

### 5. Optional: Open the Tableau Prep Flow
If you want to view or modify the preprocessing steps:
- Open **Tableau Prep**
- Load the `.tfl` file inside the `tableau` folder

### 6. Explore the Dashboard
Use the navigation buttons inside the workbook to switch between visualization pages:
- Combined Dashboard  
- Choropleth Map  
- Sorted Bar Charts  
- Scatter Plot  
- Year-Pivoted Line Chart  
- EDA Dashboard  

---

## 🎯 Project Purpose
This project aims to identify and compare provinces with the highest and lowest levels of tree cover loss and to highlight spatial and temporal patterns that can support environmental assessment and policy direction. The visualizations focus on provincial hotspots, national patterns, and variations across regions and island groups in alignment with the project's analytical objectives.

---

## 👥 Authors
- Drew Darwin Cruz  
- Melchor Ray Domingo
- Tristan Daniel Sigua  

---

<div align="center">

### 🌱 *Thank you for viewing our project!*

</div>


