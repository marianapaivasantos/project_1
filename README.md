# Federal salaries analysis in Mexico 

The goal of this project is to analyze the federal salaries in Mexico. 

# Dataset

It was used the dataset Mexican Federal Government Salaries from the website kaggle.com. 
This dataset contains uncleaned salaries data in MXN for Mexican Federal employees.
So, the first step was to clean the data. I dropped columns that I wasn't going to use in my analysis, I dropped row with null values, and I also dropped rows that had values that didn't make sense, for example, rows where the gross salary was lower that the net salary. I also decided to drop the rows that reported years with little data.
I also created a "year" column, based on the end of the period date for each salary.

# Analysis

# Hypothesis
 1) Salaries vary significantly according to the state
 2) Salaries exhibit temporal variations influenced by economic cycles
 3) Salaries follow a non-uniform distribution with potential inequalities
 4) Over time, salaries have undergone changes along with fluctuations in tax rates
 5) Certain occupations are likely to be identified as top-paying jobs

# Conclutions 
I started my analysis by checking the differences in average salaries between states, and found out there are three states that stand out for having the highest salaries, Baja California Sur, Chihuahua and Sinaloa. These states are near each other and Chihuahua is actually on the boarder with the USA, which might help justificate having highest salaries. 

Then I analyzed how the federal salaries in Mexico have evolved from 2015 through 2020. For my surprise, the data show that the salaries have decrease through time, except for 2018.  Mexico economy has increased between 2015 and 2019, so I would except the salaries followed that as well, but they didn't.

The salary distribution shows that almost every salary is below 25 000 MXN, with a few outliers that receive a much higher salary. I found that the Gini Coefficient of Mexico is 0.43, while the Gini Coefficient of the OECD (which Mexico is part of) is 0.32, showing that Mexico still has a long way ahead in fighting inequalities regarding wages.

Looking at the average net and gross salaries, and nominal tax, I found an odd behavior. I would expect the salaries and the tax to move in the same direction, but I found the opposite, with the exception of the first time period (from 2015 to 2016), when both the salaries and the tax decreased. But when looking at the rest of the data, I found that when the salaries increased the tax decreased, and when the salaries decreased the tax increased. I am not sure why this is but might be related to changes in tax policies and/or changes in tax brackets.

Regarding the top paying jobs, the data showed that Civil Protection Secretariat is the top one, followed by Undersecretary of Coordination of Preventive Plans and Programs, and Director of Institutional Liaison, this might be due to factors such as demand, skill requirements, and industry profitability.


# Major Obstacles

I had three major obstacles:
 - Understanding the data, and what was the meaning of each column 
 - Cleaning the data and still finding "unclean" things when I started the analysis
 - Data visualization, I wanted to do a map of the Mexico states, showing the salaries differences with different colour tones, but I wasn't able to do it.


Dataset: https://www.kaggle.com/datasets/ivansabik/mexican-federal-government-salaries
