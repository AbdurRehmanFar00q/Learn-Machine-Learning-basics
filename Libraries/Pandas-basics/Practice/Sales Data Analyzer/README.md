# Sales Data Analyzer

A Python-based data analysis tool designed to process and interpret product sales performance from CSV datasets. This project leverages the `pandas` library to perform data cleaning, aggregation, and performance tracking.

## 🚀 Key Features

* **Automated Data Ingestion**: Seamlessly reads and parses `sales-data.csv` files.
* **Revenue Metrics**: Calculates the total sales volume across the entire dataset.
* **Product Benchmarking**: Programmatically identifies the top-performing product based on sales figures.
* **Categorical Summarization**: Groups and aggregates sales data by category to highlight segment performance.

## 📋 Data Structure Requirements

The program expects a `sales-data.csv` file in the root directory with the following column structure:

| Column | Description |
| :--- | :--- |
| **Product** | The name of the item sold. |
| **Category** | The department or classification of the product. |
| **Sales** | The numerical value representing sales revenue. |

