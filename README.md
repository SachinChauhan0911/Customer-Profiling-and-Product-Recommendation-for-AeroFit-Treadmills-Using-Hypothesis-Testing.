# Project Title:
Customer Profiling and Product Recommendation for AeroFit Treadmills Using Descriptive Analytics and Hypothesis Testing

# Problem Statement:
AeroFit, a leading fitness equipment brand, aims to identify the characteristics of its target audience for each type of treadmill (KP281, KP481, and KP781). The goal is to provide better product recommendations for new customers based on customer profiles. The analysis focuses on customer demographics, product usage, and fitness levels, while investigating whether significant differences exist across treadmill products with respect to customer characteristics.

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months. The dataset has the following features:
Product Purchased: 	KP281, KP481, or KP781
Age: 	In years
Gender: 	Male/Female
Education: 	In years
MaritalStatus: 	Single or partnered
Usage: 	The average number of times the customer plans to use the treadmill each week.
Income: 	Annual income (in $)
Fitness: 	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
Miles: 	The average number of miles the customer expects to walk/run each week

# Approach:

- Exploratory Data Analysis (EDA): Analyze customer demographics (age, gender, income, education, marital status) and treadmill usage metrics (fitness level, weekly usage, expected miles).
- Descriptive Analytics: Use charts (countplots, histograms, boxplots) to visualize relationships between variables and detect trends.
- Hypothesis Testing: Apply hypothesis testing to determine if customer characteristics (e.g., age, gender, marital status) significantly impact the choice of treadmill.
- Probability Analysis: Construct two-way contingency tables, compute marginal and conditional probabilities for product purchases.
- Correlation Analysis: Assess relationships among variables using heatmaps and pairplots.
- Customer Profiling: Create customer profiles based on key characteristics to assist in product recommendations.

# Potential Impact:
The analysis provides insights into the distinct customer segments for each treadmill, helping AeroFit optimize its marketing strategies, improve customer targeting, and enhance product recommendations. Additionally, understanding how customer demographics and fitness levels influence product choice allows AeroFit to make data-driven decisions to increase sales and customer satisfaction.

# Product Sales Distribution:
![text](https://github.com/SachinChauhan0911/Customer-Profiling-and-Product-Recommendation-for-AeroFit-Treadmills-Using-Hypothesis-Testing./blob/main/images/Screenshot%202024-10-27%20at%208.08.28%20AM.png)

# Customer Profiling and Recommendation:
## Customer Profiling - 

- Probability of purchase of KP281 = 44%
- Probability of purchase of KP481 = 33%
- Probability of purchase of KP781 = 22%
  
### Customer Profile for KP281 Treadmill:
- Age of customer mainly between 18 to 35 years with few between 35 to 50 years
- Education level of customer 13 years and above
- Annual Income of customer below USD 60,000
- Weekly Usage - 2 to 4 times
- Fitness Scale - 2 to 4
- Weekly Running Mileage - 50 to 100 miles
  
### Customer Profile for KP481 Treadmill:
- Age of customer mainly between 18 to 35 years with few between 35 to 50 years
- Education level of customer 13 years and above
- Annual Income of customer between USD 40,000 to USD 80,000
- Weekly Usage - 2 to 4 times
- Fitness Scale - 2 to 4
- Weekly Running Mileage - 50 to 200 miles
  
### Customer Profile for KP781 Treadmill:
- Age of customer between 18 to 35 years
- Education level of customer 15 years and above
- Annual Income of customer USD 80,000 and above
- Weekly Usage - 4 to 7 times
- Fitness Scale - 3 to 5
- Weekly Running Mileage - 100 miles and above
  
## Recommendations:

### Marketing Campaigns for KP781:
- The KP784 model exhibits a significant sales disparity in terms of gender, with only 18% of total sales attributed to female customers. To enhance this metric, it is recommended to implement targeted strategies such as offering special promotions and trials exclusively designed for the female customers.

### Affordable Pricing and Payment Plans:
- Given the target customer's age, education level, and income, it's important to offer the KP281 and KP481 Treadmill at an affordable price point. Additionally, consider providing flexible payment plans that allow customers to spread the cost over several months. This can make the treadmill more accessible to customers with varying budgets.

### User-Friendly App Integration:
- Create a user-friendly app that syncs with the treadmill. This app could track users' weekly running mileage, provide real-time feedback on their progress, and offer personalized recommendations for workouts based on their fitness scale and goals.This can enhance the overall treadmill experience and keep users engaged.




