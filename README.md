# TikTok Dataset Analysis with Python

## Project Overview
This project involves analyzing a TikTok dataset using Python, focusing on various video metrics such as:
- **View Counts**
- **Like Counts**
- **Comment Counts**
- **Share Counts**
- **Download Counts**

The goal is to perform **Exploratory Data Analysis (EDA)** and visualize the distributions, outliers, and relationships between different video attributes.

---

## Prerequisites
To run the analysis, ensure you have the following Python packages installed:

- ![numpy](https://img.shields.io/badge/-numpy-013243?style=flat-square&logo=numpy&logoColor=white) for numerical operations
- ![pandas](https://img.shields.io/badge/-pandas-150458?style=flat-square&logo=pandas&logoColor=white) for data manipulation
- ![matplotlib](https://img.shields.io/badge/-matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white) for basic visualizations
- ![seaborn](https://img.shields.io/badge/-seaborn-4C8CBF?style=flat-square&logo=python&logoColor=white) for advanced visualizations

Install the required packages using the following command:
```bash
pip install numpy pandas matplotlib seaborn
```

---

## Dataset
The dataset is assumed to be in **CSV format**, located at:
```
/content/tiktok_dataset.csv
```
Make sure the file is accessible from the script, or update the file path accordingly.

---

## Data Overview
- Displays basic information about the dataset, including:
  - **Size**
  - **Shape**
  - **Data Types**
- Descriptive statistics (mean, median, etc.) are calculated for numeric columns.

---

## Visualizations
### The following plots are generated to explore the dataset:

#### 1. **Boxplots**
- Visualize the distribution of video-related metrics:
  - Duration
  - Views
  - Likes
  - Comments
  - Shares
  - Downloads

#### 2. **Histograms**
- Show the frequency distribution of key variables.

#### 3. **Claim Status by Verification and Ban Status**
- Analyze the impact of claim status on verification and ban status.

#### 4. **Median View Count by Ban Status**
- A bar chart showing how the median view count varies by the author's ban status.

#### 5. **Total Views by Claim Status**
- A pie chart breaking down total views based on video claim status (Claim vs. Opinion).

#### 6. **Outlier Detection**
- For each video metric (views, likes, shares, comments, etc.), the number of outliers is calculated using the **interquartile range (IQR) method**.

#### 7. **Scatterplots**
- **Video Views vs. Likes**: Displays the relationship between views and likes, segmented by claim status.
- **Opinions Only**: Visualize views and likes for videos marked as "opinion".

---

## Customizing the Analysis
To adapt the analysis for your dataset or extend it further:

- **Modify the file path** to the dataset if it's stored elsewhere.
- **Change the columns** and visualizations to fit your analysis needs.
- **Adjust plot styles** and settings to match your desired output.

---

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/sarwat-mumtaz/tiktok-eda.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tiktok-eda
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis script:
   ```bash
   python analyze_tiktok_dataset.py
   ```

---

## License
This project is licensed under the [MIT License](LICENSE).

