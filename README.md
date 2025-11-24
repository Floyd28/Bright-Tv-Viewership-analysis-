# Bright-Tv-Viewership-analysis-

# BrightTV Viewership Analytics Case Study

# 1. Executive Summary
The objective of this case study was to analyze user profiles and viewer transactions for BrightTV to assist the Customer Value Management (CVM) team in growing the subscription base. By analyzing Q1 2016 viewership data, we identified that Sports and Kids' content are the primary drivers of consumption. The analysis highlights that consumption is heavily influenced by live sporting events and weekend viewing habits. Recommendations focus on upselling sports packages, utilizing archive content for low-consumption weekdays, and fixing technical transmission breaks to reduce churn.

# 2. Methodology & Approach
The analysis was conducted using a raw dataset of viewer transactions.
1.  Data Cleaning
    - Adjusted `RecordDate2 from UTC to South Africa Standard Time (SAST) by adding 2 hours.
    - Converted Duration2 (HH:MM:SS) into total minutes for quantitative analysis.
    - Filtered out Break in transmission records for content analysis but retained them for technical stability analysis.
      
2.  Exploratory Data Analysis (EDA)
    - Segmented users by high, medium, and low consumption.
    - Analyzed channel popularity by frequency and duration.
    - Mapped consumption trends over days of the week and time of day.
  
    
3.  Insight Generation: Correlated specific content types (Cricket, Cartoons) with user session lengths to determine sticky content.

# 3. Key Insights
* Sports Dominance: The ICC Cricket World Cup 2011 (likely re-runs/highlights given the 2016 date) and Supersport Live Events generate the longest session durations, indicating a high-engagement user base for sports.
  
* The Babysitter Effect, Cartoon Network and Boomerang have the highest frequency of logins, suggesting a large segment of subscribers are families using the service for children.
*   Churn Risks: A noticeable amount of Break in transmission records suggests technical instability which threatens user retention.
*   Weekday Slump Consumption drops mid-week when live sports are less frequent.

# 4. Tools Used
*   **SQL:** For data cleaning, time-zone conversion, and data aggregation.
*   **Microsoft Excel:** For Pivot Tables, trend graphing, and deeper statistical analysis.
*   **PowerPoint/Canva:** For the final executive presentation.
