# Power-BI-Practice-Project---Restaurant-Ratings

![Image](https://github.com/lpthao0102/Power-BI-Project-1---Restaurant-Ratings/assets/166318783/722c97bd-43d1-4082-80d6-f6217b983525)

**INTRODUCTION**
-----------------------------------------------------------------------------------------------
Mexico is one of the countries famous for its rich and diverse cuisine. This report provides information on customer ratings and reviews of restaurants from 2012, including information about each restaurant and their cuisines, and each customer and their preferences.

**DATASET**
-----------------------------------------------------------------------------------------------
#of Records: 1910

#of Fields: 13605

Link to the dataset [Link] (http://bit.ly/4ap7Fjz)

**PROBLEM STATEMENT**
-----------------------------------------------------------------------------------------------
The objective of this report is to provide information about the context of the restaurant industry in four cities in Mexico, identify areas for improvement in food quality, service, etc., analyze customers preferences and satisfaction levels to gain insights into their behavior, and develop marketing campaigns aimed at attracting specific customer segments.

**PREPARING AND MODELING DATA**
-----------------------------------------------------------------------------------------------
The dataset includes 5 tables: consumer_preferences, consumers, ratings, restaurant_cuisines and restaurants. Related to data shaping, two tasks that were used in this step are header promotion and column renaming. To address inconsistencies in the data, empty cells were replaced with 'N/A'. Furthermore, the data type of certain columns was modified to prevent performance issues.

This data was modeled using one-to-many relationships due to the presence of foreign keys. The ratings table served as the fact table. For the two tables restaurants and restaurants_cuisines, the data was filtered on both sides of the relationship. Because a restaurant could serve more than one cuisine and a cuisine could be present in more than one restaurant. The same filtering approach was applied to the tables consumers and consumer_preferences.

![0 Model](https://github.com/lpthao0102/Power-BI-Project-1---Restaurant-Ratings/assets/166318783/46a37e53-3a7e-4180-a74f-d2c30879ac1d)

Data Analysis Expression Language (DAX) was utilized to enhance the dataset. Some Measures, such as Total Orders or Total Smokers, were organized into a separate table titled 'facts'. In addition to setting up the table structure, the functionality of creating a hierarchy and forming a new group were also applied.

**VISUALIZATION AND ANALYSIS**
-----------------------------------------------------------------------------------------------
Various cards, tables, charts and graphs were used to create 3 report pages. Some features such as Page Navigation and Bookmarks were employed to optimize the layout of the report page. Each report provides a detailed analysis.

_Page 1: Restaurant Overview_

![1 Restaurant Overview](https://github.com/lpthao0102/Power-BI-Project-1---Restaurant-Ratings/assets/166318783/c66af95e-643f-4a62-8923-4955e3a2b756)

- In general, the average of service rating was lower than the average of food rating and the average of overall rating.
- San Luis Potosi was the city with the highest number of restaurants (84 out of 130), the most diverse cuisine (18 out of 23), and the highest order volume (921 out of 1161).
- More than 80% of the restaurants were independent establishments (non-franchises) and had closed areas.
- Majority of the restaurants did not have smoking policies or serve alcohol, but they were more preferred. Half of the establishments did not have parking areas, but this didn't affect their business operations.
- Restaurants with medium price had the highest demand, followed by those with low prices, while high-priced ones were less attractive.
- In general, the average service rating was lower than the average food rating and the average overall rating.

_Page 2: Detailed Performance_

![2 Detailed Performance](https://github.com/lpthao0102/Power-BI-Practice-Project---Restaurant-Ratings/assets/166318783/22669781-421f-4c5e-87b3-c6a8aacf0a4e)

- Top 3 restaurants were Tortas Locas Hipocampo, Puesto De Tacos and Caffeteria Y Restaurant El Pacifico. What's noteworthy is that they are all located in the city of San Luis Potosi.
- Tortas Locas Hipocampo received the most ratings and the highest number of orders. It was praised for its food, services, and overall experience.
- Top 3 restaurants based on the average of overall ratings were Emilianos, Michiko Restaurant Japones, and Restaurant Las Mananitas.
- With 21 establishments, Cuernavaca city had the best-rated restaurants on average.
- Mexican cuisine was the most served and had the highest sum of overall rating (283). It also ranked at the top on the list of cuisines presented in restaurants (38 out of 130). The highest average (1.75) belonged to Mediterranean cuisine, but it was not as popular.

_Page 3: Customer Report_

![3 Customer Report](https://github.com/lpthao0102/Power-BI-Practice-Project---Restaurant-Ratings/assets/166318783/74c0aac5-707f-401c-a6f4-dac53b199cf6)

Age under 30 is categorized into the youth group, over 60 is the elderly group, while others belong to the middle-aged group.
- More than 60% of customers came from San Luis Potosi.
- Majority of customers preferred Mexican cuisine.
- Smoking and drinking levels did not make much impact because the proportion of non smokers was the majority and social plus casual drinkers were more than 60%.
- Maximum customers used public transportation methods.
- Majority of customers belonged to the youth group, and they were single or not dependent. A significant portion consisted of students with a medium-sized budget.

**RECOMMENDATION**
-----------------------------------------------------------------------------------------------
Understanding customer behavior, preferences, and market dynamics within the restaurant industry in Mexico is crucial. The insights garnered from this report provide valuable information that can guide strategic decisions, marketing methods, and potential investment opportunities by maximizing the utilization of available opportunities:
- Location Preference and Target Demographic: San Luis Potosi stood out as the prime location for restaurants due to its high customer traffic, especially among unmarried people, those around 20 to 30 years old, and students. Therefore, prioritizing this demographic and ensuring easy accessibility by public transport is crucial for success.
- Cuisine Preference and Pricing Strategy: There was a clear demand for Mexican cuisine, with customers mostly having a medium budget. Therefore, it is recommended to offer medium-priced Mexican dishes to satisfy this preference and demographic, ensuring the prices are reasonable while still making a profit.
- Investment Recommendations: Tortas Locas Hipocampos, with its medium pricing and location in San Luis Potosi, presented itself as a top investment option. Despite not offering alcohol service or allowing smoking, it remained the highest-rated restaurant, indicating that these features may not have been necessary for success in this market.
- Market Analysis and Expansion Opportunities: Considering the popularity of Mexican cuisine and the high concentration of restaurants in San Luis Potosi, investors should contemplate focusing on this area for potential expansion, especially in locations near schools to take advantage of student patronage.
