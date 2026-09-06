# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is a Data Analytics project that analyzes agricultural activities across different seasons, geographical areas, farming conditions, resource usage, environmental conditions, crop production, and economic performance.

The main purpose of this project is to identify **seasonal patterns, trends, relationships, variations, and differences in agricultural performance** using data analysis, statistics, and visualization techniques.

---

## 🎯 Problem Statement

Agricultural performance is influenced by seasonal environmental conditions, farming practices, resource availability, and market conditions. Therefore, agricultural performance can vary significantly from one season to another.

Raw agricultural data does not directly explain these differences. This project analyzes the dataset to understand how agricultural performance changes across seasons and identifies meaningful patterns, relationships, trends, and variations.

---

## 🎯 Objectives

The major objectives of this project are:

* Explore and understand the agricultural dataset.
* Clean and prepare the data for analysis.
* Analyze agricultural performance across different seasons.
* Identify important seasonal patterns and trends.
* Investigate relationships between environmental conditions and agricultural outcomes.
* Compare crops, regions, and farming practices.
* Analyze resource usage and efficiency.
* Examine economic performance such as revenue, cost, and profit.
* Identify unusual or significant patterns.
* Apply statistical analysis and data visualization.
* Generate evidence-based insights and recommendations.

These objectives follow the requirements specified in the project brief.

---

## 📂 Dataset

The dataset contains **4,000 agricultural records** with information related to farms, crops, seasons, environmental conditions, farming practices, production, resources, and economic performance.

### Main Features

| Feature                         | Description                        |
| ------------------------------- | ---------------------------------- |
| `Farm_ID`                       | Unique farm identifier             |
| `State`                         | State where the farm is located    |
| `District`                      | District where the farm is located |
| `Crop`                          | Crop cultivated                    |
| `Season`                        | Agricultural season                |
| `Farm_Area_Hectares`            | Farm area in hectares              |
| `Rainfall_mm`                   | Rainfall received                  |
| `Avg_Temperature_C`             | Average temperature                |
| `Humidity_pct`                  | Humidity percentage                |
| `Sunlight_Hours_Day`            | Daily sunlight hours               |
| `Soil_pH`                       | Soil pH value                      |
| `Soil_Moisture_pct`             | Soil moisture percentage           |
| `Nitrogen_kg_ha`                | Nitrogen usage                     |
| `Phosphorus_kg_ha`              | Phosphorus usage                   |
| `Potassium_kg_ha`               | Potassium usage                    |
| `Irrigation_Method`             | Irrigation method                  |
| `Fertilizer_kg_ha`              | Fertilizer usage                   |
| `Pesticide_Litre_ha`            | Pesticide usage                    |
| `Seed_Quality_Score`            | Seed quality score                 |
| `Yield_Tonnes_Ha`               | Crop yield per hectare             |
| `Production_Tonnes`             | Total production                   |
| `Market_Price_INR_Tonne`        | Market price                       |
| `Total_Cost_INR`                | Total production cost              |
| `Revenue_INR`                   | Revenue generated                  |
| `Profit_INR`                    | Profit or loss                     |
| `Water_Used_m3`                 | Water consumption                  |
| `Water_Efficiency_t_per_1000m3` | Water efficiency                   |
| `Disease_Pest_Risk_pct`         | Disease and pest risk              |

---

## 🛠️ Technologies Used

### Programming

* **Python**

### Libraries

* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization

### Environment

* **Jupyter Notebook**
* **Google Colab**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Dataset Understanding
   ↓
Data Quality Checking
   ↓
Data Cleaning & Preparation
   ↓
Exploratory Data Analysis
   ↓
Seasonal Analysis
   ↓
Crop & Regional Analysis
   ↓
Resource Usage Analysis
   ↓
Environmental Analysis
   ↓
Economic Analysis
   ↓
Statistical Analysis
   ↓
Visualization
   ↓
Insights & Conclusions
   ↓
Recommendations
```

---

## 📊 Analysis Performed

### 1. Seasonal Performance Analysis

Agricultural performance was compared across:

* Kharif
* Rabi
* Zaid

The analysis examined:

* Average yield
* Total production
* Average profit
* Rainfall
* Temperature
* Disease and pest risk

### 2. Crop Analysis

Different crops were compared based on:

* Average yield
* Average profit
* Production performance
* Economic performance

### 3. Irrigation Analysis

Different irrigation methods were analyzed:

* Drip
* Sprinkler
* Rainfed
* Flood

The analysis focused on:

* Yield
* Profit
* Water consumption
* Water efficiency

### 4. Environmental Analysis

Relationships between agricultural performance and environmental variables were investigated, including:

* Rainfall
* Temperature
* Soil moisture
* Disease and pest risk

### 5. Economic Analysis

The project examines:

* Revenue
* Total cost
* Profit
* Market price
* Yield and profitability relationships

### 6. Statistical Analysis

Correlation analysis was used to identify relationships between important numerical variables.

---

## 📈 Key Visualizations

The project contains visualizations such as:

* Average Yield by Season
* Average Profit by Season
* Total Production by Season
* Average Profit by Crop
* Average Yield by Irrigation Method
* Average Water Usage by Irrigation Method
* Water Efficiency vs Yield
* Yield vs Profit
* Average Rainfall by Season
* Disease & Pest Risk by Season
* Correlation Analysis

---

# 🔍 Key Findings

### 🌱 1. Kharif showed the strongest overall performance

Kharif had the highest average yield and total production among the three seasons.

* **Average Yield:** 5.64 tonnes/ha
* **Total Production:** 82,387.61 tonnes
* **Average Profit:** ₹178,914.65

This indicates that Kharif performed strongly across production and economic indicators.

---

### 💰 2. Zaid showed the weakest economic performance

Zaid had the lowest average yield and recorded a negative average profit.

* **Average Yield:** 4.67 tonnes/ha
* **Average Profit:** -₹24,804.82

This suggests that Zaid farming conditions in the dataset were economically less favorable.

---

### 🌾 3. Crop selection strongly affected profitability

The analysis showed considerable differences in profitability between crops.

The highest average profits were observed for:

* Sugarcane
* Chilli
* Cotton

Some crops, including Rice, Wheat, Maize, and Pulses, showed negative average profits in the analyzed dataset.

---

### 💧 4. Drip irrigation showed strong performance

Drip irrigation had the highest average yield and average profit among the irrigation methods.

* **Average Yield:** 6.62 tonnes/ha
* **Average Profit:** ₹219,626
* **Average Water Efficiency:** 6.27 tonnes/1,000 m³

This indicates a strong association between drip irrigation and agricultural performance in the dataset.

---

### 🚿 5. Flood irrigation consumed the most water

Flood irrigation recorded the highest average water usage:

* **Average Water Used:** approximately 8,026 m³

This highlights the importance of examining irrigation practices from a resource-efficiency perspective.

---

### 📈 6. Water efficiency was strongly associated with yield

The correlation between:

**Water Efficiency ↔ Yield = 0.915**

This represents a strong positive relationship in the dataset.

---

### 💵 7. Yield was positively associated with profit

The correlation between:

**Yield ↔ Profit = 0.490**

Higher yield was generally associated with higher profit, although yield alone does not determine profitability.

---

### 📦 8. Production was strongly related to yield

The correlation between:

**Production ↔ Yield = 0.885**

This indicates a strong positive relationship between production and yield.

---

### 🌧️ 9. Seasonal environmental conditions differed

Kharif recorded substantially higher rainfall than Rabi and Zaid.

| Season | Avg. Rainfall |
| ------ | ------------: |
| Kharif |     852.08 mm |
| Rabi   |     436.00 mm |
| Zaid   |     299.42 mm |

Temperature also differed across seasons, with Zaid having the highest average temperature.

---

### 🐛 10. Disease and pest risk varied by season

Kharif recorded the highest average disease/pest risk:

| Season | Avg. Risk |
| ------ | --------: |
| Kharif |    54.47% |
| Rabi   |    40.48% |
| Zaid   |    38.22% |

This suggests that seasonal conditions may be associated with differences in disease and pest risk.

---

## 📌 Correlation Highlights

| Relationship              | Correlation |
| ------------------------- | ----------: |
| Water Efficiency ↔ Yield  |   **0.915** |
| Production ↔ Yield        |   **0.885** |
| Profit ↔ Yield            |   **0.490** |
| Revenue ↔ Yield           |   **0.434** |
| Water Used ↔ Yield        |   **0.389** |
| Market Price ↔ Yield      |  **-0.384** |
| Rainfall ↔ Yield          |       0.031 |
| Temperature ↔ Yield       |       0.009 |
| Soil Moisture ↔ Yield     |       0.010 |
| Disease/Pest Risk ↔ Yield |       0.013 |

> **Note:** Correlation indicates association and does not establish causation.

---

## 💡 Recommendations

Based on the analysis, the following recommendations can be considered:

1. **Optimize seasonal crop planning** based on historical seasonal performance.
2. **Consider efficient irrigation methods**, particularly drip irrigation, where appropriate.
3. **Monitor water efficiency** as an important agricultural performance indicator.
4. **Select crops based on both yield and profitability**, rather than yield alone.
5. **Monitor disease and pest risk**, especially during seasons with higher observed risk.
6. **Analyze production costs and market prices** before making crop-selection decisions.
7. **Use regional and seasonal performance data** to support evidence-based agricultural planning.
8. Continue collecting more historical data to improve the reliability of seasonal comparisons.

The project brief specifically emphasizes using analytical findings to support evidence-based agricultural planning.

---

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── 📊 DOC-20260906-WA0002.csv
│
├── 📓 Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── 📑 Seasonal_Agriculture_Performance_Analysis_Presentation.pptx
│
└── 📄 README.md
```

---

## 📓 Notebook

The Jupyter Notebook contains the complete analysis, including:

* Data loading
* Data exploration
* Data cleaning
* Statistical analysis
* Seasonal comparisons
* Crop analysis
* Irrigation analysis
* Environmental analysis
* Economic analysis
* Data visualization
* Correlation analysis
* Findings
* Conclusions
* Recommendations

The project is documented as a complete analysis in a Jupyter Notebook, as required by the project brief.

---

## 🎓 Project Outcome

The analysis provides a data-driven understanding of how agricultural performance varies across seasons, crops, irrigation methods, environmental conditions, resource usage, and economic factors.

The findings can help in understanding seasonal agricultural patterns and can support better planning and decision-making. However, the observed relationships should be interpreted as **associations within the available dataset rather than proof of causal relationships**.

---

## 👨‍💻 Author

**Navinchand Sahu**

BE Computer Engineering
University of Mumbai

---

## ⭐ Conclusion

The **Seasonal Agriculture Performance Analysis** demonstrates how Data Analytics can be applied to a real-world agricultural dataset to identify meaningful patterns and relationships.

The analysis indicates that **season, crop selection, irrigation method, resource efficiency, environmental conditions, and economic factors** are associated with differences in agricultural performance.

The project follows the intended focus of the assignment: exploring seasonal differences, identifying significant observations, interpreting analytical findings, and developing evidence-based recommendations.
