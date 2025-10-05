Titanic Data Analytics Project – Executive Summary <br>
Overview <br>
This project analyzes the Titanic dataset to identify the factors that influenced passenger 
survival. The work involved data cleaning, feature engineering, exploratory data analysis 
(EDA), and insights reporting. No predictive modeling was applied; the focus was on 
understanding the data and communicating findings clearly.  <br>

Data Preparation  <br>
• Reviewed the dataset structure, distributions, and missing values.  <br>
• Filled in missing values for Age and Embarked; dropped Cabin due to excessive nulls.  <br>
• Converted categorical variables (Sex, Embarked) into numerical form.  <br>
• Created additional features to enhance analysis:  <br>
o FamilySize = SibSp + Parch + 1   <br>
o IsAlone = indicator for solo travelers  <br>
o AgeGroup = Child, Teen, Adult, Senior  <br>
o Title = extracted from passenger names  <br>

Exploratory Data Analysis  <br>
Gender  <br>
• Female survival rate: 74%  <br>
• Male survival rate: 19%  <br>
Women were about four times more likely to survive than men.  <br>

Passenger Class  <br>
• First Class: 63% survived  <br>
• Second Class: 47% survived  <br>
• Third Class: 24% survived  <br>
Higher social classes were associated with greater survival chances.  <br>

Age  <br>
• Average age: 29.7 years   <br>
• Children (<12): 58% survived  <br>
• Adults (20–49): 36% survived  <br>
• Seniors (50+): 23% survived  <br>
Younger passengers were more likely to survive. <br>

Family Size  <br>
• Solo travelers: 30% survived  <br>
• With family: 51% survived  <br>
Passengers traveling with family had better survival rates.  <br>

Fare   <br>
• Lower fares: 19% survived  <br>
• Higher fares: 62% survived  <br>
Wealthier passengers had significantly higher survival chances.  <br>

Port of Embarkation  <br>
• Cherbourg: 55% survived  <br>
• Queenstown: 39% survived  <br>
• Southampton: 34% survived <br> 

Correlation Analysis  <br>
• Sex (–0.54) and Passenger Class (–0.34) had the strongest correlations with survival.  <br>
• Fare (+0.26) showed a positive relationship with survival.  <br>
• Age (–0.08) had only a weak negative correlation.   <br>

Key Insights   <br>
• Gender and passenger class were the most important survival factors.  <br>
• Women, children, and first-class passengers had the best survival outcomes. <br> 
• Family presence and higher fares improved chances of survival.  <br>
• Economic and social status were decisive in shaping survival odds.   <br>

Skills Practiced  <br>
• Data cleaning and preprocessing with Pandas and NumPy  <br>
• Exploratory data analysis with Matplotlib and Seaborn  <br>
• Feature engineering and handling missing values   <br>
• Visualizing and reporting insights in a clear, accessible way  <br>

Conclusion  <br>
This project demonstrates the complete workflow of a data analyst: progressing from raw 
data to well-structured insights. Even without machine learning, the analysis reveals how 
social, economic, and demographic factors strongly influenced survival on the Titanic.
