# 911-Response-Insights-A-Case-Study-in-Data-Analysis
911 Response Insights: A Case Study in Data Analysis
This repository contains a Python code for analyzing 911 emergency response data. The dataset used in this analysis includes information such as emergency call type, timestamp, location (zipcode and township), and reason for the call (e.g., traffic, fire, EMS).

Basic Overview
The Python code provided performs various data analysis tasks and visualizations using the Pandas, NumPy, Matplotlib, and Seaborn libraries. Below is a summary of the tasks performed:

Data Loading and Inspection
The code begins by loading a CSV file named 911.csv into a Pandas DataFrame and inspects the basic structure and content of the dataset.

Basic Questions
It then answers several basic questions about the dataset, such as identifying the top 5 zip codes and townships with the most 911 calls and determining the number of unique title codes.

Creating New Features
New features are created based on existing data, such as extracting the reason for the call from the 'title' column and deriving time-related features like hour, month, and day of the week from the 'timeStamp' column.

Data Visualization
Various visualizations are created using Seaborn and Matplotlib to gain insights from the data, including:

Countplots of 911 calls by reason, day of the week, and month.
Line plots showing the count of calls per month and per day for different reasons.
Heatmaps and clustermaps to visualize patterns in calls by day of the week and hour, and day of the week and month.
Files Included
911.ipynb: Jupyter Notebook containing the Python code.
911.csv: Dataset used for analysis.
How to Use
Ensure you have Python installed on your system.
Clone or download the repository to your local machine.
Open the Jupyter Notebook (911.ipynb) using Jupyter Notebook or JupyterLab.
Run each cell in the notebook sequentially to see the analysis results and visualizations.
Dependencies
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This analysis is inspired by real-world emergency response data and is meant for educational purposes. The dataset used here is sourced from a publicly available dataset.
