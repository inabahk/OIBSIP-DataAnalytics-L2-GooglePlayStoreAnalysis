# Google Play Store Data Analysis

## About the Project
This project analyzes Google Play Store applications to discover insights into app categories, ratings, installs, pricing, app sizes, and user review sentiment. It was completed as part of my **Data Analytics Internship at Oasis Infobyte**.

## Objectives
- Explore Google Play Store app data.
- Clean missing, duplicate, and malformed records.
- Analyze app categories and ratings.
- Investigate app size versus installs.
- Compare free and paid applications.
- Examine paid app prices and estimated revenue.
- Analyze user review sentiment.
- Present findings through visualizations and recommendations.

## Datasets
- **Source:** [Google Play Store Apps - Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Apps file:** `googleplaystore.csv`
- **Reviews file:** `googleplaystore_user_reviews.csv`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- KaggleHub
- Jupyter Notebook / Google Colab

## Project Workflow
1. Load the app and review datasets directly from Kaggle.
2. Inspect dataset structure, column types, and descriptive statistics.
3. Handle missing values, duplicate records, and malformed entries.
4. Convert installs, prices, app sizes, and review counts into numeric formats.
5. Visualize app counts by category.
6. Analyze rating distributions and average ratings by category.
7. Explore the relationship between app size and installs.
8. Compare free and paid apps.
9. Visualize the price distribution of paid apps.
10. Estimate paid-app revenue using price multiplied by reported installs.
11. Analyze positive, neutral, and negative user review sentiment.
12. Compare sentiment across app categories.
13. Create interactive visualizations.
14. Summarize findings and develop recommendations.

## Key Performance Indicators
- Number of apps by category
- Average app ratings
- Reported install counts
- App size in megabytes
- Free versus paid app comparisons
- Paid app price distribution
- Estimated paid-app revenue proxy
- User review sentiment percentages
- Correlation between app size and installs

## Key Learnings
- Cleaning and transforming real-world datasets.
- Performing exploratory data analysis.
- Creating informative data visualizations.
- Comparing app performance across categories.
- Analyzing user sentiment.
- Interpreting trends while considering data limitations.

## Limitations
- The dataset contains missing values and may contain duplicate or malformed records.
- Install counts are approximate.
- Price multiplied by installs is only a rough revenue estimate, not actual revenue or profit.
- User reviews may not represent all app users.
- Observed relationships do not establish causation.

## Conclusion
This project provided practical experience in data cleaning, exploratory data analysis, data visualization, and extracting meaningful insights from application marketplace data.

## Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics

## Author
Created as part of my data analytics internship project portfolio.
