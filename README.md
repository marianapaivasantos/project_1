# Federal salaries analysis in Mexico 

The goal of this project is to analyze the federal salaries in Mexico. 

# Dataset

It was used the dataset Mexican Federal Government Salaries from the website kaggle.com. 
This dataset contains uncleaned salaries data in MXN for Mexican Federal employees.
So, the first step was to clean the data. I dropped columns that I wasn't going to use in my analysis, I dropped row with null values, and I also dropped rows that had values that didn't make sense, for example, rows where the gross salary was lower that the net salary. I also decided to drop the rows that reported years with little data.
I also created a "year" column, based on the end of the period date for each salary.

# Analysis

I started my analysis by checking the differences in average salaries between states, and found out there are three states that stand out for having the highest salaries, Baja California Sur, Chihuahua and Sinaloa.
Then I analyzed how the federal salaries in Mexico have evolved from 2015 through 2020. For my surprise, the data shows that these salaries are getting lower over the years, with the exception of 2018. I found that the Gini Coefficient of Mexico is 0.43, while the Gini Coefficient of the OECD (which Mexico is part of) is 0.32, showing that Mexico still has a long way ahead in fighting inequalities regarding wages.
The salary distribution shows that almost every salary is below 1 million MXN, with a few outliers that receive a higher salary (the average net salary is 12 919.24 MXN).
Looking at the average net and gross salaries, and nominal tax, I found an odd behavior. I would expect the salaries and the tax to move in the same direction, but I found the opposite, with the exception of the first time period (from 2015 to 2016), when both the salaries and the tax decreased. But when looking at the rest of the data, I found that when the salaries increased the tax decreased, and when the salaries decreased the tax increased. I am not sure why this is but might be related to changes in tax policies and/or changes in tax brackets.
Regarding the top paying jobs, Civil Protection Secretariat is on the top of the list, followed by Undersecretary of Coordination of Preventive Plans and Programs, and Director of Institutional Liaison.


# Major Obstacles

I had three major obstacles:
 - Understanding the data, and what was the meaning of each column 
 - Cleaning the data and still finding "unclean" things when I started the analysis
 - Data visualization, I wanted to do a map of the Mexico states, showing the salaries differences with different colour tones, but I wasn't able to do it.


Dataset: https://www.kaggle.com/datasets/ivansabik/mexican-federal-government-salaries
