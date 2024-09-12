# Weather Dataset Analysis

Overview

This project analyzes a time-series weather dataset containing per-hour weather data for a specific location. The dataset includes critical weather variables such as Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Weather Conditions. The objective of this analysis is to uncover insights, trends, and correlations using various data exploration techniques, and logical operators such as AND and OR to filter and examine specific conditions.

# Dataset Description
The dataset contains the following key features:
1.  Temperature (°C): The recorded temperature at each hour.
2.  Dew Point Temperature (°C): The temperature at which dew forms.
3.  Relative Humidity (%): The percentage of humidity in the air.
4.  Wind Speed (km/h): The speed of the wind.
5.  Visibility (km): The visibility distance in kilometers.
6.  Pressure (kPa): The atmospheric pressure recorded.
7.  Weather Conditions: The overall weather conditions (e.g., Clear, Rain, Snow).

# Analysis Performed
Data Exploration & Cleaning
-  Checked for missing values and handled them appropriately.
-  Converted the data types where necessary.
- Performed descriptive analysis to calculate basic statistics such as mean, median, mode, and standard deviation for the numeric features.

# In Depth Analysis
Weather Conditions and Visibility Analysis:
   Investigated how different weather conditions impact visibility. We used conditional filtering with the AND operator, e.g., analyzing data where the weather condition is foggy AND the visibility is less than 1 km to observe how specific weather conditions, such as fog, affect visibility. This analysis helps in understanding the correlation between reduced visibility and adverse weather conditions like fog or rain.

# Conclusion
The weather dataset provides rich information about the interplay between various weather parameters. By applying filters using logical operators (AND, OR), I was to extract meaningful insights into how temperature, pressure, humidity, and wind conditions affect overall weather patterns.

# Technologies Used
1.  Python: For data analysis and manipulation using libraries like Pandas.
2.  Jupyter Notebook / Google Colab: For conducting and documenting the analysis.

# Future Work
-  Extend the analysis to predict weather conditions using machine learning models.
-  Explore how weather parameters change over different seasons.
-  Data Visualization to show trends and Distributions eg Histograms.
-  Use of more Python libraries such as Matplotlib and NumPy

