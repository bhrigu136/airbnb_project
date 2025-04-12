# Airbnb Data Analysis Project

## Overview

This project performs an exploratory data analysis (EDA) on Airbnb listing data, likely focusing on listings within New York City[cite: 4, 5, 16, 17, 34, 35]. The primary goal is to load, clean, explore, and understand the characteristics of Airbnb listings, potentially examining factors like pricing, availability, location, and reviews.

## Dataset

The analysis uses the `Airbnb_data.csv` dataset[cite: 1, 933]. This dataset contains information about Airbnb listings, including:
* Listing details (ID, Name, Host ID, Host Name) [cite: 2]
* Location information (Neighbourhood Group, Neighbourhood, Latitude, Longitude) [cite: 2]
* Listing specifics (Room Type, Price, Service Fee, Minimum Nights, Construction Year) [cite: 2, 22]
* Review metrics (Number of Reviews, Last Review Date, Reviews per Month, Review Rate) [cite: 2, 22]
* Host information (Identity Verified, Host Listings Count) [cite: 2, 22]
* Availability (Availability 365) [cite: 2]

## Analysis Steps

The Jupyter notebook `air bnb project.ipynb` [cite: 1] outlines the following steps:
1.  **Import Libraries:** Uses pandas, numpy, seaborn, and matplotlib for data manipulation, analysis, and visualization[cite: 1].
2.  **Load Data:** Reads the `Airbnb_data.csv` file into a pandas DataFrame[cite: 1].
3.  **Data Cleaning & Preprocessing:**
    * Handles missing values (e.g., filling missing review dates, dropping rows with missing names)[cite: 27, 29, 30].
    * Cleans numeric columns like 'price' and 'service fee' by removing currency symbols/commas and converting to numeric types[cite: 40].
    * Drops irrelevant or sparsely populated columns like 'license' and 'house_rules'[cite: 31].
    * Removes duplicate entries[cite: 49].
4.  **Exploratory Data Analysis (EDA):**
    * Examines data structure and types (`.info()`, `.columns`)[cite: 22, 25].
    * Calculates descriptive statistics (`.describe()`)[cite: 56].
    * Includes placeholders and initial code for data visualization (e.g., price distribution, listings per neighborhood)[cite: 58, 59, 60].

## Libraries Used

* pandas [cite: 1]
* numpy [cite: 1]
* matplotlib [cite: 1]
* seaborn [cite: 1]

## How to Use

1.  Ensure you have the required Python libraries installed.
2.  Place the `Airbnb_data.csv` file in the same directory as the notebook.
3.  Run the Jupyter notebook `air bnb project.ipynb` to execute the analysis.
