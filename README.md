# ⚡ Electric Vehicle Insights Dashboard

## 📁 Power BI Dashboard

💾 [Download Dashboard (.pbix)](Electric_Vehicles.pbix)

## 📊 Project Overview
This project focuses on analyzing a dataset of electric vehicle (EV) registrations to build an interactive Power BI dashboard. The aim is to extract meaningful insights about EV adoption, types, geographical distribution, and pricing.

## 🗂️ Dataset Description
The dataset contains 150,482 rows and includes the following columns:

- **VIN (1-10)**: First 10 characters of the vehicle identification number
- **County**: County of registration
- **City**: City of registration
- **State**: State of registration
- **Postal Code**: ZIP code
- **Model Year**: Year of the vehicle model
- **Make**: Vehicle manufacturer
- **Model**: Specific model of the EV
- **Electric Vehicle Type**: Type of EV (e.g., Battery Electric, Plug-in Hybrid)
- **CAFV Eligibility**: Clean Alternative Fuel Vehicle eligibility status
- **Electric Range**: Full-charge range in miles
- **Base MSRP**: Manufacturer’s Suggested Retail Price
- **Legislative District**: Policy district
- **DOL Vehicle ID**: Licensing identifier
- **Vehicle Location**: Geographic coordinates or address
- **Electric Utility**: Power provider in the region
- **2020 Census Tract**: Census demographic location

## 🛠️ Tools Used
- Power BI (Dashboard and visualizations)
- Excel / Power Query (Data wrangling)
- Python (CSV splitting and preprocessing)

## 🎯 Objectives
- Analyze EV distribution by region
- Compare models, makes, and electric range
- Evaluate CAFV eligibility across regions
- Visualize EV registrations and pricing trends

## 📁 File Structure
```
data/
├── full_dataset.csv
├── first_half.csv
└── second_half.csv

reports/
└── PowerBI_Dashboard.pbix
```

## 📈 Dashboard Features
- Filters by Make, Model Year, CAFV Eligibility
- Top EVs by popularity and range
- Price distribution charts
- Interactive maps showing geographic EV patterns
