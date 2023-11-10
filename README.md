# Retail Sales Analysis

This project is about the analysis and prediction of retail sales data happening in betwwen certain years in different stores and departments under different conditions and factors.

## Dataset

Stores Dataset: Anonymized information about the 45 stores, including store ID, type (A, B, C), and size.

Features Dataset: Additional data related to the store, department, and regional activity for specific dates, including temperature, fuel price, promotional markdowns (MarkDown1-5), consumer price index (CPI), unemployment rate, and information about special holiday weeks.

Sales Dataset: Historical sales data covering three years, including store ID, department ID, week start date, weekly sales, and information about special holiday weeks.

## Requirements

To run this project, the following libraries are needed:

NumPy: A library for numerical computations in Python.

Pandas: A library for data manipulation and analysis.

Scikit-learn: A machine learning library that provides various regression and classification algorithms.

Matplotlib: A plotting library for creating visualizations.

Seaborn: A data visualization library built on top of Matplotlib. Make sure these libraries are installed in your Python environment before running the project.

## Exploratory Data Analysis (EDA)

Seasonal Patterns: Clear sales spikes were observed during November-December in 2010 and 2011, but this pattern was missing in 2012.

Markdowns: No significant trend between markdowns and sales was found. Assumptions about markdowns being promotions did not hold.

## Steps of the project

Exploratory Data Analysis (EDA): Use pandas, matplotlib, and seaborn libraries to explore the dataset. Analyze different variables, their distributions, and relationships. Generate visualizations such as histograms, scatter plots, or box plots to gain insights into the data.

Machine Learning Regression: Apply various machine learning regression algorithms to predict the selling price of industrial copper. Split the dataset into training and testing sets, train the models, and evaluate their performance using metrics such as mean squared error (MSE).

Machine Learning Classification: Apply different machine learning classification algorithms to predict the status (won or lost) of copper transactions. Split the dataset into training and testing sets, train the models, and evaluate their performance using metrics such as accuracy, precision, and recall.

Documentation: Prepare a comprehensive documentation summarizing the steps involved in the analysis, including the preprocessing techniques, machine learning algorithms used, and their performance. Include visualizations and interpretations to effectively communicate the results.

## Conclusion

The project successfully built regression models to predict sales across different stores and departments with the impact of markdowns. The insights gained from the analysis help in providing actions to enhance business strategies and drive sales.