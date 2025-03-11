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
The exploratory analysis reveals a nuanced used car market where mileage, price, and ownership play key roles in shaping buyer and seller behaviors:
- **Mileage & Price Distribution:**  
  - Most cars are listed with relatively low mileage (75% under 80,000 km) and priced below ₹7,43,000, indicating a preference for lower usage vehicles.  
  - Both price and downpayment distributions are significantly right-skewed, with only a few high-priced or high downpayment listings.
- **Brand & Ownership Trends:**  
  - Brands like **Honda, Hyundai, and Maruti** dominate the higher mileage segment, suggesting they are often sold after prolonged use, while **Mahindra and Tata** appear predominantly among higher-priced and newer listings.  
  - First-owner cars are the most common, and they command a premium—priced 15-20% higher than second-owner and 40-50% higher than third-owner vehicles.
- **Fuel & Transmission Characteristics:**  
  - **Petrol cars** are the most frequently listed, with diesel and CNG following; however, diesel cars tend to be pricier and, along with CNG cars, cover more distance than their petrol counterparts.  
  - Manual transmission cars significantly outnumber automatics (approximately 6:1), yet automatic cars are priced higher, likely reflecting higher initial purchase prices or additional features.
- **Regional Variations:**  
  - Price levels vary notably by location: Chennai leads with the highest mean prices (above ₹6 lakhs), while cities like Kolkata and Surat offer more budget-friendly options (below ₹5 lakhs).

## Recommendations for buyers
- **Mileage vs. Price:** Focus on first-owner, low-mileage vehicles if resale value and condition are priorities, even if these come at a premium.
- **Transmission Choice:** While manual cars dominate, consider automatic vehicles if you value added convenience despite a higher price.
- **Fuel Type Considerations:** Evaluate the long-term benefits of petrol vs. diesel vs. CNG. CNG cars might offer cost savings, but diesel vehicles may have higher mileage—ensure to check maintenance histories.
- **Location Leverage:** Explore listings in regions like Kolkata and Surat for potentially lower prices, but balance this with local service and resale considerations.
- **Brand & Ownership History:** Recognize that brands like Mahindra and Tata tend to be newer and pricier, whereas high-mileage options from Honda, Hyundai, and Maruti might offer value for budget-conscious buyers.

## Recommendations for sellers
- **Emphasize Low Mileage:** Listing cars with lower mileage is advantageous since buyers show a strong preference for less-used vehicles.
- **Ownership Premium:** Highlight first-owner status to justify higher pricing, and be mindful of the premium differences between first, second, and third-owner vehicles.
- **Brand Positioning:**  
  - For brands like Mahindra and Tata, emphasize the newer model years and premium features.  
  - For Honda, Hyundai, and Maruti, focus on reliability and extensive usage history as a testament to durability.
- **Fuel and Transmission:** Consider the market dynamics—manual cars are abundant, so competitive pricing can help; if selling an automatic, underscore any added technological or comfort benefits.
- **Regional Strategy:** Adjust pricing strategies based on location-specific market trends. For instance, premium pricing in Chennai can be justified, while competitive pricing might be necessary in markets like Surat or Kolkata.

## Technologies Used
- **Python**: For data scraping, cleaning, and analysis.
- **BeautifulSoup**: For web scraping.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
