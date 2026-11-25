# Social Media Sentiment and Engagement Analysis

# Project Overview

This project examines social media activity, sentiment distribution, and user engagement across various platforms, time periods, and countries. Through Python-based exploratory data analysis (EDA), the study investigates engagement patterns, compares platform performance, and identifies trends that provide insights into social media interactions and audience engagement.

The project uses the **Social Media Sentiments Analysis Dataset** by Kashish Parmar, sourced from [Kaggle](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data).

The cleaned dataset and findings from the analysis will serve as the foundation for developing an interactive Power BI dashboard, allowing for further exploration and visualization of social media engagement patterns.

# Objectives
- Examine the distribution of sentiments across social media posts.
- Compare engagement performance across platforms.
- Identify temporal patterns in social media engagement.
- Explore relationships between engagement metrics.
- Investigate engagement patterns across sentiments, users, and countries.
- Examine platform distribution across different countries.

# Analytical Questions

The analysis addresses the following questions:

**1. Sentiment Distribution Analysis**

- What are the most frequently recorded sentiments?

- How are the most common sentiments distributed across social media platforms?

**2. Engagement per Platform Analysis**

- Which platform has the highest number of recorded posts?

- Which platform generates the highest total engagement?

- Which platform has the highest average engagement per post?

**3. Engagement Trends Over Time**

- How does average engagement vary by hour?

- Which days of the month record the highest engagement?

- How does engagement fluctuate across different months?

- Are there identifiable periods of higher engagement?

**4. Correlation Analysis**

- What is the relationship between likes, retweets, and total engagement?

- How strongly are the engagement metrics correlated?

**5. Engagement by Sentiment**

- Which sentiments generate the highest average engagement?

- Which sentiments accumulate the highest total engagement?

- Does a higher frequency of posts correspond to higher average engagement?

**6. User Activity and Engagement Analysis**

- How many unique users are represented in the dataset?

- Which users contribute the most posts?

- How is posting activity distributed among users?

- Which users record the highest average engagement?

- How does engagement differ between users with one and two posts?

**7. Geographical Analysis**

- Which countries contribute the most recorded posts?

- Which countries have the highest total and average engagement?

- How are sentiments distributed across countries?

- Which social media platforms are most frequently represented in each country?

# Tools and Technologies

- Python – Data analysis and manipulation

- Pandas & NumPy – Data cleaning, aggregation, and statistical analysis

- Matplotlib & Seaborn – Data visualization

- Google Colab – Development environment

- Power BI – Interactive dashboard development

# Analytical Approach

The project follows an exploratory data analysis workflow:

1. Data Inspection and Cleaning – Examined dataset structure, data types, missing values, inconsistencies, and duplicate records.

2. Descriptive Analysis – Examined distributions and summarized engagement metrics.

3. Comparative Analysis – Compared engagement across platforms, sentiments, users, and countries.

4. Temporal Analysis – Investigated engagement patterns across hours, days, and months.

5. Correlation Analysis – Evaluated relationships among engagement metrics.

6. Visualization – Used charts and aggregated tables to communicate findings.

# Key Findings:

- Instagram recorded the highest total engagement among the three platforms, with 17,077 engagements and an average of 67.77 per post.

- Engagement varied across time, with July recording the highest monthly average engagement at 74.40.

- Contentment recorded the highest average engagement among the ten most frequent sentiments, at 78.11.

- Likes, retweets, and total engagement exhibited extremely strong positive correlations. However, total engagement is derived from likes and retweets, so this relationship is partly mathematical.

- The dataset contained 685 unique users, with 96.06% contributing only one post.

- The USA contributed the most posts (184), followed by the UK (140) and Canada (132).

- Brazil recorded the highest average engagement among the ten countries with the most posts, at 79.29.

- Instagram was the most frequently represented platform in the USA, UK, and Australia, while Twitter led in Canada and India.
