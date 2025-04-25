# Cyclistic Bike-Share Review: Strategies for Converting Casual Users

## Project Overview

Cyclistic is a fictional bike-sharing company based in Chicago. The goal of this project was to analyze the usage patterns of annual members and casual users to identify opportunities to increase the conversion of casual users to annual memberships.

## Tools Used

* BigQuery (SQL)
* Tableau Public

## Methodology

The analysis was carried out following a structured process that included data cleansing and transformation, exploratory analysis, and visualization of the results.

### Data Cleansing and Transformation

The data was cleansed and transformed using SQL in BigQuery. The main tasks performed were:

* Checking for and handling null values ​​(queries [cite: 1, 2, 3]).
* Eliminating inconsistent data (query [cite: 4]).
* Standardizing data formats (queries [cite: 5, 6, 7]).
* Calculating trip duration (queries [cite: 10, 11]).

*Note: The detailed SQL queries used in this process can be found in the Appendix.*

### Analysis Steps

The analysis focused on comparing the behavior of annual and casual users in three main areas:

1. **Trip Volume:** Comparison of the total number of trips taken by each user type (query [cite: 8]).
2. **Trip Length:** Analysis of the average trip length for each user type (query [cite: 12]).
3. **Weekly Usage Patterns:** Comparison of the number of trips by user type throughout the week (query [cite: 13]).

### Visualization Options

The following types of visualizations were used to present the analysis results:

* **Bar Charts:** To directly compare the total number of trips and the average trip length between the two user types.
* **Line chart:** To show the trend in the number of trips by user type throughout the week and observe usage patterns.
* **Interactive dashboard:** To provide an overview of key findings and allow for data exploration.

  ## Visualizations

Below are key visualizations that summarize the analysis findings.

### Total Trips by User Type

![Bar chart of total trips by user type]

This chart shows that casual users take a higher total number of trips than annual members, suggesting greater overall service usage by this group.

### Average Trip Length by User Type

![Bar chart of average trip length by user type]

This chart reveals that annual members tend to take longer average trips compared to casual users, which could indicate more utilitarian or transit usage for this group.

### Number of Trips by User Type and Day of the Week

![Line chart of number of trips by user type and day of the week]

This chart illustrates the weekly usage patterns of both user groups. It is observed that casual users have a peak usage on weekends, suggesting recreational use, while annual members maintain more consistent usage during the week, possibly for daily commuting.

## Key Findings

(Concise summary of the most important findings from your visualizations.)

## Recommendations

(Present your top three recommendations with a brief rationale for each.)

## Link to the Project on Kaggle

You can explore the full analysis and interactive visualizations in my public Kaggle notebook: [Link to your Kaggle Notebook]

## Contact


## Key Findings

Analysis of Cyclistic's usage data revealed the following key differences in the behavior of annual and casual users:

* **Volume of Use:** Casual users account for the majority of total trips, indicating greater overall service usage.
* **Trip Length:** Annual members take longer average trips, suggesting more utilitarian or commuter usage.
* **Weekly Usage Patterns:** Casual users peak usage on weekends, suggesting recreational use, while annual members maintain more consistent usage during the week, possibly for daily commuting.

## Recommendations

Based on the analysis findings, the following three recommendations are proposed for Cyclistic, with the goal of increasing the conversion of casual users to annual members:

### Recommendation 1: Marketing Campaigns Segmented by Usage Patterns

Implement highly segmented digital marketing campaigns targeting casual users, personalizing messages and offers based on their specific weekend usage patterns and interaction with the app. Use a combination of digital marketing channels, including social media, in-app advertising, and email marketing, to effectively reach casual users on weekends. Promote discounted weekend passes that allow casual users to enjoy unlimited rides on Saturday and Sunday. Create social media content showcasing groups of friends or families using Cyclistic for weekend leisure activities, such as park rides, museum visits, or outdoor events. Offer in-app incentives, such as bonus loyalty points for weekend trips or the chance to enter exclusive sweepstakes. Establish clear metrics to measure campaign success, such as increased weekend usage by casual users, increased conversions to annual memberships, and campaign return on investment (ROI).

### Recommendation 2: "Explora Cyclistic" Loyalty Program for Long-Distance Users

Implement a loyalty program called "Explora Cyclistic" designed specifically for casual users who take long-distance trips. This program will incentivize conversion to annual memberships by offering exclusive rewards and recognizing their passion for extended rides. Data analysis reveals that casual users have a significantly longer average trip duration than annual members. This suggests that this group values ​​the experience of long, recreational rides. By creating a loyalty program focused on this preference, Cyclistic can connect emotionally with these users and offer them relevant incentives to become members. Key elements of the "Explora Cyclistic" program include a points system, membership levels, exclusive rewards, and personalized communication. Examples of specific actions include developing a dedicated section in the mobile app, organizing "Cyclistic Explorers" events, collaborating with local bike shops, and creating social media content with the hashtag #ExploraCyclistic.

### Recommendation 3: Promoting Commuter Membership

Position the annual membership as the ideal solution for daily city commuting, emphasizing its convenience, speed, and cost-effectiveness compared to other transportation options. Identify and target campaigns to specific segments of casual users who are most likely to benefit from a commuter membership, such as those who live or work near Cyclistic stations or who make frequent trips during peak hours. Offer a free membership trial during the workweek so casual users can experience the benefits of daily use. Calculate and show casual users how much they could save on commuting costs by using an annual membership instead of other alternatives. Create partnerships with companies and employers to offer membership discounts to their employees. Develop content that highlights the health and wellness benefits of using Cyclistic for daily commuting. Utilize marketing channels targeted at professionals and students, such as LinkedIn, advertising on public transportation, and collaborations with universities and workplaces.

## Link to the Project on Kaggle

You can explore the full analysis and interactive visualizations in my public Kaggle notebook: [[Link to your Kaggle Notebook](https://www.kaggle.com/code/claudiaperezsegovia/cyclistic-analysis-strategies-for-converting-casu)]

## Contact

www.linkedin.com/in/claudia-perez-segovia
