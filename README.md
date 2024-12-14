# Upliance.ai-Assignment

Insights and Observations

![Food Sales Dashboard Excel](https://github.com/user-attachments/assets/078a9ce1-6165-458f-9638-0112e9b19d6c)

1. UserDetails Dataset:
- Contains no missing values.
- User details include location, favorite meal, total orders, etc., making it suitable for demographic and behavioral analysis.
- Mean age is around 32 years, and users have an average of ~9.4 total orders.

2. CookingSessions Dataset:
- Contains detailed session information, such as duration and session ratings.
- Average session duration is ~30.31 minutes with a mean rating of ~4.52.
- No missing values are present.

3. OrderDetails Dataset:
- Missing ratings were appropriately handled by filling them with the mean rating.
- Contains information like meal type, dish name, and order status.
- Useful for understanding user ordering patterns and preferences.


Suggestions for Analysis

1.User Demographics:
- Analyze the distribution of users by location and age groups.
- Investigate the favorite meal preferences across different demographics (e.g., age or location).

2.Order Behavior:
- Examine trends in order frequency and amounts.
- Identify the most popular dishes and meal types.

3.Session and Rating Analysis:
- Explore the relationship between session duration and session ratings.
- Identify patterns in session timings and their correlation with order amounts or ratings.

4.Revenue Insights:
- Calculate the total revenue generated by each user or meal type.
- Identify high-value customers and frequently ordered dishes.

5.Missing Rating Analysis:
- Investigate why some sessions/orders might lack ratings and assess if any patterns exist in the data.

6.Time-Series Analysis:
- Use Order Date to analyze trends over time, such as peak ordering days or seasons.


Visualizations
Popular Dishes 

![popular dish](https://github.com/user-attachments/assets/e7e981d1-7c66-44d2-ae84-e0256673cd59)



User Distribution:

![order by locaton](https://github.com/user-attachments/assets/4cf3ebb2-89f2-4836-9d8c-fb2cfdc85fc9)

Meal Preferences:

Revenue by Meal Type:

Session Duration vs Rating:

Order Trends Over Time: All visualization in the the .ipynb files


