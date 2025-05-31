# Hotel Domain Analysis using Python
## 📌 Problem Statement
AtliQ Grands, a well-established hotel chain in India, is facing increasing competition and a decline in revenue. To address these challenges, the management has opted for a data-driven approach but lacks internal expertise. They have engaged external support to analyze business data, uncover insights, and develop strategies to improve customer retention and boost profitability.

## 🎯 Project Goal
This project aims to perform a comprehensive analysis of the hotel domain using Python. By leveraging data analytics, the objective is to deliver actionable insights and strategic recommendations that will help AtliQ Grands make informed decisions, overcome current challenges, and regain a competitive edge in the hospitality industry.

## Data

The dataset used for this analysis is available in the `datasets` directory. It is provided in a CSV format and contains the following columns:

- `dim_date.csv`: This dataset contains information about dates and related attributes.
- `dim_hotels.csv`: This dataset contains details about different hotels, including their types and locations.
- `dim_rooms.csv`: This dataset provides information about the rooms available in the hotels, such as room types and capacities.
- `fact_aggregated_bookings.csv`: This dataset contains aggregated information about hotel bookings, including the total number of bookings and revenue for each hotel.
- `fact_bookings.csv`: This dataset contains individual booking records with specific details, including booking dates, customer information, and room details.
- `new_data_august.csv`: This dataset contains additional data for the month of August, which can be used to update and enrich the existing analysis.

Please refer to the individual CSV files to explore the data in detail and understand the structure and content of each dataset.

## Contents

The repository is organized as follows:

- `datasets`: This directory contains the hotel booking dataset in CSV format.

- `Atliq Grands Hotel Analysis.ipynb`: This Jupyter Notebook file contains the code for the data analysis. It utilizes Python and various libraries such as Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

## Project Highlights

1. Data Cleaning- Handling missing values and outliers.
2. Data Transformation - Added occupancy% columns.
3. Insights generation-key questions answered 
   1. calculating average  occupaancy rate by room type and city. 
   2. Identifying occupancy rate on weekdays and weekends.
   3. Analyzing  revenue generated per city.
   4. Analyzing monthly revenue trends.
   5. Assessing revenue by booking platforms.

## 🧠 Skills Learned
-  🐍 Python Programming: Gained hands-on experience in data analysis, cleaning, transformation, and visualization using Python.

-  📊 Data Visualization: Utilized libraries like Matplotlib to create meaningful charts, bar plots, and other visual insights.

-  🗃️ Pandas Fundamentals: Worked extensively with DataFrames—applying functions such as groupby(), concat(), merge(), handling missing values (NaN), and reading CSV files efficiently.
## Conclusion
The analysis offers meaningful insights into hotel performance, including occupancy trends, revenue patterns, and booking behaviors. The visualizations and key findings support data-driven decision-making, enabling AtliQ Grands to streamline operations, enhance service delivery, and improve overall customer satisfaction.

