# Supply Chain Analysis and Late Delivery Prediction

This notebook performs an exploratory data analysis on a supply chain dataset and builds a predictive model to identify orders at risk of late delivery.

## Project Goals

The main objectives of this project are to:

- Understand the structure and characteristics of the supply chain dataset.
- Perform exploratory data analysis to identify key trends and patterns in customer behavior, product performance, geographic distribution, sales, and time-based trends.
- Build a predictive model to forecast the risk of late delivery.
- Provide insights and recommendations based on the analysis to improve supply chain efficiency and customer satisfaction.

## Dataset

The dataset used in this notebook is `DataCoSupplyChainDataset.csv`. It contains information about various aspects of a supply chain, including customer details, order information, product categories, shipping details, and delivery status.

## Analysis Performed

The notebook covers the following areas of analysis:

- **Data Loading and Preprocessing:** Loading the data, handling encoding issues, checking for missing values, converting data types, and calculating shipping delay.
- **Exploratory Data Analysis (EDA):**
    - Basic statistics of numerical columns.
    - Distribution of customer segments, order statuses, and shipping modes.
    - Distribution of delivery status.
- **Customer Analysis:**
    - Grouping data by customer and analyzing total order quantity and profit.
    - Identifying top customers by order quantity and profit.
    - Analyzing key metrics by customer segment.
- **Product Analysis:**
    - Analyzing orders, quantity, sales, and profit by product category.
    - Identifying top products by sales.
- **Geographic Analysis:**
    - Analyzing orders by region and country.
    - Visualizing geographic distribution using bar charts, choropleth maps, and scatter geo maps.
- **Sales Analysis:**
    - Analyzing sales by payment type, delivery status, and shipping mode.
- **Time-based Analysis:**
    - Analyzing monthly sales trends.
    - Analyzing sales by day of the week.
- **Predictive Modeling for Late Delivery Risk:**
    - Preparing data for modeling.
    - Splitting data into training and testing sets.
    - Building a Random Forest Classifier model.
    - Evaluating the model using accuracy, ROC-AUC score, classification report, and confusion matrix.
    - Identifying feature importances.

## Key Findings and Recommendations

Based on the analysis, several key findings and recommendations are presented in the notebook's conclusion. These include insights into customer behavior, product performance, geographic trends, and factors influencing delivery times, along with actionable recommendations to improve supply chain operations and reduce late deliveries.

## How to Run the Notebook
Google Colab Link: https://colab.research.google.com/drive/1mBqkNOUm0lb7cjWIHQafLnIQV_4m2ewc?usp=sharing
1. Upload the `DataCoSupplyChainDataset.csv` file to your Google Colab environment.
2. Run each code cell sequentially to execute the analysis and modeling steps.
3. Explore the generated plots and printed outputs for insights.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- sklearn
- warnings
