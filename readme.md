# 🚗 What Drives the Price of a Car?

## Overview

The goal of this project is to identify the factors that influence used car prices and generate insights that can help a dealership make informed inventory and pricing decisions.

Using a dataset of used vehicles, exploratory data analysis and data preparation techniques were applied to determine which vehicle characteristics have the strongest impact on price.

---

## Business Problem

A used car dealership wants to understand:

> **"What drives the price of a car?"**

By analyzing historical vehicle data, we aim to identify the key attributes that increase or decrease a vehicle's market value.

---

## Dataset

The dataset contains information about used vehicles, including:

- Price
- Manufacturer
- Model
- Year
- Odometer Reading
- Fuel Type
- Transmission
- Vehicle Condition
- Vehicle Type
- Title Status
- Paint Color
- Region

---

## Methodology

The project follows the **CRISP-DM** framework.

### 1. Business Understanding

- Define business objectives.
- Identify factors that may influence vehicle prices.

### 2. Data Understanding

- Explore dataset structure.
- Assess missing values and data quality.
- Analyze variable distributions.

### 3. Data Preparation

- Remove duplicate records.
- Handle missing values.
- Address unrealistic values (for example, price = 0).
- Create an analysis-ready dataset.

### 4. Exploratory Data Analysis

- Examine relationships between vehicle attributes and price.
- Identify trends, outliers, and patterns.

### 5. Modeling

- Build predictive models to estimate vehicle prices.
- Evaluate feature importance.

### 6. Evaluation

- Interpret results from a business perspective.
- Recommend actions for the dealership.

---

## Key Findings

The analysis showed that vehicle price is primarily influenced by:

1. **Vehicle Age**
   - Newer vehicles generally command higher prices.

2. **Odometer Reading**
   - Vehicles with lower mileage tend to have higher market value.

3. **Manufacturer and Model**
   - Certain brands retain value better than others.

4. **Vehicle Condition**
   - Better-maintained vehicles achieve higher selling prices.

5. **Title Status**
   - Clean title vehicles are priced significantly higher than salvage or rebuilt title vehicles.

6. **Vehicle Type**
   - SUVs, trucks, and specialty vehicles often command higher prices compared to compact cars.

---

## Business Recommendations

- Prioritize acquisition of newer vehicles with lower mileage.
- Focus inventory on manufacturers with strong resale value.
- Improve vehicle condition before listing whenever economically feasible.
- Carefully evaluate vehicles with salvage or rebuilt titles before purchase.
- Use identified price drivers to support pricing decisions and inventory planning.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Repository Structure

```text
├── data/
│   └── vehicles.csv
├── notebooks/
│   └── car_price_analysis.ipynb
├── images/
├── README.md
└── requirements.txt
```

---

## Notebook

./notebooks/car_price_analysis.ipynb

---

## Author

**Chitra Pal**