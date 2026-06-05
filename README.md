# README – Sales Data Analysis Project

## Project Title

**Sales Data Analysis Using Python**

## Project Description

This project generates a fake retail sales dataset using the Faker library and analyzes sales performance across different stores, products, and regions. Various visualizations are created to understand sales trends and patterns.

## Objectives

* Generate synthetic sales data.
* Analyze sales performance.
* Visualize trends using charts and graphs.
* Identify sales patterns across products and regions.

## Technologies Used

* Python
* Pandas
* NumPy
* Faker
* Matplotlib
* Seaborn
* Plotly

## Dataset Fields

| Column | Description          |
| ------ | -------------------- |
| Date   | Date of Sale         |
| Store  | Store Name           |
| Item   | Product Name         |
| Region | Sales Region         |
| Sales  | Number of Units Sold |

## Features

* Data generation using Faker.
* Data cleaning and duplicate removal.
* Total, Average, Maximum, and Minimum sales calculation.
* Sales trend analysis.
* Product-wise sales analysis.
* Region-wise sales analysis.
* Correlation analysis.

## Sample Output

```text
Total Sales: 255430
Average Sales: 255.43
Max Sales: 500
Min Sales: 10
```

*Note: Values vary each time because the dataset is randomly generated.*

## Visualizations Generated

1. Sales Trend Over Time
2. Monthly Sales Bar Chart
3. Product-wise Sales Chart
4. Region-wise Sales Pie Chart
5. Sales Distribution Histogram
6. Sales Box Plot
7. Correlation Heatmap

## How to Run

```bash
pip install pandas numpy faker matplotlib seaborn plotly
python sales_analysis.py
```

## Conclusion

This project demonstrates data generation, preprocessing, statistical analysis, and visualization techniques using Python. It is useful for learning business analytics and data visualization concepts.
