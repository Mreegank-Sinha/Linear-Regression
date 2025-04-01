# Linear Regression
![image](https://github.com/user-attachments/assets/6f43491c-a1f0-48bd-a165-e4e81ed39a67)


## Overview
This project analyzes customer spending behavior for an online clothing store to determine whether the company should focus on improving its mobile app or desktop website. Customers visit the store for personal styling sessions and later make purchases online through one of these platforms. The analysis examines key factors influencing spending, including length of membership, time spent on the mobile app, and time spent on the website.

Findings reveal that mobile app usage has a strong correlation with spending, while time spent on the desktop website shows little to no impact. These insights suggest that prioritizing the mobile app experience could drive higher sales, whereas the desktop website may need improvements to enhance conversion rates.

## Dataset
The dataset is taken from kaggle.
This dataset is having data of customers who buys clothes online. The store offers in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want. The company is trying to decide whether to focus their efforts on their mobile app experience or their website.
![image](https://github.com/user-attachments/assets/67ea6f4c-f790-4a5a-b478-c1fc034e9153)

## Exploratory Data Analysis
Ploted data to get insights.
Created correlation matrix to find correlation between columns.
Created Pairplot to visualise correlation.
Find strong correlation between 3 columns
![image](https://github.com/user-attachments/assets/da4b14b5-7489-4f6f-98f9-0a5eab9fd2a1)

# Creating the Linear Regression Model
The Linear Regression model was created using Scikit-learn library.
The model's performance was evaluated using metrics such as Mean absolute error and RMS.
The score was calculated whihc came out as 0.98

# Conclusion
The analysis reveals that length of membership is the strongest predictor of customer spending, followed by mobile app usage, which has a significant positive impact. In contrast, time spent on the desktop website shows little to no correlation with spending, suggesting it is less effective in driving sales. Based on these insights, the company should prioritize enhancing the mobile app experience while considering improvements to the website to boost engagement and conversions.
