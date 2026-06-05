# Data Cleaning & Visualization Project

## Project Overview

This project focuses on cleaning, preprocessing, and visualizing a retail sales dataset using Python. The objective is to transform raw business data into meaningful insights through data analysis and visualization techniques.

## Objectives

* Understand the structure of a real-world dataset.
* Perform data cleaning and preprocessing.
* Detect and handle outliers.
* Analyze sales and profit trends.
* Create meaningful visualizations.
* Extract business insights from data.

## Dataset Information

The project uses the Superstore Sales Dataset, which contains information about:

* Orders
* Customers
* Products
* Sales
* Profit
* Discounts
* Regions
* Categories

### Dataset Statistics

* Total Records: 9,994
* Total Columns: 21
* Missing Values: 0
* Duplicate Records: 0

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Project Workflow

### 1. Data Loading

Loaded the dataset into a Pandas DataFrame for analysis.

### 2. Data Exploration

Performed:

* Data type inspection
* Statistical summary
* Dataset shape analysis
* Missing value detection

### 3. Data Cleaning

* Verified missing values
* Removed duplicate records
* Prepared data for analysis

### 4. Outlier Detection

Used the Interquartile Range (IQR) method to identify and remove extreme values from the Sales column.

### 5. Data Visualization

Created the following visualizations:

#### Sales Distribution

Shows the distribution of sales across all transactions.

#### Sales by Category

Compares total sales among different product categories.

#### Profit Distribution

Displays the frequency distribution of profit values.

#### Correlation Heatmap

Visualizes relationships between numerical features such as Sales, Quantity, Discount, and Profit.

## Key Insights

* Technology products generated the highest sales.
* Profit varies significantly across transactions.
* Discounts have an impact on profitability.
* Sales and profit exhibit different distribution patterns.
* Outlier removal improved the reliability of visual analysis.

## Project Structure

Data-Cleaning-Visualization-Project/

├── dataset/
│ └── superstore.csv

├── notebook/
│ └── Data_Cleaning_Visualization.ipynb

├── images/
│ ├── sales_distribution.png
│ ├── sales_by_category.png
│ ├── profit_distribution.png
│ └── correlation_heatmap.png

├── README.md

└── requirements.txt

## Installation

Install the required libraries:

pip install pandas numpy matplotlib seaborn

## Running the Project

1. Open Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Run all notebook cells sequentially.
4. Review generated visualizations and insights.

## Results

The project successfully demonstrates:

* Data preprocessing
* Data cleaning
* Outlier handling
* Exploratory Data Analysis (EDA)
* Business insight generation
* Data storytelling through visualization

## Future Enhancements

* Interactive dashboards using Tableau or Power BI
* Sales forecasting using Machine Learning
* Customer segmentation analysis
* Advanced business intelligence reporting

## Author

Santhosh Ganji

B.Tech Student | Data Analytics & Machine Learning Enthusiast

## License

This project is intended for educational and internship submission purposes.
