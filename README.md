Sales Data Analysis for Retail Store
Overview
This repository contains a Python-based data analysis project focused on analyzing sales data for a retail store using statistical approaches. The project leverages descriptive and inferential statistics to uncover trends, test hypotheses, and visualize sales performance across different product categories.
Project Description
In a competitive retail environment, understanding sales performance is crucial for informed decision-making. This project analyzes synthetic sales data for 20 products across four categories (Electronics, Clothing, Home, and Sports) to:

Perform descriptive statistics to summarize sales data.
Conduct inferential statistics to test hypotheses regarding average sales.
Visualize sales performance for better decision-making.

Dataset
The dataset is synthetically generated and includes the following features:

product_id: Unique identifier for each product.
product_name: Name of the product.
category: Product category (Electronics, Clothing, Home, Sports).
units_sold: Number of units sold (generated using a Poisson distribution).
sale_date: Date of the sale.

Repository Structure

sales_data_analysis.py: Python script containing the complete analysis, including data generation, descriptive statistics, inferential statistics, and visualizations.
sales_data.csv: Generated synthetic sales data.
requirements.txt: List of required Python libraries.

Installation

Clone the repository:
git clone https://github.com/<your-username>/Retail-Sales-Analysis.git
cd Retail-Sales-Analysis


Install the required dependencies:
pip install -r requirements.txt

Required libraries: pandas, numpy, matplotlib, seaborn, scipy.

Run the analysis script:
python sales_data_analysis.py



Analysis Performed
Descriptive Statistics

Mean, Median, Mode: Summarizes the central tendency of units sold.
Variance and Standard Deviation: Measures the variability in sales.
Category Statistics: Aggregates total and average sales per category.

Inferential Statistics

Confidence Interval: Estimates the range containing the population mean of units sold.
Hypothesis Testing: Tests whether the average sales volume significantly differs from a target of 20 units.

Visualizations

Histogram: Displays the distribution of units sold with mean, median, and mode.
Boxplot: Shows the spread and outliers of units sold by category.
Bar Plot: Summarizes total sales by category.

Usage
To execute the analysis:

Ensure all dependencies are installed.
Run the sales_data_analysis.py script to generate the dataset, perform statistical analysis, and create visualizations.
The script will output:
Descriptive statistics (mean, median, mode, variance, standard deviation).
Category-wise statistics.
Confidence intervals (95% and 99%).
Hypothesis test results (t-test).
Visualizations saved as images (histogram, boxplot, bar plot).



Example Output

Descriptive Statistics:Mean Units Sold: 18.80
Median Units Sold: 18.50
Mode Units Sold: 17
Variance of Units Sold: 10.91
Standard Deviation of Units Sold: 3.30


Category Statistics:   Category  Total Units Sold  Average Units Sold  Std Dev of Units Sold
0  Clothing               21              21.00                    NaN
1  Electronics            73              18.25                   2.22
2  Home                  181              20.11                   3.72
3  Sports                101              16.83                   2.71


Confidence Interval (95%):(17.25, 20.35)


Hypothesis Test:T-statistic: -1.63, P-value: 0.12
Fail to reject the null hypothesis: The mean units sold is not significantly different from 20.



Visualizations
The script generates:

A histogram of units sold with mean, median, and mode lines.
A boxplot showing sales distribution by category.
A bar plot of total units sold per category.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
License
This project is licensed under the MIT License.
