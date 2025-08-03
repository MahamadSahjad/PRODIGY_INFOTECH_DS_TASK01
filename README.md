# PRODIGY_INFOTECH_DS_TASK01
Data analysis and visualization projects from my internship at Prodigy InfoTech.
Prodigy InfoTech Data Science Internship - Task 01
A comprehensive analysis of the World Population dataset to visualize population distributions and trends.

🔹 Task Objective
To create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.

🔹 Dataset
The dataset used for this task is the World Population Dataset, which contains records for various population metrics from 2001 to 2022. The data is structured with different series codes representing specific metrics:

SP.POP.TOTL: Total Population

SP.POP.TOTL.FE.IN: Female Population

SP.POP.TOTL.MA.IN: Male Population

SP.POP.TOTL.FE.ZS: Female Population (% of total)

SP.POP.TOTL.MA.ZS: Male Population (% of total)

🔹 My Approach & Workflow
My process for completing this task involved several key steps:

Data Loading & Inspection: Loaded the dataset using Pandas and performed an initial inspection to understand its structure, columns, and data types using .head(), .info(), and .describe().

Data Cleaning: Checked for missing values (.isna().sum()) and duplicate rows (.duplicated().sum()) to ensure data quality. Dropped unnecessary columns like Series Name and Country Code to simplify the DataFrame.

Data Filtering & Sorting:

Filtered the DataFrame to isolate specific population metrics (e.g., total, male, female populations) using the Series Code.

Sorted the data based on the 2022 population to identify the top and bottom 10 countries.

Data Visualization:

Created bar charts to compare the populations of the top and bottom 10 countries for different years (2022, 2016, 2010, 2001).

Generated separate bar charts to visualize the highest and lowest male and female populations.

Developed stacked bar charts to show the composition of male and female populations for the top and bottom 10 countries in 2022, providing a clear gender distribution view.

🔹 Key Visualizations & Insights
1. Top 10 Most Populous Countries (2022)
This bar chart highlights the countries with the largest total populations.
(You can insert an image of your chart here)
Insight: India and China are clear outliers, with populations significantly larger than the rest of the world. The United States, Indonesia, and Pakistan form the next tier.

2. Top 10 Least Populous Countries (2022)
This chart shows the countries and territories with the smallest populations.
(You can insert an image of your chart here)
Insight: The least populous entities are primarily small island nations like Tuvalu and Nauru, demonstrating the vast scale difference in global populations.

3. Gender Distribution in Top 10 Countries (2022)
The stacked bar chart visualizes the male vs. female population counts in the most populous countries.
(You can insert an image of your stacked bar chart here)
Insight: While the total numbers are massive, the gender distribution in most of these countries is close to a 50/50 split, with slight variations.

🔹 Tools and Libraries Used
Python: The core programming language for the analysis.

Pandas: Used for data manipulation, cleaning, and analysis.

NumPy: Utilized for numerical operations.

Matplotlib: Used for creating the plots and visualizations.

Seaborn: Used for creating more aesthetically pleasing statistical plots.

Jupyter Notebook: The environment used for writing and executing the code.

🔹 How to Run This Project
To reproduce this analysis, you can follow these steps:

Clone the repository:

git clone https://github.com/YourUsername/YourRepoName.git

Navigate to the project directory:

cd YourRepoName

Ensure you have the required libraries installed:

pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook file (YourNotebookName.ipynb) to view and run the code.

🔹 Conclusion
This task provided valuable practice in data cleaning, filtering, and visualization. Through bar charts and stacked plots, I was able to effectively illustrate the vast differences in population sizes across the globe and analyze gender distributions within the most and least populous nations.
