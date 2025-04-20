# Screen Time Analysis Project

## Overview
This project analyzes personal screen time data across different applications to identify usage patterns, notification trends, and app engagement metrics. By visualizing and examining these patterns, the project aims to provide insights into digital habits and potential areas for improved digital wellness.

## Dataset Description
The dataset contains daily app usage information with the following features:
- **Date**: The date when the app was used
- **App**: Name of the mobile application
- **Usage (minutes)**: Duration of app usage in minutes
- **Notifications**: Number of notifications received from the app 
- **Times Opened**: Number of times the app was opened

## Project Structure
The analysis explores various aspects of app usage:

1. **Data Preparation**
   - Loading the screen time dataset
   - Converting date columns to datetime format
   - Adding derived features like day of the week

2. **Exploratory Data Analysis**
   - Visualizing relationships between usage metrics
   - Correlation analysis of numeric features
   - Time series analysis of app usage

3. **App Usage Patterns**
   - Comparison of average usage across different apps
   - Analysis of notification patterns
   - Examination of app opening frequency

4. **Temporal Analysis**
   - Day-of-week usage patterns
   - App-specific trends by day of week
   - Peak usage identification

5. **Engagement Metrics**
   - Notification effectiveness (opening rate)
   - User engagement patterns
   - Correlation between notifications and app usage

## Key Findings
Based on the visualizations and analysis:

- There appears to be a correlation between notifications and the number of times apps are opened
- Usage patterns vary significantly by day of the week, with certain days showing higher engagement
- Instagram shows the highest average usage among the analyzed apps
- Specific apps demonstrate distinct notification-to-usage conversion rates
- Weekend vs. weekday usage patterns reveal interesting differences in digital habits

## Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **NumPy**: Numerical computations

## Visualizations
The project includes various visualization types:
- Pairplots with KDE for distribution analysis
- Correlation heatmaps
- Line charts for time-series analysis
- Bar charts for comparative metrics
- Day-of-week analysis charts

## Future Work
- Incorporate machine learning to predict screen time based on historical patterns
- Develop a recommendation system for digital wellbeing

## Usage
To run this project:
1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
