# Chiptole Sales Analysis

This repository contains code and data for analyzing sales data from Chipotle, a popular fast-casual restaurant chain. The analysis aims to gain insights into Chipotle's sales performance, trends, and customer preferences using various data analysis techniques and visualization tools.


![Logo](https://media.cnn.com/api/v1/images/stellar/prod/220719153012-chipotle-file-020816.jpg?c=16x9&q=h_720,w_1280,c_fill/f_webp)


## Scenario
You are a financial data analyst at Chipotle and your manager has tasked you with analyzing the most recent sales numbers. She has provided the following set of questions she would like answered.
## Get the Data
url='https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv'
chipo = pd.read_csv(url, sep = '\t')
## Link to the Dataset
 https://raw.githubusercontent.com/justmarkham/DAT8/master/data/chipotle.tsv
 
## Challenge Questions
    1. Which was the most-ordered item?
    2. For the most-ordered item, how many items were ordered?
    3. What was the most ordered item in the choice_description column?
    4. How many items were ordered in total?
    5. Turn the item price into a float
    6. How much was the revenue for the period in the dataset?
    7. How many orders were made in the period?
    8. What is the average revenue amount per order?
    9. How many different items are sold?
## Key features
**Data Extraction :** Code for extracting sales data from Chipotle's databases or other relevant sources.

**Data Cleaning and Preprocessing:** Scripts and notebooks for cleaning and preparing the raw sales data for analysis.

**Exploratory Data Analysis:** Jupyter notebooks for exploring the sales data to uncover patterns, trends, and correlations.

**Sales Metrics Calculation:** Code for calculating key sales metrics such as average order value, items per order, and sales by product category.

**Customer Segmentation:** Techniques and models to segment Chipotle's customers based on their ordering patterns and preferences

## Tools Used
- Jupyter Notebook
- Pyhton
- Libraries : Pandas, Numpy
## Insights
- The Chicken Bowl was the most-ordered item, with a total order quantity of 761. This suggests that the Chicken Bowl is a popular choice among Chipotle customers.
- In the choice_description column, Diet Coke was the most-ordered item. This indicates that customers frequently choose Diet Coke as their preferred beverage option.
- A total of 4,972 items were ordered during the specified period, demonstrating a substantial volume of sales. This signifies a high level of customer engagement and indicates the popularity of Chipotle as a dining option.
- The item_price data type was successfully converted from object to float. This conversion allows for numerical operations and calculations to be performed on the item prices, enabling further analysis of the sales data.
- The revenue generated during the specified period in the dataset amounted to $39,237.02. This figure represents the total sales value and indicates the financial success of Chipotle during that timeframe.
- The number of orders made within the period was 1,834. This indicates a significant level of customer activity and highlights the frequency at which customers visit Chipotle to place orders.
- On average, each order generated approximately $21.39 in revenue. This average revenue per order showcases the average spending per customer and provides insights into customer purchasing patterns and behaviors.
- A diverse range of 50 different items were sold during the analyzed period. This indicates that Chipotle offers a varied and extensive product selection, catering to different customer preferences and dietary choices.


## Acknowledgements
- This project was undertaken as a challenge presented by Data in Motion (https://d-i-motion.com/) 
- I would like to express my gratitude to Data in Motion for providing the opportunity to work on this project and gain valuable insights into the analysis of sales data in the food industry.

## Support
👨‍🚀 Show your support
Give a ⭐️ if this project helped you!
## Feedback
- If you have any feedback, please reach out to me 😃(https://www.linkedin.com/in/sanjay-divate/)
- Your feedback is incredibly valuable to me, and I genuinely appreciate your time and support in helping me make this project better.

