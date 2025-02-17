# NBA_data_analysis
I conducted this data analysis as a personal project. I found the dataset online and decided to analyze it as an exercise.

NBA Player Data Analysis

Overview

This project analyzes an NBA player dataset using Python, Jupyter Notebook, and the pandas library. The goal is to clean, transform, and visualize the data to extract meaningful insights about player attributes such as height, weight, salary, and age.

Steps in the Analysis

1. Loading the Data

The dataset was loaded into a Jupyter Notebook using the pandas library for data exploration.

2. Understanding the Dataset

Inspected the dataset to understand its structure and the types of data it contained.

Displayed the head and tail of the dataset.

Checked the size of the dataset.

3. Data Cleaning

Identified and removed duplicate data to maintain accuracy.

Found missing values (NaN) and removed non-available numbers to ensure a smooth analysis.

Converted height (feet-inches) to meters and weight (pounds) to kilograms using custom functions.

4. Exploratory Data Analysis (EDA)

After cleaning and transforming the data, several analyses were performed:

Descriptive Statistics

Generated a summary using .describe() to understand key statistics like mean, median, and distribution.

Data Visualizations

📊 Height vs. Weight Scatter Plot – Analyzed the relationship between player height and weight.

💰 Salary Distribution – Visualized salary variations among players.

📈 Age vs. Salary Scatter Plot – Investigated the impact of age on salary.

🎓 College Representation – Counted the number of players from each college.

🔍 Handling Missing Salary Values – Addressed missing salary data by choosing an appropriate method.

🔗 Correlation Between Age and Salary – Measured how strongly age influences salary.

📊 Histogram for Age Distribution – Showed the age spread of players.

Technologies Used

Python 🐍

Jupyter Notebook 📓

pandas (for data manipulation)

matplotlib & seaborn (for data visualization)

Conclusion

By systematically cleaning, transforming, and visualizing the dataset, this analysis provided valuable insights into NBA player characteristics and salary trends. The project showcases the importance of data preprocessing and exploratory analysis in deriving meaningful conclusions.

How to Run the Notebook

Clone this repository:

git clone https://github.com/yourusername/your-repo.git

Install dependencies:

pip install pandas matplotlib seaborn jupyter

Open the Jupyter Notebook:

jupyter notebook

Run the analysis and explore the insights!

Future Improvements

Add machine learning models to predict player salaries based on attributes.

Expand the dataset for deeper insights into player performance.

📌 Author: Your Name📌 GitHub: Your GitHub Profile📌 License: MIT License
