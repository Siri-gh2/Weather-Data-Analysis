# 🌦️ Weather Data Analysis using Python (Google Colab)

## 📌 Project Overview

This project focuses on analyzing a weather dataset using **Python (Pandas)** in Google Colab.
The goal is to explore, clean, and extract meaningful insights from the dataset through various data analysis operations.

---

## 🛠️ Tools & Technologies Used

* Python 🐍
* Pandas 📊
* Google Colab 💻

---

## 📂 Dataset

* The dataset used: `WeatherData.csv`
* Contains weather-related information such as:

  * Temperature
  * Humidity
  * Wind Speed
  * Visibility
  * Pressure
  * Weather Conditions

---

## 🚀 Steps Performed

### 1. Data Loading

* Imported dataset using pandas
* Displayed initial rows and structure

### 2. Data Exploration

* Checked:

  * Shape of dataset
  * Column names
  * Data types
  * Index
* Viewed head and tail of dataset

### 3. Data Cleaning

* Checked for:

  * Null values
  * Non-null values
* Renamed column:

  * `Weather` → `Weather Condition`

---

## 🔍 Analysis & Insights

### ✔️ Unique Values

* Extracted unique weather conditions
* Counted unique values per column

### ✔️ Filtering Data

* Records where:

  * Weather = Clear
  * Wind Speed = 4 km/h
  * Weather contains Snow
  * Weather = Fog

### ✔️ Statistical Analysis

* Mean of Visibility
* Standard deviation of Pressure
* Variance of Humidity

### ✔️ GroupBy Operations

* Mean values grouped by Weather Condition
* Minimum values grouped by Weather Condition
* Maximum values grouped by Weather Condition

### ✔️ Conditional Queries

* Clear weather with Visibility > 40
* Combined conditions using AND & OR

---

## 📊 Key Features

* Data filtering using conditions
* GroupBy aggregation
* Statistical analysis
* Handling missing values
* Column renaming

---

## 📁 Project File

* Main file: WeatherDataset.ipynb
* Converted script: 

---

## ▶️ How to Run This Project

1. Open Google Colab
2. Upload the dataset (`WeatherData.csv`)
3. Upload the notebook or script
4. Run all cells step-by-step

---

## 💡 Learning Outcomes

* Hands-on experience with pandas
* Data cleaning and preprocessing
* Performing real-world data analysis queries
* Writing efficient filtering conditions

---

## 📌 Future Improvements

* Add data visualizations (Matplotlib / Seaborn)
* Build a dashboard
* Perform predictive analysis

---

## 🙌 Author

**Korupolu Siri**

---
