# Ford GoBike Trip Data Analysis

## Introduction
This project analyzes the Ford GoBike trip data from February 2019 to uncover usage patterns, understand user demographics, and provide actionable insights to improve bike-sharing services. The goal is to identify trends in trip durations, popular stations, and user behavior, and to enhance service efficiency.

## Libraries Used
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For creating static, interactive, and animated visualizations.
- **seaborn**: For statistical data visualization.
- **scikit-learn**: For applying clustering algorithms and computing performance metrics.
- **time**: For measuring execution time.

## Motivation
The analysis aims to provide insights into bike-sharing patterns to help improve the service. By understanding usage patterns and user demographics, we can offer recommendations for better service management and targeted improvements.

## Files in the Repository
- **`201902-fordgobike-tripdata.csv`**: The dataset used for analysis.
- **`analysis_notebook.ipynb`**: Jupyter Notebook containing the detailed analysis, including data preprocessing, exploratory data analysis, and clustering.
- **`report.html`**: HTML version of the project report summarizing the findings and results.
- **`README.md`**: This file, providing an overview of the project.

## Summary of Results
- **Clustering Results**: Three distinct user segments were identified:
  - **Frequent Users**: Regular, short trips with frequent use of central stations.
  - **Moderate Users**: Balanced usage with moderate trip frequency.
  - **Occasional Users**: Longer trips with less frequent use of central stations.
- **Trip Duration Analysis**: Majority of trips are under 20 minutes, with some longer outliers.
- **Station Popularity**: Certain stations are significantly more popular as start or end points.

## Acknowledgments
- **Ford GoBike**: For providing the dataset used in this analysis.
- **Udacity Community**: For feedback and support throughout the project.

## Project Definition, Analysis, and Conclusion
### Project Definition
The project involves analyzing bike trip data to uncover usage patterns, user demographics, and trip durations.

### Analysis
The analysis included:
- Data preprocessing: Handling missing values, normalizing data.
- Exploratory Data Analysis (EDA): Analyzing trip durations, station popularity, and user demographics.
- Modeling: Applying KMeans and MiniBatchKMeans clustering to identify patterns.

### Conclusion
The analysis revealed distinct usage patterns among bike-sharing users. Frequent users tend to take shorter trips regularly, while occasional users have longer trips and use the service less frequently. These insights can guide targeted promotions and service improvements.

For further details, refer to the `analysis_notebook.ipynb` and `report.html` files.


Link to my blog spost: https://duylkend.github.io/duylkend1.github.io/report.html