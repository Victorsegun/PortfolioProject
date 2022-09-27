# PortfolioProject
Google-Data-analytics-capstone-project
Cyclistic bike share

# Introduction
Case study: Cyclistic, a fictional bike-sharing firm, believes that increasing the number of annual members over casual riders is the key to future success. The marketing analyst teams want to know the following in order to develop a new marketing strategy aimed at converting casual riders into annual members:

How do annual members and casual riders use Cyclistic bikes differently? Why would causal riders buy Cyclistic annual memberships? How can Cyclistic use digital media to influence casual riders to become members? The director of marketing assigns me to answer question.

To come up with solutions. I will put to use the six phases of data life cycle.

# ASK
The marketing manager feels that converting casual riders to yearly riders will help the company reach its aim of faster growth in the future. To address the first question, I shall rely on data. In order to provide next steps to the organization, the current goal is to evaluate the data and discover major behavioral distinctions between casual riders and yearly members.

# Prepare
The project's data is housed on the web so I will download data. My concentration is focused on the 12 months of trip data, which starts in 2021-01and ends in 2021-12. There is no personally identifying information in the data because it has been anonymised. While this will hinder analyses that look into the personal characteristics of individual riders, such as their history or where they live, there is still enough data to establish certain patterns.

# Process
The tools I'll be using in this step Jupyter notebook. I’ll cleaning my dataset and transform it to appropriate for use.

Duplications Null data cells Misspelled words Mistyped numbers Mismatched data types Messy/Inconsistent strings Messy/Inconsistent date formats Misleading variable labels Business Logic I used Jupyter notebook to quickly merged 12 dataset into 1

Duplications:

Duplicates were found and removed.

NULLS: I used Jupyter notebook to detect null in each columns remove all rows containing NULL

Misspelled words: no problem Mistyped numbers: no problem Mismatched data types: Change the datatype of column “started_at” and “ended_at” to “datetime” using the CAST function.

Messy/Inconsistent strings: Columns “start_station_name” and “end_station_name” contain blank value. Remove rows containing it. Messy/Inconsistent date formats: no problem Misleading variable labels: Variable “member casual” and “rideable_type” is confusing, change it into “user_type” and “bike_type”.
Analyze
# ANALYZE 
I use analysis tools, mainly Jupyter Notebook and Python. Details [here](https://github.com/Victorsegun/PortfolioProject/blob/main/Cyclistic%20Bike%20Riders.ipynb)

# Act
Recommendation. Special promotion for customers who are members on weekends with discount based on rental hours. Strengthen bicycle rental points at some famous sports and gym spots to attract riders for health purpose. Reduce the number of docked_bike rentals, increase the number of electric_bikes. The number of classic_bike rentals can be slightly increased in November and December to serve loyal customers
