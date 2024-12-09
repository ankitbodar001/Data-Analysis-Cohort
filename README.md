# Cohort Analysis Using Python

This project demonstrates how to perform cohort analysis to study user behavior patterns over time, leveraging Python and data visualization libraries. The analysis provides actionable insights into trends, correlations, and user retention.

## Dataset

The dataset contains information on:
- New and returning users
- Duration of user engagement on Day 1 and Day 7
- Weekly averages of user activities

## Key Features

1. **Data Preprocessing**:
   - Handled missing values and formatted date columns for time-series analysis.
   - Conducted descriptive statistical analysis.

2. **Visualizations**:
   - Trend analysis of new vs. returning users over time.
   - Duration trends for Day 1 and Day 7 user engagement.
   - Weekly averages of user metrics visualized with line plots.
   - Heatmaps to explore correlations and cohort matrices.

3. **Cohort Analysis**:
   - Grouped user data by week and calculated weekly averages.
   - Created and visualized a cohort matrix for retention insights.

## Tools and Libraries

- **Pandas**: Data manipulation and aggregation.
- **Seaborn**: Heatmaps and advanced statistical visualizations.
- **Matplotlib**: Static plots for correlation matrices.
- **Plotly**: Interactive line plots and scatter plots.

## Visualizations

- **User Trends**: Interactive line plots showcasing user growth and engagement over time.
- **Correlation Heatmap**: Displays relationships between variables like new users, returning users, and durations.
- **Cohort Matrix**: Weekly averages heatmap highlighting retention patterns.

## How to Run

1. Clone the repository:
2. Install dependencies:
   pip install pandas matplotlib seaborn plotly
3. Run the below file:
   python cohorts.ipynb

## Insights Gained
1. Identified trends in new vs. returning users, helping inform retention strategies.
2. Analyzed correlation between user engagement metrics for actionable insights.
3. Cohort analysis revealed weekly user retention and engagement trends.

