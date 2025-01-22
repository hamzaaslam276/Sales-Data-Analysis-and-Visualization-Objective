# Sales Data Analysis Project

## Overview
This project is a Python-based data analysis tool for processing and visualizing sales data. It performs data cleaning, statistical analysis, and visualization to gain insights into sales trends, product performance, and regional sales distribution.

## Features
- Creates a sample sales dataset for demonstration purposes.
- Cleans the data by removing duplicates and handling missing values.
- Calculates key statistics like total sales, average sales, and sales variance.
- Extracts specific data based on product and region.
- Generates visualizations:
  - Bar chart: Total sales by product.
  - Line chart: Sales trends over time.
  - Pie chart: Sales distribution across regions.

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- NumPy

## Usage
1. Run the main script:
   ```bash
   python sales_data_analysis.py
   ```
2. The script will:
   - Create and save a sample sales dataset as `sales_data.csv`.
   - Load and clean the dataset.
   - Perform statistical analysis and print the results.
   - Extract and display data for a specific product and region.
   - Generate and save visualizations as PNG files:
     - `product_sales_bar_chart.png`
     - `sales_trends_line_chart.png`
     - `region_sales_pie_chart.png`

## Code Overview
- **creat_data(data)**: Generates a sample dataset and saves it as a CSV file.
- **load_data(file_name)**: Loads data from a CSV file, handling file errors.
- **clean_data(data)**: Cleans the data by removing duplicates and imputing missing values.
- **calculate_statistics(data)**: Computes total sales, average sales, and sales variance.
- **extract_data(data, product, region)**: Filters data for a specific product and region.
- **create_visualizations(data)**: Generates bar, line, and pie charts for sales analysis.

## Example Output
- **Statistics:**
  - Total Sales: 1570.0
  - Average Sales: 174.44
  - Sales Variance: 6273.33
- **Visualizations:**
  - Bar chart of total sales per product.
  - Line chart of sales trends over time.
  - Pie chart of sales distribution by region.

