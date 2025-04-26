# Crime Severity Prediction Using Machine Learning

## Project Overview
This project aims to **predict crime severity** using **NYPD Complaint Data (Year-To-Date)**. By applying machine learning models, the project identifies key crime patterns to assist law enforcement in **crime prevention and resource allocation**.

---

## Dataset
- **Source:**  [NYPD Complaint Data] (https://drive.google.com/file/d/1MDXVvgnwtTSqnRr21zYeGIyV_CppbxXo/view?usp=drive_link)
- **Description:**  
  - Crime reports from New York City.  
  - Includes details on crime type, location, time, and demographics.  

---

## Models Used
1. **Random Forest Classifier (RFC)**  
   - Robust ensemble model with feature importance analysis.  
2. **Logistic Regression (LR)**  
   - Simple and interpretable baseline model.  
3. **XGBoost Classifier (XGB)**  
   - Highly efficient boosting model with superior performance.

---

## Feature Engineering
- **Crime Duration:** Difference (in hours) between crime start and end times.  
- **Crime Hour:** Extracted from timestamps to detect time-based patterns.  
- **Crime Day of the Week:** Analyzed weekly crime patterns.

---

## Results
| Model               | Accuracy  | Precision | Recall    | F1 Score  |
|---------------------|----------|-----------|-----------|-----------|
| Random Forest       | 99.82%    | 99.82%     | 99.82%     | 99.82%     |
| Logistic Regression | 84.44%    | 76.76%     | 84.44%     | 77.65%     |
| **XGBoost**         | **99.85%**| **99.85%** | **99.85%** | **99.85%** |

**XGBoost achieved the best performance** with a balanced F1 score of **90.4%**, making it the recommended model for deployment.

---

## 📦 Installation and Usage Guide

## Prerequisites
Before you begin, make sure you have the following installed on your system:
- [Git](https://git-scm.com/downloads)
- [Python 3.8+](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)

---

## Installation Steps

1. **Clone the Repository**

   Open your terminal or command prompt and run:

   > git clone https://github.com/Parlynx1/AIM5005-Crime-Analysis-Prediction-NYC.git

2. **Navigate into the Project Directory**

   > cd AIM5005-Crime-Analysis-Prediction-NYC

3. **Open  IDE editor**

   > code .