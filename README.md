Objective:

The objective of this task is to perform Exploratory Data Analysis (EDA) to extract insights using statistical summaries and visual exploration techniques. The analysis focuses on identifying patterns, trends, relationships, and anomalies in the dataset.

Dataset:

Dataset Used: Titanic Dataset
Source: Kaggle

The dataset contains information about passengers aboard the Titanic, including survival status, age, gender, passenger class, fare, and other related attributes.

Tools & Libraries Used:

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab (execution environment)

EDA Techniques Performed:
1. Basic Data Exploration

.info() to understand data types and missing values

.describe() for statistical summary of numerical features

.value_counts() for categorical feature distribution

2. Univariate Analysis

Histogram for Age distribution

Boxplot for Fare to identify outliers and skewness

3. Bivariate Analysis

Survival vs Gender analysis

Survival vs Passenger Class analysis

4. Multivariate Analysis

Pairplot to analyze relationships between Age, Fare, and Survival

Correlation heatmap to identify feature correlations

Key Insights:

Female passengers had significantly higher survival rates than males

Passengers traveling in higher classes had better chances of survival

Higher fare-paying passengers were more likely to survive

Fare is positively correlated with survival, while passenger class is negatively correlated

Age shows a weaker influence on survival compared to gender and class

Outcome & Learning:

Through this task, I learned how to:

Perform structured Exploratory Data Analysis

Use visualizations to uncover hidden patterns and trends

Interpret statistical and visual findings meaningfully

Communicate insights clearly through observations and summaries

Files Included:

day5.ipynb– Jupyter Notebook containing code and analysis

EDA_Report.pdf – PDF report of findings

train.csv – Dataset used for analysis

README.md – Task documentation

Conclusion:

This EDA provided a deeper understanding of the Titanic dataset by uncovering key factors affecting passenger survival. The analysis demonstrates how data exploration supports data-driven insights and decision-making.
