Household Energy Consumption Analysis

The notebooks in this repository offer a comprehensive guide to analyze energy consumption data using Python's pandas, numpy, and matplotlib libraries. It covers the following key aspects:

    Data Import and Cleaning: Importing raw energy consumption data, cleaning, and formatting it to ensure consistency for analysis.
    Visualizing Daily Consumption: Generating histograms and box plots to understand the variation in daily energy consumption.
    Identifying Seasonal Patterns: Analyzing energy consumption trends over time, identifying seasonal patterns, and visualizing them using line plots.
    Defining Typical Weeks: Defining typical weeks for different seasons (winter, summer, and transitional periods) and visualizing typical daily usage patterns.
    Detecting Exceptional Usage: Implementing one-class support vector machines (SVMs) to identify exceptional usage days compared to typical patterns.
    Classifying Weekdays vs. Weekends/Vacation Days: Using time series classification to distinguish between weekdays and weekends or vacation days based on energy consumption patterns.

Usage

To utilize the functionalities provided in the notebook, follow these steps:

    Data Preparation: Ensure your energy consumption data is in a compatible format (e.g., CSV) and adjust the notebook to import and clean your data accordingly.
    Data Analysis: Execute the notebook cells sequentially to import your data, visualize daily consumption, identify seasonal patterns, define typical weeks, and detect exceptional usage days.
    Classification: Follow the steps in the notebook to classify weekdays vs. weekends or vacation days using a k-nearest neighbors (k-NN) classifier on time series data.
    Interpretation: Analyze the generated visualizations to understand your household's energy consumption patterns, identify trends, and pinpoint exceptional usage days.
    Optimization: Utilize the insights gained from the analysis to optimize energy consumption, make informed decisions about energy usage habits, and potentially reduce costs.

Requirements

Ensure you have the following libraries installed to execute the notebook:

    pandas
    numpy
    matplotlib
    scikit-learn
    seaborn
    sktime