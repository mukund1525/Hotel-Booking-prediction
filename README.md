# Hotel Booking Prediction

## Overview

This project focuses on predicting hotel booking cancellations using Machine Learning techniques. The objective was to analyze customer booking behavior and build a predictive model that helps hotels identify bookings that are likely to be cancelled, enabling better operational planning and revenue management.

The project involved data cleaning, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation using Python-based data science libraries.

---

## Problem Statement

Hotel booking cancellations can lead to revenue loss, inefficient room allocation, and operational challenges. The goal of this project was to develop a classification model capable of predicting whether a booking would be cancelled based on customer and reservation details.

---

## Technologies & Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset Information

The dataset contains hotel booking records with features such as:

* Hotel type
* Lead time
* Arrival date
* Meal type
* Market segment
* Number of special requests
* Previous cancellations
* Room type
* Customer details

Target Variable:

* `is_canceled` (0 = Not Cancelled, 1 = Cancelled)

---

## Project Workflow

### 1. Data Cleaning

* Handled missing values
* Removed duplicate records
* Processed categorical variables
* Checked data consistency

### 2. Exploratory Data Analysis (EDA)

Performed analysis to identify:

* Cancellation trends
* Seasonal booking patterns
* Customer behavior insights
* Correlation between features

Visualizations were created using Matplotlib and Seaborn to better understand the dataset.

### 3. Feature Engineering

* Encoded categorical variables
* Selected important predictive features
* Prepared training and testing datasets

### 4. Model Building

Implemented Machine Learning models including:

* Logistic Regression
* Decision Tree
* Random Forest Classifier

### 5. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

The Random Forest model achieved approximately **85% accuracy** on the test dataset.

---

## Key Insights

* Higher lead times were associated with increased cancellation probability.
* Customers with previous cancellations were more likely to cancel again.
* Certain market segments showed higher cancellation rates.
* Booking behavior patterns varied across hotel types and seasons.

---

## Business Impact

This solution can help hotels:

* Improve occupancy planning
* Reduce revenue leakage due to cancellations
* Optimize customer engagement strategies
* Support data-driven operational decisions

---

## Future Improvements

* Hyperparameter tuning for better performance
* Deployment using Flask/Streamlit
* Real-time prediction dashboard integration
* Advanced ensemble models

---

## Repository Structure

```bash
Hotel-Booking-prediction/
│
├── data/
├── notebooks/
├── images/
├── hotel_booking_prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Conclusion

This project demonstrates the application of Machine Learning and data analytics techniques to solve a real-world business problem. It highlights skills in EDA, feature engineering, predictive modeling, and model evaluation using Python.
