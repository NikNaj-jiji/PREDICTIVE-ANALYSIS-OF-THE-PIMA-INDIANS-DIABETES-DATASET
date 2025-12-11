

# **Pima Indians Diabetes Prediction — Data Science Project**

This repository contains a data science project focused on analysing and modelling the **Pima Indians Diabetes Dataset**.
The aim of the project is to **develop a predictive model capable of identifying individuals within the Pima Indian population who are likely to develop diabetes**, 
based on a range of health-related features such as:

* Blood glucose level
* BMI (Body Mass Index)
* Number of pregnancies
* Blood pressure
* Skin thickness
* Insulin levels
* Diabetes pedigree function
* Age

The analysis follows the **CRISP-DM** methodology and uses **IBM SPSS Modeler** for data exploration, cleaning, preprocessing, and modelling.

The full report is available in this repository as a PDF:
***NikooNajafian-Khordad-PimaIndianProject.pdf*** 

---

## **Project Overview**

The project includes:

### **1. Business Understanding**

Type 2 diabetes is a chronic metabolic condition associated with insulin resistance. Early prediction is crucial for prevention and targeted interventions.
This project explores how demographic and health measurements relate to diabetes likelihood in the Pima Indian population.

### **2. Data Understanding**

The dataset contains **768 observations**, each representing a female patient aged 21 or older from the Pima Tribe.
Eight physiological predictors and one binary outcome variable (`Outcome`) are analysed.

### **3. Data Preparation**

The following preprocessing steps were performed (detailed inside the PDF):

* Handling incorrect zero-entries
* Detecting and managing outliers and extreme values
* Imputing missing values through median/mean or CART modelling
* Normalising data using min–max scaling (0–100)

### **4. Modelling**

A **K-Means Clustering** approach was applied to uncover natural groupings in the data.
After testing cluster configurations from 1 to 5 groups, **2 clusters** achieved the highest silhouette score.
Key findings include:

* **Age** and **Number of Pregnancies** were the most influential clustering features.
* The two clusters generally correspond to **higher-risk (diabetic)** and **lower-risk (non-diabetic)** groups.

### **5. Results & Insights**

The final clustering results reveal:

* Clear separation between risk groups
* Strong predictive potential for early detection
* Demonstration of how unsupervised learning can support healthcare decision-making

See the report PDF for full tables, figures, and explanations.

---

## **Repository Structure**

```
├── README.md     # Project documentation
└── NikooNajafian-Khordad-PimaIndianProject.pdf   # Full project report with visuals
```



---

**Author**

**Nikoo Najafian**
Course Project — *Foundations and Concepts of Data Science*
University of Tehran · October 2025

---
