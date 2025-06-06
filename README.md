# British Airways Lounge Access Lookup Table - Heathrow Terminal 3

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
