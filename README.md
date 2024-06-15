# masai-food


![image](https://github.com/kapil733/masai-food/assets/155940732/9e852c87-2248-4247-a108-d5f9c957cd3e)









**Title**: Masai food, Bengluru




### **overview**
This project aims to analyze and extract valuable insights from the restaurant data of Bengaluru. These insights will help clients make informed decisions on key aspects to consider when opening a new restaurant in Bengaluru. The project focuses on determining the type of restaurant to open, identifying the best suitable location, pricing items on the menu, and selecting the types of cuisine to offer.

*Objectives*
Determine the Optimal Type of Restaurant: Identify the most popular types of restaurants in Bengaluru and the preferences of local diners.
Best Suitable Location: Analyze various locations in Bengaluru to find the areas with the highest potential for a new restaurant.
Menu Pricing: Provide recommendations on the optimal pricing for menu items based on market trends and competitor analysis.
Cuisine Selection: Identify the most popular cuisines in Bengaluru to curate a menu that caters to local tastes and preferences.


### **tool used**:

Requests

Selenium and bs4(BeautifulSoup)

Matplotlib and seaborn

Pandas

NumPy

**Methodology** 🛠️

1) Getting Data: first we request to Zomato server to allow us for data scraping using class request.get() of requests package. we install requests package using pip install requests and than passing request using request.get(url of zomato). after getting a response code 200 we are able to do scraping.

2) Web scrapping: after getting permission the process of web scrapping is done with the help of BeautifulSoup and Selenium.using different tags of HTML we fetch the text part and store in a dictionary. after successfully storing the data in dictionary we convert the dictionary into a DataFrame with the help of padas library.

3) data cleaning: using different method of numpy and pandas library we clean the data. In data cleaning we remove the duplicates values, replace Nan values either with Zeroes or mean value from the data set

4) data visualization: Matplotlib and seaborn libraries are used for visualization purposes.


## Content 📋

The Zomato dataset provides a unique opportunity to gain valuable insights into Bengaluru's vibrant restaurant scene. With over 12,000 restaurants serving diverse cuisines worldwide, Bengaluru is a dynamic culinary hub. This analysis aims to shed light on the factors influencing restaurant establishment and success, as well as the preferences of the city's residents.
Bengaluru, known as the IT capital of India, witnesses a continuous influx of new restaurants to meet the growing demand for convenient dining options.
Many people here rely on restaurant food due to time constraints.
Despite the increasing demand, newcomers often struggle to compete with established eateries, often offering similar menus.
Given the overwhelming demand for restaurants, it becomes crucial to examine the demographic characteristics of different localities.


## To address these questions, we will leverage the Zomato dataset to analyze the following factors:
(1) Location of the restaurant
(2) Approximate price of food
(3) Theme-based restaurant categorization
(4) Localities with the highest concentration of specific cuisines
(5) Meeting the culinary needs of residents
(6) We were able to scrape the Zomato website successfully and extract around 3,000 records.


## key finding Sections 📚
 
 (1) Area-wise distribution
 (2) cheapest and the most expensive restaurant with respect to cuisine
 (3) maximum number of restaurants where the delivery review number is greater than 1000.
(4)  Location with maximum number of the less-rated restaurant.
(5)  Area wise cheap and expensive restaurant and their average price.
(6)  Number of restaurants for each type of cuisine.
(7)  interesting insight from the data







conclusion

