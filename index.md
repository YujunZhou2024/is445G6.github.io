---
layout: default
title: Home
---

#Final Project Visualizations
## Dataset
[Click here to see the dataset](https://github.com/YujunZhou2024/IS445.github.io/blob/main/python_notebooks/annual_aqi_by_county_2018-2023.csv)

## Visualization
[Click here to see the visualizations](/IS445_Final.html)

## Outline

**1. Data Preparation**

1.1. Import necessary libraries.

1.2. Read the dataset and perform any initial data filtering or cleaning.

**2. Data Visualization**

Six visualizations were built.

2.1. max_aqi (2): Calculate the average maximum AQI per state and visualize it using a bar chart and a heatmap. 

2.2. good_days (1): Calculate and visualize the average number of good air quality days per state with a bar chart.

2.3. unhealthy_days (1): Calculate and visualize the average number of bad air quality days per state with a bar chart and a year selector.

2.4. air_quality_map (1): Create an interactive plot that updates based on the year selected from a dropdown, showing different kinds of day counts.

2.5. aqi_trend (1): Plot the trend of AQI over the years for a selected state using a line plot with a trend line.

**3. Building Dashboard and refresh button**

3.1. Organize the individual visualizations into a tabbed layout using ipywidgets.tab, with each tab corresponding to a different visualization of the air quality data as shown above.
3.2. Build a refresh button to update all visualizations with new data if needed.

## Python notebook
[Click here to see the notebook](/IS445_Final.ipynb)

---
