# Movies-Analysis
****Audience Preference Analysis Using Bollywood and Tamil Movie Datasets**
📌 **Project Overview**
This Power BI project dives into two separate movie industries—Bollywood (Hindi) and Tamil (Telugu)—to analyze what types of movies audiences liked most, based on ratings, genres, and upcoming trends.

🎯** **Objective****
To analyze Bollywood and Tamil movie datasets to understand which types of movies were most liked by people in the past—based on their ratings and genres—and to identify patterns that can help predict audience preferences for future movie releases.

🗂️ **Datasets Used**
Bollywood Dataset (cleaned_file4)

Fields: Genre, Movie, Rating, Year, Rating_Category, Industry

Tamil (Telugu) Dataset

Fields: Genre, Movie, Rating, Year, No. of Ratings, Runtime, Certificate, Industry

*Note: The tables were not merged, but analyzed in parallel using separate visuals.
**Techniques Used**
Excel and Power Query Editor for data cleaning and column creation
DAX measures for custom calculations
Conditional columns using SWITCH(TRUE(), ...) for rating category
Use of cards, bar, line, donut, table, tooltip visuals
Segregated analysis (not using table joins)

**Insights From the Dashboard**
🎬 1. Total Number of Movies
Bollywood has produced a significantly higher number of movies (6,693) compared to Telugu (Tamil) movies (1,376).

👉 Bollywood dominates in quantity, but quantity ≠ quality.

⭐ 2. Average Audience Ratings
Telugu movies have a higher average rating (6.31) than Bollywood (6.02).

👉 Despite producing fewer films, Tamil/Telugu movies have slightly better audience approval.

🏆 3. Highest Rated Movies
Telugu: Pichhodu scored a 9.50 — the best in the dataset.

Bollywood: Dushman has a rating of 26.50, indicating either a different scale or a special metric (possibly sum or inflated rating).

👉 Outliers like Dushman and Pichhodu can be flagged for deep qualitative review.

🎭 4. Top Performing Genres
Bollywood: Drama, Romance

Telugu: Drama, Action

👉 Drama is loved across both industries; Telugu viewers prefer more action than romance.

🧠 5. Rating Category Distribution (Audience Sentiment)
Telugu movies: Majority fall under Very Good (55.29%)

Bollywood: Majority in Good (33.5%), with fewer Excellent ratings.

👉 Telugu movies are perceived more positively overall in terms of quality.

📈 6. Year-Wise Trends (Ratings and Movie Counts)
Movie counts increasing in both industries post-2000.

Average ratings are relatively stable but Telugu movies see better consistency post-2010.

👉 Modern Telugu cinema is gaining strong momentum in both production and quality.

🎯 7. Upcoming Movie Trends (2025–2026)
Bollywood: 30+ upcoming movies already listed with release years.

Telugu: Only 1 upcoming movie (Raja), showing a lag in pre-releases or updates.

👉 Bollywood is more aggressive in planning and announcing upcoming movies.

📊 8. Donut Chart Insight – Industry-wise Average Ratings
Donut/Pie visuals show that Telugu has a slightly higher average rating share, even with fewer movies.

👉 Quality-over-quantity insight: Fewer Telugu movies but better-liked by audience.

💡 9. Top 10 High Rated Movies (Bar Chart)
Visual shows clear outliers in both industries.

Helps to benchmark what a 'high rating' means per industry (Bollywood has inflated ratings).

🗃️ 10. Audience Rating KPI Cards
Clear summary of:

Avg. Ratings

Total Movies

Individual Ratings per Year (2024, 2025)

🧾 11. 2024 Breakdown
Bollywood: 49 movies in 2024; Avg Rating: 6.00

Telugu: 5 movies in 2024; Avg Rating: 6.72

👉 Telugu movies again show better quality in fewer numbers.
