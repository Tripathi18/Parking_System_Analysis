# Parking System Analysis

This repository contains Python code for analyzing parking data using various data analysis and visualization techniques. The code uses libraries such as NumPy, pandas, seaborn, and matplotlib for data manipulation and visualization. The primary objectives of the code are to clean and preprocess the parking data, perform exploratory data analysis, and apply K-means clustering to identify patterns in the parking occupancy rates.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [K-means Clustering](#k-means-clustering)
- [License](#license)

## Introduction

The data used in this analysis is stored in a CSV file named 'parking_birmingham.csv'. The code reads the data, cleans it by removing inconsistent or missing records, and preprocesses it to add new features like 'OccupancyRate', 'Date', 'Time', and 'DayOfWeek'. The analysis includes visualizations to understand parking occupancy patterns over time and days.

## Installation

To run the code, you need to have Python and the following libraries installed:

- NumPy
- pandas
- seaborn
- matplotlib
- scipy
- scikit-learn

You can install these libraries using pip by running the following command:

```bash
pip install numpy pandas seaborn matplotlib scipy scikit-learn
```

## Usage

1. Clone this repository to your local machine.
2. Make sure you have the required libraries installed (as mentioned in the installation section).
3. Place the 'parking_birmingham.csv' file in the same directory as the code.
4. Run the code in your Python environment (e.g., Jupyter Notebook, Python script).

## Data Cleaning

The initial part of the code involves cleaning the data by removing inconsistent records, dropping missing values, and filtering out negative occupancy and capacity values. Any occupancy data that exceeds the parking capacity is also removed to ensure data accuracy.

## Exploratory Data Analysis

The exploratory data analysis (EDA) section includes various visualizations to analyze the parking occupancy rate over time for different parking lots. The code generates line plots and scatter plots to visualize occupancy rates on different dates and times, as well as bar plots and box plots to understand the distribution of occupancy rates and patterns on different weekdays.

## K-means Clustering

The last part of the code focuses on applying K-means clustering to the training data. The clustering helps identify patterns and group parking lots based on similar occupancy and capacity characteristics. The code visualizes the clusters in a scatter plot, highlighting the clusters using different colors.

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use the code for personal or commercial purposes.

Feel free to modify and extend the code to suit your specific requirements.

If you have any questions or suggestions, please feel free to reach out or create an issue in this repository. Happy analyzing!
