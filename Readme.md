# Prosper Data Exploration

# Goal
In this project, we will be analyzing dataset from Prosper.com, a website where individuals can either invest in personal
loans or request to borrow money. The dataset contains 113,937 loans with 81 variables on each loan, including loan amount,
borrower income, borrower APR and interest rate .....etc.

# Instructions
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis 
process. In the first part, we will use Python visualization libraries to systematically explore a selected dataset, 
starting from plots of single variables and building up to plots of multiple variables. In the second part, we will 
produce a short presentation that illustrates interesting properties, trends, and relationships that we discovered in our
selected dataset. The primary method of conveying our findings will be through transforming our exploratory visualizations
from the first part into polished, explanatory visualizations.

# Analysis
Throught our analysis, these are our main findings:
+ the borrower APR has a negative correlation with the prosper score. A better prosper score gives borrower a lower APR.
+ the borrower APR has also a negative correlation with the prosper rating alpha. A bad rating alpha results in a high APR.
+ regardless of your employment status, the borrower APR decreases for a better prosper score and rating alpha.

# Tools
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that
we use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well
as Jupyter Notebooks. The following libraries are expected to be used in this project:
+ NumPy
+ pandas
+ Matplotlib
+ Seaborn
