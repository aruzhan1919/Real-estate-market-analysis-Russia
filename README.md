**Real Estate Market Analysis in Russia**
This project presents an exploratory data analysis (EDA) of real estate listings in Russia. The analysis is conducted using Python and provides insights into pricing patterns, listing characteristics, and potential factors affecting the real estate market.

**Overview**
The project involves the following steps:
1. Loading and inspecting the dataset
2. Data cleaning and preprocessing
3. Exploratory data analysis using visualizations
4. Identifying patterns and correlations
5. Drawing conclusions based on statistical summaries

**Dataset**
The dataset includes information about apartment listings such as: 
- Listing date
- Floor number and total floors
- Ceiling height
- Apartment area (total, living, kitchen)
- Distance from city center
- Time on market (exposure time)
- Listing price

**Technologies Used**
pandas, numpy, seaborn, matplotlib, plotly, datetime

**Process and Methods**
Data Preprocessing
Converted date columns to datetime format
Removed duplicates
Filled missing values using medians and group-based means
Exploratory Analysis
Distribution plots for features such as ceiling height, floor number, price
Bar charts to understand how many listings are on each floor type
Correlation matrix between numerical variables
Time-series analysis to observe monthly and yearly trends
Visualization Techniques
Bar charts and histograms for categorical distributions
Box plots to detect outliers in price
Line plots for temporal trends
Interactive charts with plotly for better visual inspection

**Key Observations**
- Properties closer to the city center are generally more expensive
- Ceiling height and area are positively correlated with listing price
- Listings on the last floor tend to have different exposure characteristics
- Most listings are added in spring and early summer months

**How to Run**
Clone the repository
Open the notebook in Jupyter or any compatible editor
Install required libraries:
pip install pandas numpy matplotlib seaborn plotly
Run the notebook cells sequentially to reproduce the analysis
