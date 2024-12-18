# tiktok-data-analysis

This project involves analyzing a TikTok dataset using Python, focusing on various video metrics such as view counts, like counts, comment counts, share counts, and download counts. The goal is to perform exploratory data analysis (EDA) and visualize the distributions, outliers, and relationships between different video attributes.

Project Setup
Prerequisites
To run the analysis, you will need the following Python packages:

numpy for numerical operations
pandas for data manipulation
matplotlib for basic visualizations
seaborn for advanced visualizations
You can install the required packages using pip:
Dataset
The dataset is assumed to be in CSV format, located at /content/tiktok_dataset.csv. Make sure the file is accessible from the script or update the file path accordingly.

Data Overview:

Basic information about the dataset is displayed, including the size, shape, and data types.
Descriptive statistics (mean, median, etc.) are calculated for numeric columns.
Visualizations: Several plots are generated to explore the dataset:

Boxplots: To visualize the distribution of video-related metrics like duration, views, likes, comments, shares, and downloads.
Histograms: To show the frequency distribution of key variables.
Claim Status by Verification and Ban Status: To analyze the impact of claim status on verification and ban status.
Median View Count by Ban Status: A bar chart showing how the median view count varies by the author's ban status.
Total Views by Claim Status: A pie chart that breaks down total views based on video claim status (Claim vs Opinion).
Outlier Detection: For each video metric (views, likes, shares, comments, etc.), the script calculates the number of outliers using the interquartile range (IQR) method.

Scatterplots:

Video Views vs. Likes: A scatterplot showing the relationship between views and likes, segmented by claim status.
Opinions Only: A scatterplot showing views and likes, filtered for videos marked as "opinion".
Customizing the Analysis
If you'd like to adapt the analysis for your own dataset or extend it further, you can:

Modify the file path to the dataset if it's stored elsewhere.
Change the columns and visualizations to fit your own analysis needs.
Adjust plot styles and settings to better match your desired output
