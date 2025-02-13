# Clean-and-analyze-social-media-usage-data-with-Python
Data analyst at a marketing firm specializing in social media brand promotion. Using Python to extract, clean, and analyze tweets in specific categories (health, family, food, etc.) and generate visualizations.

## **Conclusions**
This project analyzed a synthetic dataset of social media engagement, focusing on likes across different categories over time.  The process began with data generation using Pandas and random data for categories like Food, Travel, Fashion, etc., and a time series of 'Likes'.  The key challenge was working with randomly generated data that lacks inherent trends or meaningful correlations, which is different from real-world data analysis where underlying patterns might be obscured by noise and require more sophisticated methods for discovery.

My approach involved exploratory data analysis *(EDA)* using Matplotlib and Seaborn, visualizations like histograms and box plots were used to study the distribution of 'Likes', the relationship between 'Likes' and categories, and trends over time.  While real data would have likely revealed more distinct patterns, this exercise allowed me to practice the fundamentals of EDA, data cleaning, and visualization.

The code first explores the dataset using `df.head()`, `.describe()`, and `.info()` to gain an initial understanding of the structure and summary statistics.  Histograms from `sns.histplot` provide insights into the 'Likes' distribution, and box plots from `sns.boxplot` compare 'Likes' across different categories.  Time-series plots visualize the 'Likes' trend over the specified date range using `plt.plot`.

