# B2B Courier Charges Optimization Project

## Overview

This project involves analyzing and optimizing B2B courier charges based on various datasets such as order reports, invoices, pincode mappings, SKU masters, and courier company rates. The goal is to enhance the accuracy and efficiency of the charging process, leading to cost savings and improved customer satisfaction.

## Project Steps

### 1. Data Loading and Exploration

- Utilized Pandas library to read and load CSV files into DataFrames.
- Explored and examined the structure and content of each dataset.

### 2. Data Cleaning and Preparation

- Checked for missing values in each DataFrame and handled them appropriately.
- Removed unnecessary columns to streamline data processing.

### 3. Data Integration

- Merged relevant datasets to incorporate all necessary information for analysis.
- Renamed columns to prepare the desired DataFrame structure.

### 4. Expected Charges Calculation

- Calculated weight slabs and expected charges based on delivery zones, shipment types, and weight categories.
- Incorporated the calculated expected charges into the courier invoice data.

### 5. Analysis and Visualization

- Determined differences between actual charges and expected charges for each order.
- Summarized the accuracy of B2B courier charges.
- Visualized the summary using a pie chart to provide a clear representation of charge distribution.

## Results

The project provides valuable insights into the accuracy of B2B courier charges, highlighting the proportion of orders that were correctly charged, overcharged, and undercharged. By identifying discrepancies and optimizing the charging process, businesses can achieve cost savings and enhance operational efficiency.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies (Pandas, Plotly) using pip.
3. Execute the provided Python script to run the analysis.
4. Review the generated visualizations and summary to gain insights into the B2B courier charges.

## Dependencies

- Pandas: For data manipulation and analysis.
- Plotly: For data visualization.
