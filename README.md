# Predict-Food-Delivery-Time

The digital transformation of our world has significantly enhanced our interaction with technology, making our lives easier by saving time and effort. With the convenience of smartphones, almost everything—from groceries to cooked food, and from medicines to doctors—is accessible at our fingertips. This project leverages data reflecting our growing relationship with technology.

## Project Overview

In this project, we are provided with data from thousands of restaurants in India, detailing the time it takes to deliver food for online orders. Our goal as data scientists is to predict online order delivery times based on various factors.

## Dataset

- **Training Set Size:** 11,094 records
- **Test Set Size:** 2,774 records

### Features

- **Restaurant:** A unique ID representing the restaurant.
- **Location:** The location of the restaurant.
- **Cuisines:** The cuisines offered by the restaurant.
- **Average_Cost:** The average cost for one person/order.
- **Minimum_Order:** The minimum order amount.
- **Rating:** Customer rating for the restaurant.
- **Votes:** Total number of customer votes for the restaurant.
- **Reviews:** Number of customer reviews for the restaurant.
- **Delivery_Time:** Order delivery time of the restaurant (Target variable).

## Modeling and Prediction

We will build a simple classifier to predict delivery times using the provided data.

### Approach

1. **Data Preparation:**
   - Split the training data into a training set and a validation set.
   - Separate independent and dependent variables from the dataset.

2. **Modeling:**
   - Initialize a Random Forest classifier.
   - Train the classifier with the training data.
   - Evaluate the model's performance on the validation set.
   - Predict the delivery times for the test set.

### Results

- **Training Score:** 0.774
- **Testing Score:** 76.901

This basic approach uses a Random Forest classifier without parameter tuning as a starting point. Future improvements could involve more advanced techniques and parameter optimization to enhance prediction accuracy.
