## From Comedy to Crime: Analyzing Movie Genres, Ratings, and Revenue Trends
This project analyzes popular movie genres, user ratings, and preferences across different age groups and genders. It also examines the relationship between movie budgets and revenue, uncovering trends and patterns in how movies perform financially. By understanding these insights, we can recommend movies that align with users' favorite genres, helping them discover films they are likely to enjoy.

## Dataset Information:

* Source: The dataset contains 626,139 rows and 23 columns, including details like UserID, MovieID, Rating, Genre, Budget, Revenue, Gender, Age, and Occupation.

Key Variables:
* Rating: User ratings for movies (1-5).
* Genre: Movie genres such as Comedy, Drama, Action, etc.
* Budget and Revenue: Financial metrics to analyze movie success.
* Demographics: User information like Gender, Age, and Occupation.

## Key Objectives:

1. Analyze Movie Ratings: Identify the highest-rated movies and genres based on user ratings.
2. Explore Genre Popularity: Determine the most popular genres and their trends over time.
3. Budget vs. Revenue Analysis: Investigate the relationship between movie budgets and revenues to identify successful and underperforming movies.
4. Demographic Preferences: Analyze how movie preferences vary by age group and gender.
5. Recommendation System: Build a system to recommend movies based on genre and user preferences.

## Methodology:

* Data Loading & Cleaning: The dataset was loaded, and missing values were handled by filling them with appropriate defaults (e.g., "Unknown" for text, 0 for numeric columns).
* Time-Based Analysis: The Timestamp column was converted to datetime format, and time-based features (year, month, day of the week) were extracted.
* Feature Engineering: A popularity score was calculated using revenue and budget, and categorical variables like Genre were analyzed.
* Exploratory Data Analysis (EDA): Visualizations such as histograms, bar charts, and line plots were used to explore trends in ratings, genres, and demographics.
* Recommendation System: A simple recommendation system was built to suggest movies based on genre and user preferences.

## Key Insights:

1. Top Genres: Comedy is the most popular genre, followed by Drama and Comedy|Romance. Users tend to rate Comedy movies slightly higher.
2. Highest-Rated Movies: Movies like Seven Samurai, Schindler's List, and Raiders of the Lost Ark have consistently high ratings (above 4.5).
3. Budget vs. Revenue: Higher-budget movies generally generate higher revenue, but there are outliers where low-budget movies perform exceptionally well.

Demographic Preferences:
1. Age Group: Users aged 18-24 prefer Comedy|Mystery|Romance|Thriller, while users aged 25-34 prefer Crime|Film-Noir.
2. Gender: Males favor Crime|Film-Noir and Sci-Fi|War, while females prefer Film-Noir|Romance|Thriller and Comedy|Drama|Western.
3. Rating Distribution: Most user ratings fall around 4.0, indicating a positive bias, with fewer ratings at the extremes (below 2.0 or above 4.5).

## Recommendations:

1. Genre-Based Marketing: Focus on promoting Comedy and Drama genres, as they are the most popular and highly rated.
2. Targeted Campaigns: Tailor marketing campaigns based on demographic preferences, such as Crime|Film-Noir for males and Film-Noir|Romance|Thriller for females.
3. Budget Optimization: Analyze successful low-budget movies to identify strategies for maximizing revenue with minimal investment.
4. Personalized Recommendations: Use the recommendation system to suggest movies based on user preferences, improving engagement and satisfaction.
5. Content Creation: Invest in producing high-quality movies in genres like Action, Drama, and Adventure, which consistently receive high ratings.

## Conclusion:

The Movie Trends and User Preferences Analysis project provides valuable insights into movie trends, user behavior, and demographic preferences. By understanding which genres and movies resonate most with audiences, businesses can optimize their marketing strategies, improve content creation, and enhance user satisfaction. The recommendation system further enables personalized movie suggestions, driving engagement and loyalty in a competitive entertainment landscape.
