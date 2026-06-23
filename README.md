# Tips-Data-cleaning

Project Overview:

- Objective: To compare the data visualization capabilities and syntax of two core Python libraries: Matplotlib and Seaborn.

- Task: Recreate five specific types of charts (Bar chart,Histogram, Box plot, Scatter plot, Heatmap) using both libraries.

- Dataset: Used the built-in restaurant "tips" dataset.

- Requirements: Customize aesthetics (titles, labels, font sizes, color palettes) and export at least one visualization as a .png file.

Link to Project Page: https://roadmap.sh/projects/data-visualization-tutorial

Dataset

Source: Kaggle Tips Dataset

File used: tips.csv

-----------------------------------------------------------------------------------------------------------------------------------------------------

Technologies Used:

- Python

- Pandas

- Matplotlib

- Seaborn

-----------------------------------------------------------------------------------------------------------------------------------------------------

Data Exploration:

- Distribution Analysis: Examined how the total_bill amounts are spread out using a Histogram.

- Categorical Comparison: Analyzed how the total_bill varies across different days of the week using Bar charts and Box plots.

- Relationship Mapping: Investigated the direct relationship between total_bill and tip amounts using a Scatter plot.

- Correlation Tracking: Isolated numeric variables to calculate and visualize their mathematical relationships using a Heatmap.

-----------------------------------------------------------------------------------------------------------------------------------------------------

Key Insights:

- Seaborn requires significantly less code for statistical plots (like automatically calculating means for bar charts), while Matplotlib requires more manual setup.

- Most bills fall into a lower range, with a few very high bills.

- Visually identifiable positive correlation between the total bill amount and the tip given (as the bill increases, the tip generally increases).

-----------------------------------------------------------------------------------------------------------------------------------------------------

visualizations:

- Bar chart
- Histogram
- Box plot
- Scatter plot
- Heatmap

-----------------------------------------------------------------------------------------------------------------------------------------------------

Conclusion:

- The project successfully demonstrated how to translate the same dataset into visual insights using two different tools.

- While Seaborn is generally faster and more visually appealing out-of-the-box for Exploratory Data Analysis (EDA), an understanding of Matplotlib remains essential since Seaborn is built on top of it and relies on it for deep customizations.
