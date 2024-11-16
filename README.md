![MasterHead]([https://cdn.dribbble.com/users/1197989/screenshots/5585685/media/139eef797b4034c31cd8189a717c2022.gif])

# Swiggy Analysis Project
Swiggy Anaysis (bangalore) based on Data Scrapped from website.

---

## Aim of the project 🎯:

The aim of this project is to empower aspiring entrepreneurs in the food industry by leveraging data analysis techniques on Swiggy's extensive dataset. By analyzing Swiggy's data, the project seeks to provide valuable insights and actionable recommendations for individuals looking to start their own restaurant business. This endeavor aims to democratize information, allowing entrepreneurs to make informed decisions, optimize their strategies, and increase their chances of success in the competitive restaurant market.

---

## Project Description 📃:
In this project, we delve into the world of food delivery with Swiggy, one of the leading platforms in the industry. Our project is geared towards extracting valuable insights from Swiggy's vast dataset, employing a multi-faceted approach that combines the power of Python libraries, Excel, and Power Query.

Project Phases:

- Data Extraction using Python Libraries:
  - Utilized Python libraries such as Pandas and Requests to extract raw data from Swiggy's servers.
  - Implemented web scraping techniques to collect real-time data on restaurant listings, customer reviews, and menu items, ensuring a comprehensive dataset for analysis.

- Data Cleaning and Transformation using Power Query:
  - Imported the extracted data into Excel and use Power Query to clean, transform, and structure the dataset.
  - Addressed missing values, standardize formats, and remove duplicates to ensure data accuracy and consistency.
  - Leveraged Power Query's intuitive interface to streamline the cleaning process and prepare the data for in-depth analysis.

- Data Analytics using Excel:
  - Employed advanced Excel functions and statistical analysis tools to derive meaningful insights from the cleaned dataset.
  - Performed descriptive analytics to identify popular cuisines, customer preferences, peak ordering hours, and regional trends.
  - Utilized pivot tables and charts to visualize data patterns, aiding in the identification of key market trends and opportunities.

---

# _Steps involved in process:_

## 1. Web Scrapping ⛏️
Given the dynamic nature of Swiggy's content, a traditional iteration over pages was not possible. Instead, automation was utilized to scroll continuously through the website, retrieving data as it dynamically loaded.By leveraging webdriver and selenium, the automation script was designed to mimic user behavior, scrolling down the Swiggy website to capture the dynamically loaded content. This approach allowed the extraction of data beyond what was initially visible on the screen. As the script scrolled down, it effectively retrieved the data, ensuring a comprehensive dataset for further analysis. Following is he code for website automation:
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/e3f73b58-9e4b-4400-9de5-a5a70ac8b59c)

## 2. Data Cleaning 🧹

In the data cleaning phase, Power Query was utilized to refine the extracted dataset from Swiggy, ensuring its accuracy and consistency for further analysis. Several key cleaning processes were implemented:

1. Cleaning Duplicate Data:
    Duplicate records within the dataset were identified and eliminated using Power Query. Removing duplicates ensured that each entry was unique, preventing any distortions in the analysis due to redundant information.

2. Correcting Location Spelling:
    Inconsistent or misspelled location data was rectified using Power Query transformations. Standardizing the location names not only enhanced the dataset's readability but also facilitated accurate geographical analysis, enabling precise insights into regional trends.

3. Removing Null Values:
    Null or missing values in the dataset were identified and removed to enhance data completeness. Power Query allowed for the easy identification and filtering out of these null values, ensuring that the dataset was comprehensive and reliable for subsequent analysis.

# Key Learnings:
The Swiggy project offers several key learnings that can be invaluable for entrepreneurs and businesses:
  - Data-Driven Decision Making: Swiggy's success is attributed to its effective use of data analytics. Entrepreneurs can learn the importance of collecting, analyzing, and leveraging data to make informed decisions. Data-driven insights enable businesses to understand customer preferences, market trends, and operational efficiencies, leading to strategic choices.


# Futute Scope:
The future scope of Swiggy's analysis for entrepreneurs entering the hotel business is vast and promising. Here are some key areas where Swiggy's data analytics can be leveraged for strategic decision-making:

  - Market Demand Analysis: Swiggy's extensive data can be used to analyze market demand patterns. Entrepreneurs can identify specific cuisines, dishes, and food types that are popular in a particular location. This information is crucial for menu planning and understanding local tastes and preferences.

  - Location Intelligence: Swiggy's data can provide insights into the most lucrative locations for opening a hotel or restaurant. By analyzing delivery trends, foot traffic, and customer demographics, entrepreneurs can make data-driven decisions about the optimal location for their business, maximizing visibility and profitability.

  - Dynamic Pricing Strategies: Swiggy's pricing data can be used to implement dynamic pricing strategies based on demand fluctuations, seasonal changes, and local events. By adjusting prices in real-time, entrepreneurs can optimize revenue and stay competitive in the market.

  - Supply Chain Optimization: Swiggy's data analytics can help in optimizing the supply chain by predicting demand for various ingredients and supplies. This ensures efficient inventory management, reduces wastage, and maintains cost-effectiveness in operations.

  - Customer Behavior Analysis: Swiggy's customer behavior data provides valuable insights into ordering habits, peak ordering times, popular add-ons, and customer feedback. By understanding customer preferences, entrepreneurs can tailor their services, menus, and marketing efforts to enhance customer satisfaction and loyalty.

  - Operational Efficiency: Swiggy's analytics can be utilized to streamline internal processes, such as kitchen operations and delivery logistics. Entrepreneurs can optimize staffing levels, delivery routes, and order processing times, leading to improved efficiency and reduced operational costs.

  - Quality Control and Feedback Analysis: Swiggy's feedback and rating data offer a window into customer satisfaction levels. Entrepreneurs can analyze this data to maintain high-quality standards, address customer concerns, and continuously enhance the overall dining experience.

  - Expansion Strategies: Swiggy's data can aid entrepreneurs in identifying potential areas for business expansion. By analyzing demand trends in different regions, entrepreneurs can make informed decisions about opening new outlets or diversifying their offerings to meet specific market needs.

  - Partnership and Collaboration Opportunities: Swiggy's network of restaurants, cloud kitchens, and suppliers can provide valuable partnership opportunities for entrepreneurs. By analyzing successful collaborations within the Swiggy ecosystem, entrepreneurs can identify potential partners for sourcing ingredients, exploring co-branding opportunities, or expanding their menu offerings.

In summary, leveraging Swiggy's robust data analytics capabilities can empower entrepreneurs entering the hotel business with actionable insights. By harnessing this data, entrepreneurs can make informed decisions, optimize their operations, enhance customer experiences, and stay ahead in the competitive hospitality industry.
