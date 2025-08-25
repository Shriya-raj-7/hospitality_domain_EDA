# Exploratory Data Analysis in the Hospitality Domain

## Project Overview
This project performs Exploratory Data Analysis (EDA) for an imaginary hotel chain called **AtliQ Grands**. The company operates hotels in four major Indian cities—Delhi, Mumbai, Bangalore, and Hyderabad. Facing declining market share and revenue due to increased competition, the company aims to adopt data-driven decision-making.

The analysis uses booking data from various sources to uncover patterns in room types, booking platforms, and cancellation behavior, and to support AtliQ Grands' goal of increasing revenue through data insights.

## Objectives
- Load and explore hotel booking data from multiple CSV files
- Identify trends in room categories and booking platforms
- Analyze cancellation rates and revenue distribution
- Provide insights to guide business decisions

## Datasets Used
The project is based on six CSV files:

- `dim_date.csv`: Calendar date reference table
- `dim_hotels.csv`: Details about hotel branches and locations
- `dim_rooms.csv`: Types of rooms and their categories
- `fact_aggregated_bookings.csv`: Aggregated bookings data
- `fact_bookings.csv`: Raw transactional booking data
- `new_data_august.csv`: Additional August booking data

All datasets are stored in the `datasets/` folder.

## Tools and Libraries
- Python
- Pandas
- Jupyter Notebook

## Folder Structure
hospitality_domain_EDA/
├── datasets/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   ├── fact_bookings.csv
│   └── new_data_august.csv
└── EDA in Hospitality Domain.ipynb

