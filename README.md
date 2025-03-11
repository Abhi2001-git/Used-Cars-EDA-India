# Used-Cars-EDA-India
This project focuses on performing an Exploratory Data Analysis (EDA) on used car sales data in India. The dataset is scraped from the Cars24 website, covering the top 9 cities in India and the top 5 most sold car brands. The analysis aims to uncover patterns and insights that can help buyers and sellers to make data-driven decisions 

## Data Collection
The data is collected by scraping the Cars24 website for used car listings in the top 9 Indian cities:
- New Delhi
- Mumbai
- Bangalore
- Hyderabad
- Ahmedabad
- Chennai
- Kolkata
- Surat
- Pune

The top 5 car brands analyzed are:
- Maruti
- Hyundai
- Honda
- Tata
- Mahindra

## Data Cleaning
The scraped data is cleaned and preprocessed to handle missing values, format columns, and ensure consistency. The following steps are performed:
- Handling missing values.
- Converting price, distance traveled, and downpayment columns to numeric format.
- Standardizing categorical variables like fuel type and transmission.

## Exploratory Data Analysis (EDA)
The EDA focuses on understanding the relationships between different variables and uncovering patterns in the data. Key areas of analysis include:
- Distribution of car prices across different cities and brands.
- Relationship between car age (model year) and price.
- Impact of distance traveled on car prices.
- Popular car models and their price ranges.
- Fuel type and transmission preferences in different cities.

## Key Insights
- **Price Distribution**: The price of used cars varies significantly across cities, with metropolitan cities like Mumbai and Bangalore having higher price ranges.
- **Car Age vs. Price**: Newer cars (2020 and above) tend to have higher prices, while older cars (2010 and below) are more affordable.
- **Distance Traveled**: Cars with lower mileage (less than 50,000 km) are priced higher compared to those with higher mileage.
- **Popular Models**: Maruti Swift and Hyundai i20 are among the most popular models in the used car market.
- **Fuel Type**: Petrol cars dominate the used car market, followed by diesel and CNG.

## Visualizations
The project includes various visualizations to better understand the data:
- **Price Distribution by City**: A boxplot showing the distribution of car prices across different cities.
- **Car Age vs. Price**: A scatter plot showing the relationship between car age and price.
- **Distance Traveled vs. Price**: A scatter plot showing how distance traveled affects car prices.
- **Fuel Type Distribution**: A bar chart showing the distribution of fuel types across different cities.

## Technologies Used
- **Python**: For data scraping, cleaning, and analysis.
- **BeautifulSoup**: For web scraping.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
