# DoorDash_Demo
Analyze the DoorDash delivery data, to predict actual delivery duration.

## Introduction
This project aims to analyze the DoorDash delivery data, and build a predictive model to determine the acutal delivery duration based on various features.
The dataset contains information about each delivery's store category, subtotal, number of busy dashers, total dashers available, and more.

## Usage
1. The dataset can be found in the same repositoray as the Jupyter Notebook file.
2. Follow the step-by-step analysis in the notebook to explore the data, preprocess it, and build the predictive model.

## Data
The DoorDash dataset includes the following columns:
- market_id	created_at
- actual_delivery_time
- store_id
- store_primary_category
- order_protocol
- total_items	subtotal
- num_distinct_items
- min_item_price
- max_item_price
- total_onshift_dashers
- total_busy_dashers
- total_outstanding_orders
- estimated_order_place_duration
- estimated_store_to_consumer_driving_duration

## Data Preperation
1. Cleansed data by removing nan values.
2. Performed preliminary feature engineering and created the target variable.
3. Created dummy variables based on nominal features.
4. Examined collinearity and multicollinearity issues and filtered out highly correlated features.
5. Ranked features based on their Gini importances and created multiple feature sets for further exploration.

## Model Exploration
1. Created dictionaries to store different models, feature sets, and scaler that will be explored.
2. Iterate through different combinations of elements discussed above, and choose the best-performing model.
3. Narrowed down selections based on previous results, and attempted to optimize the result through further engineering of the features.
