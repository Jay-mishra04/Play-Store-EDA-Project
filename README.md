# Google Play Store Dataset Analysis

## Introduction

The Google Play Store is a prominent platform for distributing and accessing Android applications (apps). As part of this data analysis project, we will explore and analyze a Google Play Store dataset to gain insights into app categories, ratings, reviews, sizes, installs, pricing, content ratings, genres, and more. This analysis aims to provide a comprehensive understanding of the app ecosystem on the Google Play Store and identify patterns, trends, and correlations that can assist developers, marketers, and decision-makers in making informed choices and optimizing their strategies.

## Objectives

- **Explore App Categories**: Analyze the distribution of apps across categories, identify popular categories, and examine relationships between categories and ratings, reviews, or installs.
- **Assess App Ratings**: Investigate the distribution of ratings, identify highly-rated and poorly-rated apps, and explore correlations between ratings and factors like app installs.
- **Analyze App Installs**: Examine the distribution of install counts, identify the most installed apps, and discover patterns between installs and variables like category, rating, or price.
- **Evaluate Reviews and Sentiment**: Study app reviews and sentiment, identify common user sentiments, and explore connections between sentiment, ratings, and other factors.
- **Explore App Pricing**: Analyze the distribution of app prices, identify free and paid apps, and assess the relationship between price and variables like category or rating.
- **Investigate Content Ratings and Genres**: Explore the distribution of content ratings, identify popular age groups, and analyze the variety of genres available. Examine relationships between content rating, genres, and other variables.

## Problem Statement

The Google Play Store is a thriving platform for Android apps, offering users a wide range of options and developers a massive audience. However, navigating the dynamic app ecosystem and making data-driven decisions can be challenging. The problem at hand is the lack of comprehensive insights into the Google Play Store dataset and the absence of a clear understanding of the factors influencing app performance, user engagement, and market dynamics. This leads to suboptimal app strategies, missed growth opportunities, and potential user dissatisfaction.

## Business Objectives

- **Understand Market Trends**: Gain insights into the app categories that are currently popular on the Google Play Store. Identify emerging trends and high-demand categories.
- **Improve App Ratings**: Analyze app ratings and reviews to identify areas for improvement. Identify factors that positively or negatively impact app ratings and use this information to enhance app features, functionality, and user experience.
- **Increase App Installs**: Explore the relationship between app installs and various factors such as category, content rating, or price. Use these insights to develop strategies that can increase app downloads and user engagement.
- **Enhance User Satisfaction**: Analyze app sentiment and review feedback to understand user sentiments and pain points. Use this information to address user concerns, improve app performance, and enhance user satisfaction.

## Dataset Overview

- **Rows**: 1463
- **Key Columns**:
  - **App**: The name of the application.
  - **Category**: The category or genre to which the app belongs.
  - **Rating**: The user rating of the app, typically on a scale of 1 to 5.
  - **Reviews**: The number of user reviews the app has received.
  - **Size**: The size of the app installation package.
  - **Installs**: The approximate number of times the app has been installed.
  - **Type**: Whether the app is free or paid.
  - **Price**: The price of the app if it is not free.
  - **Content Rating**: The target audience or age group for which the app is suitable.
  - **Genres**: The specific genres or sub-categories the app falls into.
  - **Last Updated**: The date when the app was last updated.

## Data Manipulations

- **Duplicates**: Removed duplicate values and duplicate app names in different rows.
- **Data Type Conversions**: Converted Reviews column from object to integer and Install column from comma-separated strings to numeric values.
- **Price Formatting**: Removed dollar signs from the Price column.
- **Date Formatting**: Standardized the Last Updated column date format and extracted the year into a new column called year_updated.

## Insights

- **Ratings**: Mean ratings for all apps is 4.1, indicating a general preference for apps on the Play Store.
- **App Categories**: 
  - Most apps belong to the **Family** category (1831 apps).
  - **Games** category has the highest number of installs and reviews.
  - Categories like **Parenting**, **Comics**, and **Beauty** have the least number of apps and installs.
- **Reviews and Sentiments**:
  - Most apps have positive sentiments.
  - **Games** have the highest number of both positive and negative sentiments.
  - Apps with higher sentiment polarity are generally liked by users.

## Charts and Analysis

- **Count Plot**: Used to count the number of apps in each category and visualize category distribution.
- **Bar Plot**: Analyzed the number of installs, reviews, and price distribution across different app categories.
- **Box Plot**: Visualized the median ratings of apps in different categories.
- **Line Graph**: Examined the relationship between ratings and the year of last update.
- **Heat Map**: Showed correlations between various columns such as reviews, installs, ratings, and price.
- **Scatter Plot**: Analyzed the relationship between sentiment polarity and subjectivity.
- **Pair Plot**: Displayed relationships between multiple numerical variables.

## Solution to Business Objectives

1. **For Gaming Companies**: Develop free games accessible to everyone. Consider low-priced paid versions to attract more users.
2. **For Lifestyle Companies**: Develop paid apps as people are willing to pay for apps in this category.
3. **General Recommendation**: Focus on regular updates, as they positively impact ratings and user satisfaction. Free apps generally attract more users, but paid apps in specific categories like Lifestyle and Finance can also be successful.

## Conclusion

The Google Play Store dataset analysis reveals that while the majority of apps are free, games are the most popular and frequently installed category. Regular updates and positive reviews significantly impact app success. Businesses should leverage these insights to enhance app development and marketing strategies.


This project demonstrates the effective application of data exploration, cleaning, and visualization techniques to gain valuable insights into the Google Play Store ecosystem. By analyzing app ratings, installs, reviews, and other key metrics, we provide actionable recommendations for app developers, marketers, and decision-makers to enhance their strategies and improve user engagement.

Feel free to explore the code and visualizations provided in this repository to gain a deeper understanding of the analysis and replicate the results. If you have any questions or suggestions, please don't hesitate to reach out via [email](jabcd.1997@gmail.com).

Happy analyzing!
