# Capstone-Project-Real-Estate-Listings-Automated-Comparison
Capstone Project Real Estate Listings: Automated Comparison



# Final-Project-Tableau


Introduction

In the dynamic realm of real estate, where market trends fluctuate and economic landscapes evolve, understanding the intricate interplay of factors governing property transactions is essential for success. As the cornerstone of wealth generation and economic development, real estate encompasses a myriad of disciplines, from finance and investment analysis to urban planning and property law. This capstone project delves into the multifaceted world of real estate, aiming to explore, analyze, and propose innovative solutions to contemporary challenges facing the industry.

Understanding Real Estate Dynamics

Real estate markets operate within a complex ecosystem influenced by macroeconomic factors, demographic shifts, technological advancements, and regulatory frameworks. The volatility and resilience of these markets necessitate a comprehensive understanding of supply and demand dynamics, investment strategies, and risk management techniques. By examining historical trends, market data, and predictive analytics, stakeholders can gain insights into market behavior and make informed decisions regarding property acquisition, development, and disposition.

Emerging Trends and Challenges

The real estate landscape is constantly evolving, driven by emerging trends and disruptive technologies. From the rise of proptech startups revolutionizing property management to the growing demand for sustainable and resilient infrastructure, stakeholders must adapt to changing consumer preferences and regulatory requirements. Moreover, demographic trends such as urbanization, aging populations, and remote work have profound implications for housing demand, commercial development, and community planning. Addressing these challenges requires innovative approaches, collaborative partnerships, and forward-thinking strategies that balance economic growth with social and environmental sustainability.


# Project/Goals

This capstone project aims to achieve the following objectives:

Comprehensive Analysis: 

Conduct a thorough analysis of local, regional, or national real estate markets, identifying key trends, opportunities, and challenges.

Case Studies: 

Explore real-world case studies highlighting successful real estate projects, investment strategies, and regulatory frameworks.

Innovative Solutions:

Propose innovative solutions to address contemporary challenges facing the real estate industry, such as housing affordability, infrastructure development, and sustainable urbanization.

Stakeholder Engagement: 

Engage with industry professionals, policymakers, and community stakeholders to gain diverse perspectives and insights into real estate dynamics.

Strategic Recommendations: 

Develop strategic recommendations for stakeholders, including investors, developers, government agencies, and community organizations, to enhance decision-making processes and maximize value creation in real estate projects.

Conclusion

As the global population continues to grow and urbanize, the demand for quality housing, infrastructure, and amenities will intensify, presenting both opportunities and challenges for the real estate industry. By leveraging data-driven insights, embracing innovation, and fostering collaboration, stakeholders can navigate the complexities of the real estate market and contribute to sustainable development and inclusive prosperity. This capstone project endeavors to provide a holistic understanding of real estate dynamics and equip stakeholders with the knowledge and tools to thrive in an ever-changing landscape.



# Process



Data Preparation

This involved getting the dataset, converting to a data source supported by Tableau, imported the dataset into Tableau, which includes the name of the airbnb, the property type, room type, beds, price and other relevant data.

Data exploration

Explored the data to view the details provided by using data source provided in Tableau.

Data Cleaning

Perform necessary data cleaning tasks such as

Handled missing values by filtering out and replacing missing values using Tableau's data preparation tools.

Removed duplicates records from the data.

Standardizied data formats by ensuring that data types are consistent across columns.

Renamed fields to make them more understandable or consistent.

Data Transformation

Transfrom the data by combining multiple fields and grouping data into creating meaningful categories.

Used aggregation data at different levesl using different functions like SUM, Quartile, Max and Min.

Data Validation

Validated data to ensure ensure accuracy and consistency, while checking for outliers, anomalies and discrepancies that will affect the analysis of the data used.

Creating data visualization

Once the data is ready, then several tools like charts, graphs, maps to present data retrieved and prepared to showcase this information on tableau. This will be used to create different views and analyze trends and patterns

Results

The results from this project was generated by answering the following questions.

Considering the influence of factors like location and property features, how significant is the correlation between the number of bedrooms and the total price of properties in the dataset?

By using a Box and Whisper plot

Box Plot:

The box represents the interquartile range (IQR) of the data, with the median sum of prices depicted by a line inside the box for each category of bedrooms.
It provides insights into the central tendency of total prices across different bedroom categories.
The length of the box signifies the spread of total prices within each category of bedrooms.
The whiskers extend from the box, indicating the range of total prices excluding outliers.
Whisper Plot:

The whisper plot overlays individual data points, each representing a real estate property and its corresponding sum of prices and number of bedrooms.
It offers a detailed view of the distribution of total prices for each category of bedrooms.
Patterns or clusters of data points within the plot can indicate trends or correlations between total price and number of bedrooms.

Interpretation:

While the number of bedrooms affect the pricing of the various housing, it's just one of many variables that collectively determine property prices some of which are.


Location: The old adage "location, location, location" holds true in real estate. Properties in desirable neighborhoods or areas with good amenities, schools, transportation links, and low crime rates often command higher prices regardless of the number of bedrooms.

Property Size and Features: The total square footage of a property, as well as specific features like the presence of a backyard, swimming pool, or high-end appliances, can significantly influence its price.

Market Conditions: Supply and demand dynamics, as well as broader economic conditions, can impact real estate prices. In a seller's market with high demand and limited inventory, prices tend to rise, whereas in a buyer's market, prices may stagnate or even decrease.

Property Condition: The overall condition of the property, including any necessary repairs or renovations, can affect its perceived value and, consequently, its price.

Historical Trends: Historical sales data and price trends in the area can provide valuable insights into how prices have evolved over time and help forecast future price movements.

Given these factors conducting a thorough analysis that takes into account various factors can provide a more comprehensive understanding of real estate market dynamics.


![image](https://github.com/Ayiwoma/Capstone-Project-Real-Estate-Listings-Automated-Comparison/assets/141646278/529f7b0c-83d6-4569-89b1-a79ce543d1e7)




Using Line graph was another way to showcase this data, this combined the AirBnB hosts since 2009, the top X customers and their price range, this chart enabled the data to show that the highest price point was in 2014, it also showed the trend of rentals from the different hosts. This line graph can also be used to project future trends thereby making informed decisions based on predicitive analytics because it combines three data types.

image

Use the trend of past number of beds and price to forecast the trend with scatter plot to show that where clients will rent airbnb in the future as that has been the trend in past as the concentration is in the lefthand corner of the chart.

image

In comparing the data set and identifying outliers, a box plot was used to show the concentration of rentals across room type and prices. This chart showcased the median price range for each property type and room type, while also showing the outliers for prices that are out of range. The observation noticed here is that the property type that were the outliers, had some unique features some of which villa and private room. Using this box plot also showed both the upper whisker, upper hinge and lower whisker, lower hinge indicating the interquartile range across the data excluding the outliers.

image

A bar chart was used to showcase how number of rooms compared to prices, some rooms rented for less and some rooms rented for more, which showed that the price was not a determining factor when it compared to count of rooms rented. The insight from this type of chart showed that the product determined the price in this case the product is the room type. This bar chart shows comparison between categories across room types and property types, recommendation given will be that investing in the types that provide the most revenue.

image

Tableau Dashbord

https://public.tableau.com/app/profile/ayiwoma.anwasia/viz/practicestory_17154032168170/AirBnDNYC?publish=yes

Challenges
Some of the challenges faced included having to deals with missing data, which would affect the accuracy of the data provided, and would require extensive cleaning and preprocessing before visualization can occur. Some of the missing data included zip codes and host names. Therefore the data shown included only the available data.

Determing profit was difficult as no data showing cost was provided so therefore comparison could not be made as to the profitability of a unit available for rent.

Deciding on which visualtion was the most suitable to present the information in a very easy to understand manner, that will best convey the information to the user.

Future Goals
Clean up the data more and ensure that it more accurate to present to the required audience.

Use other wasys to combine the data presented to give more insights into the provided data.
