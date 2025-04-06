📊 Exploratory Data Analysis on Superstore Dataset

This project performs an Exploratory Data Analysis (EDA) on the popular Superstore dataset using Python. The analysis uncovers insights about customer segments, regional performance, sales distributions, and product category performance using both Matplotlib/Seaborn and interactive Plotly visualizations.
📁 Dataset Overview

The Superstore dataset includes transactional data for a fictional retail chain. It contains:

    Orders and shipping details

    Customer segmentation

    Product categories and sub-categories

    Regional and state-based sales

    Sales and profit data

🧹 Data Preprocessing

    Handling Missing Values:

        Postal Code null values were replaced with 0 and cast to integers.

    Checking for Duplicates:

        Verified with df.duplicated().sum() and printed the result.

🔍 Analysis and Visualizations
1. 🎯 Customer Segmentation

    Counted customers per Segment.

    Visualized the distribution using a pie chart.

2. 💰 Sales by Segment

    Aggregated total Sales per Segment.

    Plotted using bar chart and pie chart to show contribution per segment.

3. 📦 Shipping Mode Analysis

    Counted orders by Ship Mode.

    Visualized using a pie chart.

4. 📋 Order Frequency per Customer

    Grouped by Customer ID, Customer Name, and Segment.

    Calculated the number of orders each customer placed.

5. 🧭 Category vs Sub-Category Sales (Nested Pie Chart)

    Grouped Sales by Category and Sub-Category.

    Created a Sunburst chart using Plotly to show hierarchical sales contribution.


   
📌 Conclusion

This EDA highlights:

    The distribution and behavior of customer segments.

    Performance insights by region and product.
5
    Visual storytelling through interactive Plotly visualizations.

Use this analysis to guide further tasks such as predictive modeling, customer targeting, or inventory optimization.
