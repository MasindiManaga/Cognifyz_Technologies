# Restaurant Data Analysis and Prediction

## Description

This project involves analyzing restaurant data to uncover insights, perform feature engineering, and build predictive models. The goal is to predict restaurant aggregate ratings and analyze customer preferences based on various features such as cuisine type, price range, and service offerings.

## Features

- **Price Range Analysis**:
  - Identified the most common price range.
  - Calculated average ratings for each price range.
  - Determined which price range color represents the highest average rating.

- **Customer Preference Analysis**:
  - Analyzed the relationship between cuisine types and ratings.
  - Identified the most popular cuisines based on vote counts.
  - Determined cuisines with higher ratings using group-wise analysis.

- **Feature Engineering**:
  - Extracted features like the length of restaurant names and addresses.
  - Created new features such as:
    - `Has Table Booking`: Whether the restaurant allows table booking.
    - `Has Online Delivery`: Whether online delivery is available.
  
- **Model Building**:
  - Built and evaluated predictive models:
    - **Linear Regression**
    - **Decision Tree Regressor**
    - **Random Forest Regressor**
  - Used metrics like Mean Squared Error (MSE) and R² to compare model performance.
  - Ranked models based on performance:
    1. Random Forest Regressor
    2. Decision Tree Regressor
    3. Linear Regression
