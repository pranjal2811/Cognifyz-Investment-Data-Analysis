## Cognifyz Internship Project: Investment Data Analysis
Hello folks! My name is Pranjal Joshi, and I am delighted to present my project on Business Analytics, which I completed during my internship at Cognifyz Technologies. This project involved a comprehensive analysis of a dataset related to investment patterns, demographics, and financial expectations, providing valuable insights into consumer behavior within the investment banking sector.
# Project Overview
The core of this project was to perform an in-depth analysis of investment-related data. The primary goal was to understand various aspects of investment behavior, including gender distribution among investors, preferred investment avenues, reasons behind investment choices, and expectations from investments. The dataset provided a rich source of information for descriptive statistics, correlation analysis, and pattern identification.
# Objectives
The project was structured around several key objectives, divided into different levels of complexity:
•	Task 1: Data Overview
o	Understand the dataset structure, including the number of entries, columns, and data types.
o	Load the dataset using Python with pandas and gather descriptive statistics.
•	Task 2: Gender Distribution
o	Visualize the gender distribution within the dataset using appropriate charts.
•	Task 3: Descriptive Statistics for Numerical Columns
o	Present basic statistics (mean, median, standard deviation) for numerical columns such as age, mutual funds, equity market, debentures, government bonds, fixed deposits, PPF, and gold.
•	Task 4: Most Preferred Investment Avenue
o	Identify and quantify the most preferred investment avenue among participants.
•	Task 5: Reasons for Investment
o	Analyze and summarize the common reasons participants provided for their investment choices.
•	Task 6: Savings Objectives
o	Identify and describe the main savings objectives mentioned by participants.
•	Task 7: Common Information Sources
o	Analyze and summarize the common sources participants rely on for investment information.
•	Task 8: Investment Duration
o	Calculate the average investment duration among participants.
•	Task 9: Expectations from Investments
o	Summarize participants' expectations regarding returns from their investments.
•	Task 10: Correlation Analysis
o	Explore potential correlations between key factors like age, investment duration, and expected returns.
# What I Did
I utilized Python with popular libraries such as pandas for data manipulation, matplotlib.pyplot for data visualization, and seaborn for creating aesthetically pleasing statistical graphics.
1.	Data Loading and Initial Inspection (Task 1):
o	Loaded the Data_set 2 - Copy.csv file into a pandas DataFrame.
o	Used df.head() to view the first few rows and df.shape to check the dimensions (40 entries, 24 columns).
o	df.info() provided a summary of the DataFrame, showing no null values across all columns, with 8 numerical and 16 object (categorical) columns.
2.	Gender Distribution (Task 2):
o	Extracted gender information using df['gender'].value_counts().
o	Visualized the distribution using a pie chart:
	Male: 25 participants (62.5%)
	Female: 15 participants (37.5%)
3.	Descriptive Statistics for Numerical Columns (Task 3):
o	Identified numerical columns: age, Mutual_Funds, Equity_Market, Debentures, Government_Bonds, Fixed_Deposits, PPF, Gold.
o	Calculated and presented mean, median, and standard deviation for each:
| Column | Mean | Median | Std Dev |
 | :--------------- | :------ | :----- | :------- |
 | age | 27.80 | 27.0 | 3.56 |
 | Mutual_Funds | 2.55 | 2.0 | 1.197 |
 | Equity_Market | 3.475 | 4.0 | 1.132 |
 | Debentures | 5.75 | 6.5 | 1.676 |
 | Government_Bonds | 4.65 | 5.0 | 1.369 |
 | Fixed_Deposits | 3.575 | 3.5 | 1.796 |
 | PPF | 2.025 | 1.0 | 1.609 |
| Gold | 5.975 | 6.0 | 1.143 |
5.	Most Preferred Investment Avenue (Task 4):
o	Analyzed the Investment_Avenues column.
o	Result: 37 participants indicated "Yes" for investment avenues, while 3 indicated "No". This suggests a high inclination towards investment among respondents.
6.	Reasons for Investment (Task 5):
o	Explored columns like Reason_Equity, Reason_Mutual, Reason_Bonds, and Reason_FD.
o	Common Themes:
	Equity: "Capital Appreciation" and "Dividend" were key drivers.
	Mutual Funds: "Better Returns" and "Tax Benefits" were frequently cited.
	Bonds: "Safe Investment" and "Assured Returns" were prominent.
	Fixed Deposits: "Fixed Returns" and "High Interest Rates" were common reasons.
7.	Savings Objectives (Task 6):
o	Analyzed the What are your savings objectives? column.
o	Main Objectives:
	Retirement Plan: 21 participants (52.5%)
	Health Care: 8 participants (20.0%)
	Education: 7 participants (17.5%)
	Children's Future: 4 participants (10.0%)
o	This indicates that "Retirement Plan" is the most significant savings objective.
8.	Common Information Sources (Task 7):
o	Analyzed the Source column to identify preferred information channels.
o	Most Common Sources:
	Internet: 15 participants (37.5%)
	Financial Consultants: 10 participants (25.0%)
	Newspapers and Magazines: 8 participants (20.0%)
	Television: 7 participants (17.5%)
o	The internet is the leading source of investment information.
9.	Average Investment Duration (Task 8):
o	Converted the Duration column into a numerical format by mapping duration ranges to their midpoints or average years.
o	Average Investment Duration: Approximately 2.76 years.
	Less than 1 year: 8 participants
	1-3 years: 15 participants
	3-5 years: 13 participants
	More than 5 years: 4 participants
10.	Expectations from Investments (Task 9):
o	Summarized expectations from the Expect column.
o	Most Common Expectations:
	20%-30%: 24 participants (60.0%)
	10%-20%: 10 participants (25.0%)
	30%-40%: 4 participants (10.0%)
	More than 40%: 2 participants (5.0%)
o	A significant majority (60%) expect returns between 20% and 30%.
11.	Correlation Analysis (Task 10):
o	Performed correlation analysis between age, Duration_numeric, and Expect_numeric.
o	Correlation Matrix: | | age | Duration_numeric | Expect_numeric |
 | :------------- | :------- | :----------------- | :--------------- |
 | age | 1.00 | 0.28 | 0.04 |
| Duration_numeric | 0.28 | 1.00 | -0.05 |
| Expect_numeric | 0.04 | -0.05 | 1.00 |
o	Insights:
	There is a weak positive correlation (0.28) between age and Duration_numeric, suggesting older individuals might tend to invest for slightly longer durations, though the relationship is not strong.
	The correlation between age and Expect_numeric is almost negligible (0.04).
	The correlation between Duration_numeric and Expect_numeric is very weak and slightly negative (-0.05), indicating no significant linear relationship between how long someone invests and their expected returns.
# Results and Conclusion
The analysis provided a clear picture of the investment landscape based on the given dataset:
•	Demographics: The dataset comprised more male participants (62.5%) than female (37.5%), with the average age being around 27.8 years.
•	Investment Propensity: The vast majority of participants (37 out of 40) are already engaged in investments.
•	Key Investment Drivers:
o	The most significant savings objective is Retirement Planning (52.5%), highlighting a long-term financial planning mindset.
o	The Internet (37.5%) stands out as the primary source of investment information, underscoring the importance of digital platforms for financial literacy and decision-making.
•	Return Expectations: A large proportion of investors (60%) anticipate returns in the 20%-30% range, which could indicate a moderate to high-risk appetite.
•	Correlations: While some weak correlations were observed (e.g., between age and investment duration), no strong linear relationships were found between age, investment duration, and expected returns, implying that these factors might be influenced by a more complex interplay of variables.
This project provided valuable experience in data cleaning, exploratory data analysis, visualization, and interpreting statistical results, all crucial skills in the field of Business Analytics within the investment banking domain.
# Contact Information
Name: Pranjal Joshi

GitHub: https://github.com/pranjal2811

LinkedIn: https://www.linkedin.com/in/pranjaljoshi2811

Email: pranjaljoshi2811@gmail.com
