# Restaurant Recommendation System using Yelp Dataset

## Overview

This project was developed for the **B141 Data Mining** module. The objective is to analyze restaurant data from the Yelp Open Dataset using Python and Apache Spark to discover business patterns, perform customer-oriented analytics, and build a simple recommendation system.

The project demonstrates a complete data mining workflow including data understanding, preprocessing, exploratory data analysis, customer segmentation, and restaurant recommendation.

---

## Technologies Used

* Python
* Apache Spark (PySpark)
* Pandas
* Jupyter Notebook
* VS Code
* Git & GitHub

---

## Project Structure

```text
restaurant-recommendation-system/
└── yelp_cleaned_restaurants/
    ├── 1_understanding.ipynb
    ├── 2_preprocessing.ipynb
    ├── 3_analysis.ipynb
    ├── 4_segmentation.ipynb
    ├── 5_recommendation.ipynb
    ├── cleaned_yelp_restaurants.csv
    ├── processed_yelp_restaurants.csv
    ├── analysis_yelp_restaurants.csv
    ├── segmented_yelp_restaurants.csv
    └── ReadMe.md
```

---

## Project Workflow

### 1. Data Understanding

* Loaded the Yelp restaurant dataset.
* Examined dataset dimensions.
* Explored data types.
* Calculated descriptive statistics.
* Identified unique values.

### 2. Data Preprocessing

* Removed duplicate records.
* Checked and handled missing values.
* Selected relevant restaurant attributes.
* Standardized categorical information.
* Prepared the dataset for analysis.

### 3. Exploratory Data Analysis

* Analysed restaurant ratings.
* Studied review count distribution.
* Compared restaurant performance across cities and states.
* Generated summary statistics and insights.

### 4. Restaurant Segmentation

Restaurants were segmented based on:

* Star ratings
* Review counts
* Business popularity
* Customer engagement

This helps identify high-performing restaurants and distinguish them from lower-performing businesses.

### 5. Recommendation System

A simple recommendation system was created that recommends restaurants using:

* Restaurant ratings
* Number of reviews
* Location
* Business categories

---

## Dataset

This project uses the **Yelp Open Dataset**.

Dataset:
https://business.yelp.com/data/resources/open-dataset/

---

## Repository

GitHub Repository:

https://github.com/ranavijayender/restaurant-recommendation-system

---

## Author

**Vijayender Singh Rana**

MSc Data Science, AI and Digital Business

GISMA University of Applied Sciences

Module: **B141 Data Mining**

---

## License

This repository has been created solely for academic purposes as part of the B141 Data Mining module.
