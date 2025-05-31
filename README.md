Summer Analytics 2025 - Week 1 Assignment: Car Data Analysis
Project Overview
This repository contains the solution for the Week 1 Data Analysis Assignment of Summer Analytics 2025. The primary objective of this assignment is to perform various data analysis tasks on the Cars.csv dataset to derive insights into car characteristics and performance.

Dataset
The analysis is based on the Cars.csv dataset, which contains information about various car models, including their MPG, cylinders, displacement, horsepower, weight, acceleration, model year, origin, and name.

Technologies Used
Python: The core programming language used for the analysis.
Pandas: For data loading, manipulation, and analysis.
NumPy: For numerical operations (underlying Pandas).
Matplotlib: For creating static, animated, and interactive visualizations in Python.
Seaborn: A data visualization library based on Matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.
Jupyter Notebook: The environment used for developing and presenting the analysis.
Assignment Tasks & Key Findings
This assignment covered several key data analysis tasks:

Data Loading and Inspection:

Loading the Cars.csv dataset.
Displaying DataFrame shape and column names.
Setting 'name' and a new 'horsepower_per_weight' metric as DataFrame indices.
Identifying unique mpg values.
Car Model Consistency Analysis:

Identified "consistent" car models (produced over multiple years with std(mpg) < 1.0).
Report: [Include the table of consistent cars here or state the main findings, e.g., "Identified X consistent car models, with 'ford galaxie 500' and 'plymouth fury iii' having the most appearances." ]
Specific Data Queries:

Car with Highest Horsepower: Found the car(s) with the highest horsepower. [State the answer, e.g., "The car with the highest horsepower is: pontiac grand prix"]
Cars with MPG ≥ 35: Counted the number of cars achieving 35 MPG or more. [State the answer, e.g., "Number of cars with mpg ≥ 35: 36"]
Most Common Origin (High HP, Low Weight): Determined the most common origin for cars with horsepower > 100 and weight < 3000. [State the answer, e.g., "Most common origin for specific performance cars: usa"]
Mean Acceleration from Japan: Calculated the average acceleration for Japanese cars. [State the answer, e.g., "Mean acceleration of cars from Japan: 16.17"]
Year with Highest Average MPG: Identified the model year with the best average fuel efficiency. [State the answer, e.g., "Year with highest average mpg: 1980"]
Best Horsepower-to-Weight Ratio (Above-Median MPG): Found the car(s) with the optimal horsepower-to-weight ratio among fuel-efficient models. [State the answer, e.g., "Car with the best hp/weight ratio among above-median mpg cars: bmw 2002"]
Data Visualization:

Average MPG Evolution by Origin: A multi-line plot showing how average MPG changed over years for cars from USA, Europe, and Japan.
Horsepower vs. Weight Scatterplot: A scatterplot visualizing the relationship between horsepower and weight, colored by origin and sized by MPG.
