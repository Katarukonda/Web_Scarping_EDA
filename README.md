# Web_Scarping_EDA
Web Scraping and Exploratory Data Analysis of Hyderabad Housing Rentals
This project focuses on a comprehensive data science workflow, from data acquisition to insightful analysis. The goal is to collect and analyze data on residential rental properties in Hyderabad, India, to uncover key trends and characteristics of the local housing market.

1. Project Overview
The project is structured in two main phases:

Web Scraping: Data is collected directly from a real estate website to create a relevant, up-to-date dataset.

Exploratory Data Analysis (EDA): The collected data is cleaned, processed, and analyzed to answer questions about the rental market, such as how price relates to property size, location, and amenities.

2. Files in This Repository
web scraping project1 (1).ipynb: This Jupyter notebook contains the code used to scrape real-time data from a housing rental website. It uses Python libraries to parse HTML and extract key information like property price, area, number of bedrooms, and location. The scraped data is saved to a CSV file.

Web scraping project-EDA process final (1).ipynb: This notebook contains the complete data analysis. It covers data cleaning (handling duplicates and missing values), data preprocessing, and a detailed exploratory analysis with visualizations.

housing_rental_in_hyderbad.csv: This is the raw dataset collected during the web scraping process.

3. Technologies and Libraries Used
Python: The primary programming language for the project.

Pandas: Used extensively for data manipulation and analysis.

Requests & BeautifulSoup: Python libraries for web scraping and parsing HTML content.

Numpy: Used for numerical operations.

Matplotlib & Seaborn: Libraries for creating static and interactive data visualizations.

4. Key Findings and Insights
The exploratory data analysis revealed several interesting insights into the Hyderabad housing rental market:

Relationship between Price and Property Size: There is a clear correlation between the rental price and the size of the property in square feet.

BHK Distribution: The most common property type available for rent is 2 BHK (Bedrooms, Hall, Kitchen) houses, followed by 3 BHK and 1 BHK.

Security's Impact on Price: Properties with a "24x7 Security" feature tend to have a higher average rental price compared to those without this amenity, highlighting the value of security for renters.

Area-Based Pricing: The analysis showed that rental prices vary significantly by neighborhood, with some areas having a higher average rent than others.
