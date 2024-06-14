# masai-food
Title: Masai food, Bengluru
![alt text](image.png)

overview
This project aims to analyze and extract valuable insights from the restaurant data of Bengaluru. These insights will help clients make informed decisions on key aspects to consider when opening a new restaurant in Bengaluru. The project focuses on determining the type of restaurant to open, identifying the best suitable location, pricing items on the menu, and selecting the types of cuisine to offer.

Objectives
Determine the Optimal Type of Restaurant: Identify the most popular types of restaurants in Bengaluru and the preferences of local diners.
Best Suitable Location: Analyze various locations in Bengaluru to find the areas with the highest potential for a new restaurant.
Menu Pricing: Provide recommendations on the optimal pricing for menu items based on market trends and competitor analysis.
Cuisine Selection: Identify the most popular cuisines in Bengaluru to curate a menu that caters to local tastes and preferences.


tool used:
Requests
Selenium and bs4(BeautifulSoup)
Matplotlib and seaborn
Pandas
NumPy




methodology

1) getting Data: first we request to Zomato server to allow us for data scraping using class request.get() of requests package. we install requests package using pip install requests and than passing request using request.get(url of zomato). after getting a response code 200 we are able to do scraping.

2) Web scrapping: after getting permission the process of web scrapping is done with the help of BeautifulSoup and Selenium.using different tags of HTML we fetch the text part and store in a dictionary. after successfully storing the data in dictionary we convert the dictionary into a DataFrame with the help of padas library.

3) data cleaning: using different method of numpy and pandas library we clean the data. In data cleaning we remove the duplicates values, replace Nan values either with Zeroes or mean value from the data set

4) data visualization: Matplotlib and seaborn libraries are used for visualization purposes.


key findings





Area-wise distribution
cheapest and the most expensive restaurant with respect to cuisine
maximum number of restaurants where the delivery review number is greater than 1000.
Location with maximum number of the less-rated restaurant.
Area wise cheap and expensive restaurant and their average price.
Number of restaurants for each type of cuisine.
interesting insight from the data







conclusion

