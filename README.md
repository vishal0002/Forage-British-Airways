# British Airways - Heathrow Terminal 3

# Summary Task 1

The analysis provides insights into the distribution and characteristics of eligible passengers, supporting further business or operational decisions.
# Detailed Analysis Description

This notebook provides a comprehensive analysis of passenger eligibility data sourced from the `ba.xlsx` dataset. The steps and rationale are as follows:

1. **Data Loading**
   - Utilized the `pandas` library to import the Excel file into a DataFrame, enabling efficient data manipulation and analysis.

2. **Initial Exploration**
   - Displayed the first few rows to understand the structure and contents of the dataset.
   - Used summary statistics and `.info()` to check for missing values, data types, and overall data quality.

3. **Key Column Summaries**
   - Focused on columns representing eligibility tiers (e.g., Silver, Gold, Bronze).
   - Calculated total counts and proportions for each tier to understand their distribution.

4. **Grouping and Aggregation**
   - Grouped data by relevant categories such as region, time of day (morning, afternoon, evening), and haul type (short-haul, long-haul).
   - Aggregated eligible passenger counts within each group.
   - Computed percentages to compare eligibility rates across different segments.

5. **Visualization**
   - Created bar plots using libraries like `matplotlib` or `seaborn` to visualize the distribution of eligible passengers by group.
   - Visualizations helped identify trends and outliers in eligibility across regions, times, and haul types.

6. **Additional Insights**
   - Extracted and listed unique arrival countries for each group to provide further context on passenger demographics.
   - Highlighted any notable patterns or anomalies discovered during the analysis.

This structured approach ensures a thorough understanding of the dataset, enabling data-driven decisions and deeper business insights.

# Summary Task 2

This notebook focused on predictive modeling of customer bookings using a real-world dataset. The primary objective was to build a machine learning model capable of predicting whether a customer would complete a booking, based on various features available at the time of booking.

### Data Overview

The dataset contained the following key features:

- **num_passengers:** Number of passengers in the booking.
- **sales_channel:** Platform used for booking (e.g., online, offline).
- **trip_type:** Type of trip (Round Trip, One Way, Circle Trip).
- **purchase_lead:** Days between booking and travel date.
- **length_of_stay:** Duration of stay at the destination.
- **flight_hour:** Departure hour.
- **flight_day:** Day of the week for departure (converted from string to numeric).
- **route:** Origin and destination pair.
- **booking_origin:** Country where the booking was made.
- **wants_extra_baggage, wants_preferred_seat, wants_in_flight_meals:** Customer preferences for additional services.
- **flight_duration:** Total flight duration in hours.
- **booking_complete:** Target variable indicating if the booking was completed.

### Workflow Summary

1. **Exploratory Data Analysis:**  
    - Inspected the first few rows and data types.
    - Checked for missing values and performed necessary data type conversions (e.g., mapping days of the week to numbers).

2. **Feature Engineering:**  
    - Converted categorical variables to dummy/indicator variables for modeling.
    - Ensured all features were in a suitable format for machine learning algorithms.

3. **Model Training:**  
    - Split the data into training and test sets (80/20 split).
    - Trained a Random Forest Classifier to predict booking completion.
    - Evaluated the model using a classification report, providing precision, recall, F1-score, and support for each class.

4. **Feature Importance Analysis:**  
    - Used mutual information and Random Forest feature importances to identify the most influential features.
    - Visualized both individual dummy variable importances and aggregated importances by original column.
### Classification Report

### The classification report provides the following metrics for each class:

- **Precision:** Proportion of positive identifications that were actually correct.
- **Recall:** Proportion of actual positives that were identified correctly.
- **F1-score:** Harmonic mean of precision and recall.
- **Support:** Number of occurrences of each class in the test set.
  
### Key Insights

- The model achieved reasonable performance in predicting booking completion, as shown by the classification report.
- Feature importance analysis highlighted which variables most strongly influenced booking outcomes, providing actionable insights for business strategy and further analysis.

This workflow demonstrates a complete pipeline from data exploration and preprocessing to model training, evaluation, and interpretation, offering a robust approach to predictive analytics in customer booking scenarios.

### Completion Certificate: [Link](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/tMjbs76F526fF5v3G/NjynCWzGSaWXQCxSX_tMjbs76F526fF5v3G_W2Wx6ttJCfjcfB4cd_1748993537278_completion_certificate.pdf)

### Forage BCGx Gen AI Program [Link](https://www.theforage.com/simulations/british-airways/data-science-yqoz)
