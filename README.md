# IBM Applied Data Science Capstone Project

## Overview

This repository contains the work done for the **IBM Applied Data Science Capstone Project**, part of the IBM Data Science Professional Certificate. The project involves various data science tasks, including data collection, analysis, visualization, and machine learning.

## Project Description

The project aims to apply data science concepts to real-world problems by analyzing datasets, cleaning and preparing data, building models, and presenting the findings. The project focuses on several key areas:

- **SpaceX Launch Data**: Analyzing SpaceX's historical launch data to predict the success of future missions.
- **SQL and API Usage**: Leveraging SQL and APIs to retrieve, store, and analyze data.
- **Geo-location**: Using geo-location data for mapping and site analysis.
- **Machine Learning Models**: Implementing various models to solve classification and regression problems.

## Project Structure

```
├── notebooks/
│   ├── SpaceX_Launch_Analysis.ipynb
│   ├── API_Data_Collection.ipynb
│   ├── SQL_Queries.ipynb
│   └── Geo-Location_Analysis.ipynb
├── data/
│   ├── spacex_data.csv
│   └── geo_data.csv
├── README.md
└── requirements.txt
```

### Notebooks

- **SpaceX_Launch_Analysis.ipynb**: This notebook analyzes SpaceX launch data to explore patterns in success rates, launch locations, and other variables.
- **API_Data_Collection.ipynb**: Demonstrates how to collect data from APIs and use it for analysis.
- **SQL_Queries.ipynb**: Contains SQL queries for data manipulation and analysis.
- **Geo-Location_Analysis.ipynb**: Performs geospatial analysis using launch sites' geo-coordinates.

### Data

- **spacex_data.csv**: A CSV file containing historical SpaceX launch data.
- **geo_data.csv**: Geo-location data used for mapping and site analysis.

## Requirements

To run the notebooks, install the necessary Python packages:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file includes essential libraries like:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Requests
- SQLite3

## Project Outcomes

- **Predictive Models**: Built machine learning models to predict the success or failure of SpaceX launches based on historical data.
- **Data Visualization**: Created insightful visualizations of launch data and geo-spatial analysis.
- **SQL Integration**: Demonstrated the power of SQL for querying large datasets.
- **API Data Integration**: Collected and analyzed data using public APIs.


