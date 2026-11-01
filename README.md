# Social Media Engagement Analytics Using Python

## Project Overview

This project focuses on analysing social media engagement data using Python. It explores user interactions, content performance, audience behaviour, and engagement patterns through data cleaning, exploratory data analysis, statistical analysis, and data visualization.

The project uses Python libraries to transform raw data into meaningful insights that help understand social media engagement.

## Dataset Overview

- **Dataset:** `social_media_engagement_5000.csv`
- **Total Records:** 5,000
- **Original Columns:** 19
- **Final Columns:** 20 (including the additional `hashtag_count` feature)

The dataset includes user information, post details, likes, comments, shares, watch time, impressions, follower count, device type, sentiment, hashtags, and engagement rate.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Project Workflow

### 1. Data Import and Setup
- Imported the dataset using Pandas.
- Inspected dataset structure, columns, and data types.
- Converted the posting date column into datetime format.
- Performed basic NumPy operations.

### 2. Data Cleaning and Preprocessing
- Identified and handled missing values.
- Used median and mode imputation.
- Checked for duplicate records.
- Standardized categorical text values.
- Corrected data types.
- Cleaned hashtag values.
- Created a `hashtag_count` feature.

### 3. Exploratory Data Analysis
- Examined dataset structure and summary statistics.
- Analysed categorical distributions.
- Explored numerical features and correlations.
- Compared engagement metrics using groupby operations.

### 4. Data Wrangling
- Created an `engagement_score` feature.
- Applied logarithmic transformations using `log1p()`.
- Performed merge, concatenate, and join operations.
- Generated grouped summaries by post type, country, and sentiment.

### 5. Statistical Analysis
Calculated:
- Mean, median, and mode
- Standard deviation and variance
- Percentiles
- Skewness and kurtosis

### 6. Data Visualization

**Matplotlib**
- Scatter plot
- Line chart
- Bar chart
- Pie chart
- Histogram
- Box plot

**Seaborn**
- Count plot
- Bar plot
- Violin plot
- Pair plot
- Correlation heatmap
- Swarm plot

**Plotly**
- Interactive line chart
- Interactive bar chart
- Interactive scatter plot
- Interactive bubble chart

### 7. Final Insights

The analysis explored:
- Best-performing content category
- Country with the highest average engagement
- Engagement across different age groups
- Verified and non-verified account performance
- Posting-time data limitations
- Device-wise watch time comparison
- Engagement patterns across sentiment groups

## Key Findings

- Food recorded the highest average engagement rate among content categories.
- Brazil recorded the highest average engagement rate among countries.
- The 41–50 age group recorded the highest average engagement rate.
- Verified accounts showed a higher average engagement rate than non-verified accounts.
- Mobile users recorded the highest average watch time.
- Negative-sentiment posts showed a higher average engagement rate than neutral posts.
- Actual best posting time could not be identified because the dataset contains dates without usable time-of-day information.

## Project Outcome

This project provided practical experience in Python-based data analysis, including data cleaning, preprocessing, data manipulation, statistical analysis, exploratory data analysis, and visualization.

It demonstrates how Python can be used to explore social media engagement data and communicate meaningful findings.

## Repository Contents

- `Social Media Engagement Analytics.ipynb` – Jupyter Notebook containing the complete Python analysis, code, and visualizations.
- `Social Media Engagement Analytics Report.pdf` – PDF report presenting the project workflow, analysis, and findings.
- `Data Analysis.docx` – Assignment instructions and requirements.
- `social_media_engagement_5000.csv` – Dataset used for the analysis.
- `README.md` – Project overview, workflow, tools, and key findings.
  
## Author

**Akshaya S**  
B.Sc. Computer Science Graduate  
Aspiring Data Analyst
