# Android App Market Analysis

This repository contains a Jupyter notebook that conducts a comprehensive analysis of the Android app market by examining thousands of apps available in the Google Play Store. The analysis utilizes a dataset of app and review data scraped from the Google Play Store to derive insights about app ratings, sizes, installs, and more.

## Project Overview

The notebook explores various aspects of the Android app market, focusing on:

1. **Data Cleaning and Preparation**: Removing unused columns, handling missing values, and ensuring the dataset is ready for analysis.
2. **App Ratings**: Identifying the highest-rated apps and the implications of using ratings as a quality metric.
3. **App Sizes**: Analyzing the sizes of apps and discussing potential size limits imposed by the Google Play Store.
4. **Review Counts**: Investigating the apps with the most reviews and checking for paid apps among the top entries.
5. **Data Visualization**: Using Plotly to create pie charts, bar charts, and box plots to visualize categorical data, competition among genres, and revenue estimates for paid apps.
6. **Revenue Estimates**: Estimating revenue for paid apps based on installs and price.

## Dataset

**Data Source:** 
The dataset used in this analysis was scraped from the Google Play Store by Lavanya Gupta in 2018. The original files can be found [here](https://www.kaggle.com/lava18/google-play-store-apps).

## Key Features

- **Data Cleaning**: Steps taken to clean and preprocess the data, including removing NaN values and duplicates.
- **Visualizations**: Interactive visualizations created using Plotly to analyze trends and distributions.
- **Market Insights**: Insights on the app market based on categories, ratings, prices, and competition.

## Dependencies

To run the notebook, ensure you have the following libraries installed:

- Python 3
- Pandas
- Plotly

You can install the required dependencies using:

```bash
pip install pandas plotly
```

## Usage

1.Clone the repository:

```bash
git clone https://github.com/yourusername/android-app-market-analysis.git
```
2.Navigate to the repository directory:

```bash
cd android-app-market-analysis
```

3. Open the Jupyter notebook:

```bash
jupyter notebook Android_App_Market_Analysis.ipynb
```

## Insights

- Highest Rated Apps: Ratings alone may not accurately represent an app's quality due to potential bias.
- Size Limitations: The analysis of app sizes raises questions about limitations imposed by the Google Play Store.
- Revenue Potential: Insights into the revenue estimates for paid apps indicate that while some categories can yield significant earnings, others may not cover development costs.

  
## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! If you'd like to suggest improvements or additions, please feel free to submit a pull request.
