# Zomato_Data_Analysis

## Overview
This project analyzes a dataset of restaurants from Zomato, focusing on various factors such as online orders, table bookings, ratings, votes, and approximate costs for two people. The analysis includes data visualization and key insights drawn from the dataset.

## Steps in the Analysis

### 1. **Importing Necessary Libraries**
The required Python libraries, including Pandas, NumPy, Matplotlib, and Seaborn, were imported for data manipulation and visualization.

### 2. **Loading the Dataset**
The dataset was uploaded and loaded into a Pandas DataFrame. The structure of the dataset was explored by displaying the first few rows and summarizing the data types.

### 3. **Data Cleaning and Preprocessing**
- Converted the "rate" column to a numeric format by removing the denominator.
- Handled missing values and ensured all columns had the correct data types.
- Removed commas from the "approx_cost(for two people)" column and converted it to a numeric format.

### 4. **Exploratory Data Analysis (EDA)**

#### **Distribution of Restaurant Types**
- A count plot was used to show the distribution of different restaurant categories.
- Conclusion: Most restaurants fall under the "Dining" category.

#### **Votes by Restaurant Type**
- A grouped sum of votes was calculated for each restaurant type.
- Dining restaurants received the highest number of votes, indicating their popularity.

#### **Finding the Most Voted Restaurant**
- The restaurant with the maximum votes was identified.
- "Empire Restaurant" had the highest votes.

#### **Online Order Analysis**
- The proportion of restaurants that accept online orders was visualized.
- Conclusion: Most restaurants do not accept online orders.

#### **Ratings Distribution**
- A histogram was used to analyze restaurant ratings.
- Conclusion: Most restaurants have ratings between 3.5 and 4.

#### **Cost Analysis**
- The distribution of the approximate cost for two people was analyzed.
- Conclusion: The most common cost for two people is 300 rupees.

#### **Comparison of Online and Offline Orders' Ratings**
- A box plot compared the ratings of restaurants that accept online orders vs. those that do not.
- Conclusion: Restaurants with online orders tend to receive higher ratings.

#### **Heatmap of Online Orders by Restaurant Type**
- A heatmap showed the relationship between online orders and restaurant type.
- Conclusion: Dining restaurants primarily operate offline, whereas cafes receive more online orders.

#### **Identifying the Most Expensive and Cheapest Restaurants**
- The dataset was sorted by cost to determine the top 10 most expensive and cheapest restaurants.
- "Ayda Persian Kitchen" was the most expensive restaurant, while several small eateries had the lowest costs.

#### **Most Popular Restaurants by Votes**
- A bar plot visualized the top 10 restaurants with the most votes.
- Conclusion: Certain restaurants received significantly more public engagement.

#### **Impact of Table Booking on Ratings**
- A box plot analyzed whether booking a table influenced ratings.
- Conclusion: Restaurants that allow table booking generally receive higher ratings.

## Key Insights
- **Dining restaurants dominate the market**, with the highest number of votes.
- **Online orders correlate with higher ratings**, indicating a preference for online ordering.
- **The most common cost for two people is 300 rupees**, making budget-friendly options popular.
- **Higher-end restaurants tend to receive more votes**, showing increased customer interest in premium dining experiences.
- **Restaurants allowing table bookings tend to have better ratings**, possibly due to enhanced service and experience.

## Future Improvements
- Incorporate more features for deeper insights, such as cuisine type and location.
- Use machine learning to predict restaurant success based on features like cost, votes, and ratings.
- Explore customer sentiment analysis based on reviews to gain qualitative insights.

## Conclusion
This analysis provides valuable insights into restaurant trends, customer preferences, and factors influencing restaurant ratings. Future work can build on this to further refine business strategies and customer experience.

---

### Author: Pratham Nagar   
### Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn

