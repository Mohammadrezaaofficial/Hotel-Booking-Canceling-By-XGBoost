# Hotel-Booking-Canceling-By-XGBoost

## Summary
The document outlines a data science project using XGBoost for a classification task. The goal is to predict whether a customer will cancel their hotel booking. The project uses the hotel_bookings.csv dataset, which contains 119,390 entries and 32 columns. The target variable for this prediction is "is_canceled".


## 1. Data Loading and Initial Inspection: 
The project begins by loading the hotel_bookings.csv file into a pandas DataFrame called df. It then uses df.info() to check the data types and see which columns have missing values, such as children, country, agent, and company. The document also provides a statistical summary of the numerical columns using df.describe().

## 2. Target Variable Analysis:
The file shows the distribution of the target variable, is_canceled. A bar chart visually represents the number of bookings that were canceled (1) versus those that were not canceled (0). The analysis reveals that approximately 37% of the bookings in the dataset were canceled.

## 3. Feature Correlation Analysis: 
The document calculates a correlation matrix to identify which numerical features have a relationship with the is_canceled variable. The matrix shows that lead_time, previous_cancellations, and days_in_waiting_list have positive correlations with is_canceled. Conversely, is_repeated_guest, booking_changes, agent, required_car_parking_spaces, and total_of_special_requests show negative correlations with is_canceled. This step helps to understand which factors are most influential in predicting a cancellation.

## Conclusion
Based on the provided document, the process stops at the exploratory data analysis phase. The file shows the data loading, initial data inspection, and correlation analysis. However, it does not contain the subsequent steps of the machine learning pipeline, such as the actual training of the XGBoost model, the prediction on test data, or the final evaluation metrics like a classification report or a confusion matrix. Therefore, a conclusion on the model's performance cannot be drawn from the available content.
