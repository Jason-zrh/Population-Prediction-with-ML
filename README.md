# Population-Prediction-with-ML

# 1. Introduction and Reading Assignment 
In this project, we will look at the human population statistics collected by the various national governments 
and build a machine learning model to make population predictions. 

An Introduction to Population Growth 
By: Sunny B. Snider (College of Agriculture, California State University, Chico) & Jacob N.Brimlow (College of Agriculture, California State University, Chico) 
https://www.nature.com/scitable/knowledge/library/an-introduction-to-population-growth-84225544/



# 2. Data Source: Singapore Department of Statistics (SingStat) 
Let’s start with looking at the population statistics of Singapore.
Download Singapore population data from 1950 to 2022 from: https://www.singstat.gov.sg/
a) Graph the total population vs year.

b) Use linear regression to build an estimator of the total population of Singapore in the future. Use the data for years 2019 and earlier as training data. 

c) Performance metrics: 
i. What are the slope and y-intercept of the best fit line? Plot the best fit line over the empirical data. 
ii. What is the R2 coefficient and mean squared error (MSE) of the estimator on the training data? 
iii. Use years greater than 2020 as test data and predict the population for those years. 
iv. What is the MSE of the estimator on the test data?

d) What is your estimate of Singapore’s population in 2023, 2030 and 2050? Do you think these estimates 
are reasonable? Explain your answer. 

e) What pattern do you expect for human population growth in Singapore? 

f) How could you improve your estimates of the future population?

# 3. Data Source: World Bank
Repeat Question 2 for your own country’s population from 1950 to 2022. You may download the data from 
the World Bank: https://data.worldbank.org/indicator/SP.POP.TOTL


# ============ Experiment Optimization =============
# Comparison of various model data fitting
<img width="1368" height="1211" alt="image" src="https://github.com/user-attachments/assets/675909cd-a160-4b00-97a0-7739992f3882" />
<img width="1000" height="560" alt="93b292a33d41dafbd7d53de5e49c9ab5" src="https://github.com/user-attachments/assets/37f987c4-af92-46ca-8557-1640a19485a4" />
<img width="1000" height="560" alt="a59ae28659e1ddd95dacb8569838a815" src="https://github.com/user-attachments/assets/c89bd2e5-2350-4012-96c3-ecc64db5f7ff" />
<img width="1000" height="560" alt="6b71f0727a7c0367ff3a21fbe0dd115b" src="https://github.com/user-attachments/assets/85548497-25cc-467f-a7af-4b47bbbdb371" />



