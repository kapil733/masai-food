# Masai_Food


![maxresdefault](https://github.com/kapil733/masai-food/assets/155940732/2e47d43d-407d-489c-9067-773e1ea643ac)













https://public.tableau.com/shared/RZW8KH32Z?:display_count=n&:origin=viz_share_link


# **Title**: Masai food, Bengluru

### **overview**
This project aims to analyze and extract valuable insights from the restaurant data of Bengaluru. These insights will help clients make informed decisions on key aspects to consider when opening a new restaurant in Bengaluru. The project focuses on determining the type of restaurant to open, identifying the best suitable location, pricing items on the menu, and selecting the types of cuisine to offer.

### **Objectives**
Determine the Optimal Type of Restaurant: Identify the most popular types of restaurants in Bengaluru and the preferences of local diners.
Best Suitable Location: Analyze various locations in Bengaluru to find the areas with the highest potential for a new restaurant.
Menu Pricing: Provide recommendations on the optimal pricing for menu items based on market trends and competitor analysis.
Cuisine Selection: Identify the most popular cuisines in Bengaluru to curate a menu that caters to local tastes and preferences.


### **Tool used**:

Requests

Selenium and bs4(BeautifulSoup)

Matplotlib and seaborn

Pandas

NumPy

Excel

### **Methodology** 🛠️

1) Getting Data: first we request to Zomato server to allow us for data scraping using class request.get() of requests package. we install requests package using pip install requests and than passing request using request.get(url of zomato). after getting a response code 200 we are able to do scraping.

2) Web scrapping: after getting permission the process of web scrapping is done with the help of BeautifulSoup and Selenium.using different tags of HTML we fetch the text part and store in a dictionary. after successfully storing the data in dictionary we convert the dictionary into a DataFrame with the help of padas library.

3) data cleaning: using different method of numpy and pandas library we clean the data. In data cleaning we remove the duplicates values, replace Nan values either with Zeroes or mean value from the data set

4) data visualization: Matplotlib and seaborn libraries are used for visualization purposes.


###  Content 📋

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


### **Quick Summary**
1.Using Selenium And BeautifulSoup libraries of Python we Extracted data present on page and stored it in series and merging them to get DatFrame

**MainPage Scrapper**
![Screenshot (333) 1](https://github.com/kapil733/masai-food/assets/155940732/1c9e9a48-2b19-46b7-8ce7-22d230ae8e26)

![Screenshot (334) 2](https://github.com/kapil733/masai-food/assets/155940732/928cf5ba-97b9-41a2-a1b0-1f76c0c495b5)






2. After obtaining the DataFrame we performed some data cleansing operation using Power Querry Editor , Excel and obtained a single table.

# **Raw data**

## Table 1 :
![Screenshot 2024-06-14 221220](https://github.com/kapil733/masai-food/assets/155940732/9853e8a5-e389-4d24-80b6-0561790ef4d1)

## Table 2 :
![Screenshot (335)](https://github.com/kapil733/masai-food/assets/155940732/f535f482-6e5f-4385-863b-70bbdea62888)





# **Cleaned Table and Joined Table(After Cleaning raw data)**

 ![Screenshot 2024-06-14 221019](https://github.com/kapil733/masai-food/assets/155940732/c872ebf8-23ca-4da7-afa8-e8265f7089a4)







## **Final Chart Using Data Visualization (Matplotlib and seaborn libraries)**

 (a) Count of resurant by Area

 
  ![Screenshot 2024-06-15 094215](https://github.com/kapil733/masai-food/assets/155940732/22d7df44-9fbc-4571-bd00-07658de9436e)


  (b) Rating Category Distribution

  
   ![Screenshot (328)](https://github.com/kapil733/masai-food/assets/155940732/ad467ac8-932c-4fb3-ac8e-3856f7e9ee0b)

   (c) price range by cuisine

   
   ![Screenshot (327)](https://github.com/kapil733/masai-food/assets/155940732/7888327a-8c09-48ba-b615-db1e78bb5ba1)


    (d) Rating category by review Count  

    
   ![Screenshot (326)](https://github.com/kapil733/masai-food/assets/155940732/02a1eae3-3e57-4804-94cf-28d26b9c6e85)














### **Challenges Faced**
There are several limitations and challenges that arised during the project. Some potential challenges include:

(1) Learning web scraping with different tools was challenging due to the diversity of tools, evolving website structures, anti-scraping measures, and the need for data cleaning and 
    preprocessing.
    
(2) Dynamic page scrolling posed an additional challenge during the data scraping process, requiring specific techniques and tools to effectively capture and extract the desired 
    information from web pages that load content dynamically as the user scrolls.
    
(3) Data quality and consistency were compromised in the scraped data from Zomato, with errors, missing values, and inconsistencies present, thereby impacting the integrity of the raw 
    dataset.



**DASHBOARD**:

![Zomato final dashboard](https://github.com/kapil733/masai-food/assets/155940732/dead9b9d-9947-4fae-a660-4a66cb7f19c0)


### **Conclusion**

   (1) As per our analysis, if the person wants to open a remote kitchen in Bangalore he/she should prefer opening it in Shanti Nagar or Basavanagudi, since the place is having less no 
       of restaurant which reduces the competition and it has some of the expensive restaurants in the Banglore, hence the person can deliver food at lower price which reduces the 
       competition even further.

(2)    The second suggestion would be sell North Indian, South Indian cuisine as they are demanded the most by the customers and they can keep the price ranging from 300 - 400 Rs for 
       Non vegetarian category and 200 - 300 Rs for vegetarian category.

