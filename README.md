# Hotel Booking Cancellation Prediction

## Project Overview
This project analyzes hotel booking data to identify customer behavior patterns and predict booking cancellations using machine learning models.

The project includes:
- Exploratory Data Analysis (EDA)
- Data Cleaning & Feature Engineering
- Business Insights Generation
- Data Visualization
- Machine Learning Model Comparison

The primary goal is to help hotels reduce cancellation-related revenue loss and improve booking management strategies.

---

## Dataset Information

The dataset contains hotel booking records for:
- Resort Hotels
- City Hotels

### Dataset Size
- Rows: 119,390
- Columns: 32

### Features Include
- Lead Time
- Booking Status
- ADR (Average Daily Rate)
- Customer Type
- Meal Type
- Market Segment
- Room Type
- Booking Changes
- Special Requests
- Cancellation Status

---

## Technologies Used

```python
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn
Folium
```

---

## Project Workflow

### 1. Data Cleaning
- Handled missing values using `fillna()`
- Removed invalid records
- Converted date columns into datetime format
- Removed records with zero guests

### 2. Exploratory Data Analysis
Performed analysis on:
- Country-wise guest distribution
- Monthly hotel demand
- Room pricing trends
- Cancellation trends
- Resort vs City hotel comparison

### 3. Feature Engineering
- Mean Encoding for categorical variables
- Date feature extraction
- Outlier handling using logarithmic transformation
- Feature selection using Lasso Regression

### 4. Machine Learning Models
Implemented multiple models:
- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

---

## Important Insights

### Booking Cancellation Trends
- Higher lead time increases cancellation probability.
- Customers with non-refundable deposits are highly likely to cancel.
- Customers with more special requests are less likely to cancel.

### Seasonal Trends
- Resort hotels experience peak demand during July and August.
- City hotels receive consistently higher bookings throughout the year.

### Pricing Insights
- Resort hotel ADR increases significantly during peak seasons.
- City hotel pricing remains relatively stable compared to resort hotels.

---

## Model Performance

| Model | Accuracy |
|------|------|
| Logistic Regression | 70.58% |
| Naive Bayes | 59.33% |
| Decision Tree | 95.03% |
| Random Forest | 95.72% |
| KNN | 95.36% |

### Best Performing Model
```python
Random Forest Accuracy: 95.72%
```

---

## Data Visualizations

The project includes:
- Choropleth maps
- Line charts
- Correlation analysis
- Box plots
- Distribution plots

---

## Business Impact

This project helps hotels:
- Predict potential booking cancellations
- Optimize room pricing strategies
- Improve occupancy planning
- Reduce revenue leakage
- Understand customer booking behavior

---

## Folder Structure

```bash
Hotel-Booking-Prediction/
│
├── hotel_booking_prediction.ipynb
├── hotel_bookings.csv
├── README.md
└── images/
```

---

## Future Improvements

- Hyperparameter tuning
- Streamlit dashboard deployment
- Real-time prediction API
- Ensemble learning methods
- Power BI dashboard integration

---

## Author

### Mukund Mane
- Python Developer
- Data Analytics Enthusiast
- Machine Learning & Business Intelligence
