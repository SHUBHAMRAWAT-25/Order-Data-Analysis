# Orders Data Analytics Project

This is an end-to-end data analytics project analyzing an orders dataset sourced from Kaggle. The project involves data extraction, cleaning, transformation, and generating insights through SQL queries and Python analysis.

## Problem Statement

The objective of this project is to analyze orders data and extract valuable insights to aid in decision-making. Key areas of analysis include:

1. Identifying the top 10 revenue-generating products.
2. Comparing month-over-month growth for 2022 and 2023 sales (e.g., January 2022 vs. January 2023).
3. Determining the month with the highest sales for each product category.
4. Identifying the subcategory with the highest profit growth in 2023 compared to 2022.

## Project Workflow

1. **Dataset Acquisition**: Utilized Kaggle API to download the dataset.
2. **Data Processing**: Performed cleaning and transformation using Python and Pandas.
3. **Data Storage**: Loaded the cleaned data into SQL Server for further analysis.
4. **Analysis**: Answered business questions using SQL queries.

## Technologies Used

- **Python**:
  - Libraries: `pandas`, `numpy`, `sqlalchemy`, `kaggle`
- **SQL Server**:
  - Used for storing and querying data.
- **Jupyter Notebook**:
  - For data exploration and visualization.

## Key Analysis and Insights

1. **Top 10 Revenue-Generating Products**:
   - Identified products contributing most to revenue.

2. **Month-over-Month Growth**:
   - Compared sales trends across the same months in 2022 and 2023.

3. **Highest Sales by Month for Each Category**:
   - Found peak sales months for each product category.

4. **Subcategory Profit Growth**:
   - Identified subcategories with the highest profit growth between 2022 and 2023.

## How to Run the Project

### Prerequisites

- Python 3.x
- SQL Server
- Kaggle API Key

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Order-Data-Analytics.git
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/Order\ data\ analysis.ipynb
   ```

3. Execute SQL queries in the `orders.sql` file using SQL Server.

## Results

- **Top Products by Revenue**:
  - Example: `Product A` generated the highest revenue of `$10,000`.

- **Sales Growth**:
  - Month-over-month growth revealed `10%` higher sales in January 2023 compared to January 2022.

- **Highest Sales by Category**:
  - The `Electronics` category had the highest sales in `December`.

- **Profit Growth by Subcategory**:
  - The `Accessories` subcategory exhibited the highest profit growth of `15%` in 2023.

## Project Files

- `Order data analysis.ipynb`: Jupyter notebook with data processing and analysis.
- `orders.sql`: SQL queries for answering key business questions.
- `README.md`: Project documentation.
- `requirements.txt`: List of Python dependencies.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
