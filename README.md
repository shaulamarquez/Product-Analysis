# 🛍️ Product Analysis with Customer Reviews

Sources: BestBuy, Amazon, Walmart, eBay, Homedepot, Petco and CBW

## 📊 Overview
This project performs a comparative analysis of products across seven major e-commerce platforms—BestBuy, Amazon, Walmart, eBay, Homedepot, Petco and CBW. It includes an in-depth look at:

* Customer Reviews

* Recommendation Rate

* Products

* Ratings

* Brands

The goal is to help the client to understand about ratings and reviews of their products that can influence their sales. Identifying the top performing and highly recommended products that can help their marketing strategy.


![image](https://github.com/user-attachments/assets/2cf68be7-2a99-415a-bb3c-c8ebc85ce270)
![image](https://github.com/user-attachments/assets/c0ed96d5-8916-488d-a952-103f04fdfe31)

## 📊 Data Dictionary

* id	- A unique identifier for each product entry	String
* brand - The brand name of the product	String
* categories - The categories the product belongs to, often separated by commas	String
* colors - The color(s) of the product, standardized to lowercase	String
* dateAdded - The date the product was added to the dataset	DateTime
* dateUpdated	- The most recent date the product information was updated	DateTime
* dimension	- The dimensions of the product, filled with 'Unknown' if missing	String
* manufacturer- The manufacturer of the product, filled with 'Unknown' if missing	String
* manufacturerNumber - The manufacturer's unique number for the product	String
* name - The name of the product	String
* reviews.date - The date of the review, converted to datetime format	DateTime
* reviews.dateSeen - The date(s) the review was seen, could be multiple dates separated by commas	String
* reviews.doRecommend - Whether the reviewer recommends the product ('True', 'False', or 'Unknown' for missing data)	String
* reviews.numHelpful - The number of people who found the review helpful, with outliers removed	Float
* reviews.rating - The rating given by the reviewer, on a scale from 1 to 5	Float
* reviews.text - The text of the review	String
* reviews.title - The title of the review	String
* reviews.username - The username of the reviewer	String
* sourceURLs - The URL(s) where the product information was sourced, could be multiple URLs separated by commas	String
* upc - The Universal Product Code for the product	Float
* weight - The weight of the product, standardized to a string format	String




