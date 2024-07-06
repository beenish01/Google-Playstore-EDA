# Google-Playstore-EDA
Problem Statement
The objective of this project is to analyze the Google Playstore dataset to identify key factors that drive app popularity and user engagement. By examining user ratings, download counts, category successes, and monetization strategies, the goal is to uncover insights that app developers and marketers can leverage to enhance app visibility, etc.


Data Cleaning
Drop Missing Values: Rows with missing Rating values were removed.
Data Type Conversion:
Installs was converted to integer after removing non-numeric characters.
Price was converted to float after removing the dollar sign.
Reviews was converted to integer.
Date Extraction: Extracted Month, Day, and Year from the Last Updated column.


Univariate Analysis and Visualizations
Distribution of Ratings:

Histogram showing most apps have ratings between 3.5 and 4.5.
Average Rating by Category:

Bar plot indicating higher average ratings for categories like 'BOOKS_AND_REFERENCE' and 'EDUCATION'.
Number of Apps by Category:

Bar plot revealing 'FAMILY' and 'GAME' categories have the highest number of apps.
Rating vs. Number of Reviews:

Scatter plot showing apps with higher ratings generally receive more reviews.
Installs Distribution:

Histogram indicating most apps have between 10,000 and 100,000 installs.
Average Installs by Category:

Bar plot showing categories like 'COMMUNICATION' and 'VIDEO_PLAYERS' have the highest average installs.
Free vs. Paid Apps: Rating Comparison:


Correlation Analysis:

Pearson correlation tests between numerical columns identified significant correlations:
Rating and Reviews: Positive correlation, indicating higher ratings are associated with more reviews.
Rating and Installs: Positive correlation, suggesting higher-rated apps have more installs.
Chi-Squared Tests:

Chi-squared tests assessed associations between categorical variables:
Category and Type (Free vs. Paid): Significant association, indicating certain categories have a higher proportion of free or paid apps.
Content Rating and Type: Significant association, showing different content ratings have different distributions of free and paid apps.
ANOVA and Tukey's HSD Tests:

ANOVA tests compared mean ratings across categories and content ratings:
Ratings across Categories: Significant differences detected. Tukey's HSD test revealed specific categories with differing mean ratings.
Ratings across Content Ratings: Significant differences detected. Tukey's HSD test highlighted specific content ratings with differing mean ratings.
Key Insights
Ratings and User Engagement: Higher ratings are positively correlated with the number of reviews and installs, indicating that user satisfaction influences app engagement.
Category Impact: Certain categories, such as 'BOOKS_AND_REFERENCE' and 'EDUCATION', tend to have higher average ratings, while 'FAMILY' and 'GAME' categories have the most apps.

Free vs. Paid Apps: Paid apps generally receive slightly higher ratings, suggesting that users may have higher expectations or satisfaction with paid apps.
Content Rating Distribution: 'Everyone' is the most common content rating, highlighting a focus on family-friendly apps.
Update Trends: There has been a noticeable increase in the number of app updates over recent years, reflecting the importance of maintaining and improving apps to retain user interest.
