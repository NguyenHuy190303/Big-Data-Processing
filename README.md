# Data Processing for Big Data

## Overview

This repository contains assignments for the FIT5202 course, focusing on data processing for big data using PySpark. The assignments cover various aspects of data processing, including text data analysis, CSV data analysis, and weather forecasting.

## Table of Contents

- [Part A: Analysing Text Data](#part-a-analysing-text-data)
- [Part B: Analysing CSV Data](#part-b-analysing-csv-data)
- [Part C: Weather Forecasting](#part-c-weather-forecasting)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Part A: Analysing Text Data

In this part, we analyze two books on software development methodologies. The goal is to understand the distribution of words, identify the most common words, and calculate their average frequency.

### Steps:
1. **Initialize Spark**: Create a SparkContext and SparkSession.
2. **Create RDDs**: Load the text data into Resilient Distributed Datasets (RDDs).
3. **Clean Text Data**: Remove non-alphabet characters, convert to lowercase, and trim spaces.
4. **Count Words**: Split text into words, create word pairs, and count their frequency.
5. **Remove Stop Words**: Use NLTK to filter out common stop words.
6. **Calculate Average Occurrence**: Find the average frequency of words.
7. **Exploratory Data Analysis**: Visualize the distribution of words using matplotlib.

## Part B: Analysing CSV Data

In this part, we analyze crime data from South Australia. The dataset includes reported incidents of crime from 2010 onwards.

### Steps:
1. **Initialize Spark**: Create a SparkContext and SparkSession.
2. **Create DataFrame**: Load the CSV data into a DataFrame.
3. **Write to Database**: Insert the data into MongoDB.
4. **Read from Database**: Load data from MongoDB into a DataFrame.
5. **Calculate Statistics**: Compute statistics for numeric and string columns.
6. **Change Data Type**: Convert the "Reported Date" column to date format.
7. **Preliminary Data Analysis**: Answer analytical queries about the data.
8. **Exploratory Data Analysis**: Visualize the number of crimes per year using matplotlib.

## Part C: Weather Forecasting

In this part, we predict whether it will rain tomorrow in Australia using machine learning algorithms.

### Steps:
1. **Initialize Spark**: Create a SparkContext and SparkSession.
2. **Load Dataset**: Load the weather data into a DataFrame.
3. **Data Cleaning**: Remove unnecessary columns and handle missing values.
4. **Data Transformation**: Convert data types and create feature vectors.
5. **Split Dataset**: Divide the data into training and testing sets.
6. **Apply Machine Learning Algorithms**: Use DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, and GBTClassifier to predict rainfall.
7. **Evaluate Models**: Compare the accuracy of different models and visualize the results.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following software installed:

- **Python 3.x**: The programming language used for the project.
- **PySpark**: The main framework used for big data processing.
- **MongoDB**: The NoSQL database used for storing and querying CSV data in Part B.
- **NLTK**: A library used for natural language processing tasks, specifically for removing stop words in Part A.
- **Matplotlib**: A Python library used for creating visualizations in all parts of the project.

### Installation

To set up and run the project locally, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/NguyenHuy190303/Big-Data-Processing.git
