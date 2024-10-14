# Project Overview

This project focuses on building **Machine Learning Pipelines** for regression analysis, leveraging **SparkSQL** and **PySpark** for scalable data processing and analysis. The main objective is to design an end-to-end system capable of efficiently handling large datasets, performing necessary transformations, and building regression models for predictive insights.

Key technologies utilized in this project:
- **PySpark**: Used for scalable data processing and machine learning tasks.
- **SparkSQL**: Enables querying large datasets using SQL-like syntax.
- **Machine Learning Pipelines**: Facilitates seamless workflow from data preparation to model training and evaluation.

The primary goal of this project is to streamline the process of feature extraction and regression model training, ensuring scalability and efficiency when dealing with big data.

---

# Stages

### 1. Descriptive Data Analysis
The first phase of the project involves conducting detailed descriptive data analysis, which includes:
- **Data Preprocessing**: Selecting necessary columns and handling missing or inconsistent data.
- **Data Queries**: Writing queries in **SparkSQL** to explore and summarize the dataset.
- **Feature Extraction**: Identifying and extracting key features that will serve as inputs to the machine learning model.

This phase is documented in the `descriptive_analysis.ipynb` file, where all relevant preprocessing steps and SQL queries are implemented.

### 2. Regression Analysis
The second phase of the project focuses on building the **ML Pipelines** for regression. Using the features extracted from the previous phase, we construct a pipeline that handles:
- **Feature Transformation**: Ensuring all features are in a suitable format for model input.
- **Model Training**: Applying regression algorithms to train models using the transformed features.
- **Model Evaluation**: Assessing the performance of the regression models.
  
This phase is implemented in the `regression_analysis.ipynb` file, where the machine learning pipeline is constructed and evaluated.
Additionally, you can refer to `Spark_Cheat_Sheet.docx` to learn more about the commands.

---
