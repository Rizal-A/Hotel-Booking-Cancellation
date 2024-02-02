# Hotel Booking Cancellation
<img src = 'https://github.com/Rizal-A/Hotel-Booking-Cancellation/assets/117552819/92e736f7-d80d-4c22-a5d1-80fb1ca5ffa4' width = 1000>

## Project Overview
Data Science Project from Dibimbing.Id Bootcamp. This project is about predicting hotel booking cancellation using supervised machine learning (Classification)

### Problem Statement
The hotel experienced a loss of revenue due to unexpected hotel cancellations made by customers. The company's goal is to handle this uncertainty by predicting which customers are likely to cancel their hotel bookings. The ultimate goal of doing this is to help the company identify customers with the highest probability of cancellation, so that the company can immediately anticipate this by providing proactive strategies such as providing incentives, special reminders and implementing other strategies to mitigate the occurrence of order cancellations, and ultimately increase company revenue

### Objective
The main objective is to create a model that can accurately predict the possibility of a hotel booking being canceled or not. And with this prediction can provide valuable insights for companies that can help them allocate resources effectively and provide business recommendations to reduce the number of canceled bookings and increasing company revenue.

## Things that are done on this dataset are

- **Data Understanding & Data Preprocessing**
  - Dataset Contains 83293 rows and 33 columns
  - Data Cleaning
    - Missing Value & Duplicate Handling
    - Convert Incorrect Data Type
- **Exploratory Data Analysis**
  - Outlier Handling
  - Exploratory Data Categorical and Numerical
- **Modelling**

  Here are the steps and processes in Machine Learning modeling

  <img src = 'https://github.com/Rizal-A/Hotel-Booking-Cancellation/assets/117552819/0bd92d9d-368e-4de4-a45d-9804b387a0ee' width = 800>
  
  In this project, 6 classification models were used and performance evaluation was carried out to determine the best model, such as:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - LGBM
  - XGBoost
 


- **Evaluation**
  **Here are the results of Sentiment Analysis**

  **Best Model for Prediction**

  **Random Forest Classifier (F1 Score : 0.7979, Recall Score : 0.8218)**
  - Best Parameter Random Forest :  'max_depth': 50, 'min_samples_split': 2, 'n_estimators': 300'
    ![image](https://github.com/Rizal-A/Hotel-Booking-Cancellation/assets/117552819/94246fd9-3a89-4fa0-922f-db3485110a3f)
  - **False Negative Rate (FNR): 0.1781**
    
- **Business Recommendation**
  - Focus on managing reservations during peak season periods, by focusing on prospective customers who are likely to cancel
  - Implement a deposit system ( upfront payment ) for customers who make early bookings so as to minimize the cancelation.
  - Implement a stricter cancellation policy, where the cancellation policy determined can be differentiated between regular season and high season, by applying Down Payment for reservations and giving partial refunds when canceling in regular season to minimize losses. However, during the high season, cancellation of bookings is free of charge due to high demand, and if a cancellation occurs, it can be quickly replaced by another customer.
  - Most customers reserve lower room categories. Therefore, hotels can reduce the price gap between the lower room category and the next room category. With a small price difference, customers can be compelled to pay a little more to book in a higher category.
  - Hotels create a membership system by collecting points that can be redeemed for certain benefits, thus increasing customers to repeat bookings.
  - Provide remainder to the customer if the time of arrival or stay is close so that the customer is aware of his order
  - The hotel provides surveys to customers who stay overnight so that with this feedback the hotel can improve its services so that it can increase the number of customers making repeat bookings.










