# FIFA21 Data Cleaning Project (PySpark / Databricks)

## 📌 Overview

This project focuses on **data cleaning and preprocessing** of the FIFA21 dataset using **PySpark in Databricks**. The goal was to explore raw football player data, clean inconsistencies, handle missing values, and transform it into a structured format suitable for analysis or machine learning.

## 🎯 Objectives

* Clean and preprocess FIFA21 player dataset
* Handle missing values and inconsistent formats (e.g., height, weight, wage, release clause)
* Perform feature engineering (numeric conversions, derived columns)
* Ensure data quality for downstream analytics

## 🛠️ Technologies Used

* **Python**
* **PySpark** (DataFrame API, UDFs, Window functions)
* **Databricks** (for scalable processing)
* **GitHub** (version control & project showcase)

## 📂 Project Structure

```
├── fifa21_data_cleaning.ipynb   # Main Databricks notebook
├── README.md                    # Project documentation
└── data/                        # (Optional) dataset storage
```

## 🚀 Key Steps in Data Cleaning

1. **Loading dataset** into PySpark DataFrame
2. **Handling missing values** (`fillna`, `dropna`)
3. **Converting string columns to numeric** (e.g., wages: "€200K" → 200000)
4. **Standardizing height and weight** (feet/inches to cm, lbs to kg)
5. **Removing duplicates** using `dropDuplicates`
6. **Validating data quality**

## 📊 Results

* Cleaned FIFA21 dataset ready for analysis
* Structured features like player height, weight, wage, and release clause
* Demonstrated ability to use PySpark for large-scale data transformation

## 🔍 Learnings

* Practical experience in **ETL pipelines** using PySpark
* Hands-on with **Databricks notebooks and Git integration**
* Writing **user-defined functions (UDFs)** in PySpark for data transformation
* Improved skills in **data wrangling and feature engineering**

## 📌 How to Use

1. Clone this repository

   ```bash
   git clone https://github.com/your-username/fifa21-data-cleaning.git
   ```
2. Open the notebook in Databricks or Jupyter
3. Upload the dataset into your Databricks environment
4. Run the cells step by step to reproduce the cleaning process

## 👨‍💻 Author

**Srikanth Balabadra**

* Full Stack Java Developer | Aspiring Data Engineer
* [LinkedIn](https://www.linkedin.com/in/srikanthbalabadra/) | [GitHub](https://github.com/BalabadraSrikanth/)
