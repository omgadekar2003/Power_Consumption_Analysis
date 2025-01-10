
# Power Consumption Analysis Project

## Overview

This project focuses on analyzing power consumption data for multiple zones based on various environmental factors such as temperature, humidity, wind speed, and diffuse solar radiation. The analysis was carried out using a combination of data extraction, data cleaning, transformation, and visualization. The final results are presented through a dynamic report or dashboard created using Microsoft Excel. Also explre this:([https://github.com/omgadekar2003/Power-Consumption-Prediction-Analysis])

## Table of Contents

- [Project Description](#project-description)
- [Data](#data)
- [Process](#process)
  - [Data Extraction](#data-extraction)
  - [Data Cleaning](#data-cleaning)
  - [Data Transformation](#data-transformation)
  - [Reporting & Dashboard](#reporting-dashboard)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [License](#license)

## Project Description

The goal of this project is to analyze the relationship between environmental variables (temperature, humidity, wind speed, etc.) and power consumption in three zones of a building. Through data cleaning and transformation, insights were derived, and a dynamic Excel-based report/dashboard was created for easy analysis and visualization.

## Data

The dataset used for the analysis contains the following features:

| Column                  | Description                                  |
|-------------------------|----------------------------------------------|
| `Temperature`            | Temperature (°C)                             |
| `Humidity`               | Humidity (%)                                 |
| `WindSpeed`              | Wind Speed (m/s)                             |
| `GeneralDiffuseFlows`    | General Diffuse Solar Radiation (W/m²)       |
| `DiffuseFlows`           | Diffuse Solar Radiation (W/m²)              |
| `Day`                    | Day of the month                             |
| `Month`                  | Month of the year                            |
| `PowerConsumption_Zone1` | Power Consumption in Zone 1 (kWh)            |
| `PowerConsumption_Zone2` | Power Consumption in Zone 2 (kWh)            |
| `PowerConsumption_Zone3` | Power Consumption in Zone 3 (kWh)            |

## Process

### Data Extraction

Data was collected from the provided dataset which contains environmental and power consumption data for multiple days and months. The data was initially in CSV format, making it easy to load and manipulate using Excel.

### Data Cleaning

The raw dataset had some issues, such as:
- Missing values in temperature, humidity, wind speed, and power consumption columns.
- Outliers in the power consumption data.

Steps taken during data cleaning:
- Imputation of missing values with median values.
- Removal or capping of outliers to improve model performance and prevent skewed analysis.

### Data Transformation

Once cleaned, the data was transformed to:
- Create aggregated monthly and daily averages for power consumption.
- Normalize temperature, humidity, and wind speed for better comparative analysis.
- Generate new variables like temperature-based power consumption patterns.

### Reporting & Dashboard

An interactive dashboard was created using Excel, which includes:
- **Charts**: Power consumption trends over time for each zone, temperature vs. power consumption, etc.
- **Pivot Tables**: Aggregated power consumption data, broken down by day, month, and zone.
- **Conditional Formatting**: Highlight areas with high or low power consumption.
  
The dashboard provides an intuitive interface for users to explore the data and gain insights into power consumption patterns.

## Technologies Used

- **Data Extraction**: Microsoft Excel
- **Data Cleaning & Transformation**: Microsoft Excel (functions, formulas, pivot tables)
- **Data Visualization**: Microsoft Excel (Charts, Pivot Tables, Conditional Formatting)
  
## How to Use

1. Clone this repository to your local machine.
2. Open the provided Excel file (e.g., `PowerConsumption_Analysis.xlsx`).
3. Explore the dashboard and visualizations created in the file.
4. You can modify the data or update the dashboard by adding new data entries in the respective sheet.

Open `PowerConsumption_Analysis.xlsx` in Excel to start exploring the dashboard.



Feel free to adjust any section based on your specific details or changes made in your project!

Regards,
Om
