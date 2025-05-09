# 🛒 Shopping Habits of Instacart Customers

Welcome to the Instacart Exploratory Data Analysis (EDA) project! This project dives into customer behavior on the Instacart grocery delievery platform by analyzing ahopping patterns using real-world anonymized data. 

## 📌 Table of Contents
  - Project Description
  - Dataset
  - Installation & Setup
  - How to Use
  - Features
  - Insights & Visualizations\
  - Credits
  - License

## 📖 Project Description

This project is developed as part of a data analysis siprint and focuses on cleaning, analyzing, and visualizing a grocery shopping dataset. The goal is to uncover patterns in customer behavior, such as: 
  - What time of day do people shop for groceries?
  - What day of the week do people shop for groceries?
  - How long do people wait until placing another order?
  - Is there a difference in orders placed each hour of day on Wednesdays and Saturdays?
  - What are the top 20 popular products?
  - How many items do people typically buy in one order?
  - What are the top 20 items that are reordered most frequently?
  - What are the top 20 items that people put in their carts first?
Through this analysis, we gain insight into user preferences and habits that could be useful for product recommendations, inventory management, and marketing.

## 🗃️ Dataset
The project uses a modified version of the Instacart 2017 Kaggle dataset. It consists of five CSV files:
  - instacart_orders.csv - Orders data per customer.
  - products.csv - Product details.
  - order_products.csv - Mapping between orders and products.
  - aisles.csv - Aisle categories. 
  - departments.csv - Department categories.
  📌 Note: The dataset has been intentionally modified to include missing and duplicate values for the purpose of testing data cleaning skills.

## 🛠 Installation & Setup
To run this project locally: 
  1. Clone the repository:
       `git clone https://github.com/your-username/instacart-eda.git`
       `cd instacart-eda`
  3. Install required packages:
       `pip install pandas matplotlib seaborn juypter`
  4. Start the Jupyter notebook:
       `jupyter notebook`

## ▶️ How to Use
  1. Open the notebook and run the cells in order.
  2. The anaylsis includes data loading, cleaning, exploration, and visualiztion.
  3. Each anaylsis step includes explanations in markdown cells frr clarity.
  4. Visualizations use `matplotlib` and `seaborn` to communicate key insights. 

## ✨ Features
  - Cleaned and prepared five interlinked datasets
  - Visual anaylsis of:
     - Shopping times (hour, day of the week)
     - Order patterns
     - Wait time between orders
  - Top 20 reordered products
  - Distribution of cart size
  - Clean and readable code structure with markdown documentation

## 📊 Insights & Visualizations
### 📊 Insights
  - Shopping Time Patterns:
    Most Instacart customers place their orders between 7 AM and 8 PM, indicating a strong     preference for daytime grocery shopping. Order volume declines significantly after 8 PM.

  - Weekly Shopping Trends:
    While customers order throughout the week, Sunday and Monday see the highest number of orders. This suggests a common pattern of restocking groceries at the beginning of the week.

  - Order Frequency:
    Many customers tend to place orders weekly or monthly, implying planned, periodic grocery shopping habits, often timed around the weekends.

  - Product Preferences:
    There is a strong customer preference for organic food items, especially fruits and vegetables. These items dominate:
    -  The most popular products
    -  The most reordered items
    -  The first items added to the cart

  - Notable Exception:
Among the top 20 items customers add to their carts first, Sodas stand out as a popular non-organic item, suggesting a niche demand for sweetened beverages.

### 📈 Visualizations (Highlights)
  - Hourly Order Distribution
  A bar chart showing order volume by hour reveals a peak from 7 AM to 8 PM, with a gradual decline thereafter.
  
  - Orders by Day of the Week
  A line graph illustrates that Sunday and Monday receive the highest number of orders, confirming they are the most popular shopping days.
  
  - Days Since Prior Order
  A histogram displays a concentration around 7 and 30 days, showing that many customers reorder weekly or monthly.
  
  - Top 20 Most Popular Items
  A horizontal bar chart showcasing top items by frequency — the majority are organic fruits and vegetables.
  
  - Top 20 Reordered Items
  This chart mirrors the popular items, reinforcing the strong customer loyalty to organic groceries.
  
  - First Carted Items
  A stacked bar chart reveals that items like Bananas, Organic Strawberries, and Organic Baby Spinach are often the first items added to the cart. Sodas is the only standout artificial item in this list.

## 🤝 Credits
This project was created as part of the TripleTen Data Science program.
Special thanks to:
  - Instacart for the original dataset
  - Kaggle for hosting the competition
  - TripleTen instructors and peers for ongoing support and feedback
