# Electronics Product Analysis with Customer Reviews (2007-2018)

Dataset: [onyxdataset](https://onyxdata.kit.com/datadna-feb-2024)

## Overview
This project is a February 2024 Data DNA - Dataset Challenge!

Using Electronic Product Data Ratings dataset that performs a comparative analysis of products across seven major e-commerce platforms—BestBuy, Amazon, Walmart, eBay, Homedepot, Petco and CBW. It includes an in-depth look at:

* Customer Reviews

* Recommendation Rate

* Products

* Ratings

* Brands

The goal is to help the client to understand about ratings and reviews of their products that can influence their sales. Identifying the top performing and highly recommended products that can help their marketing strategy.

## Dashboard

![image](https://github.com/user-attachments/assets/2cf68be7-2a99-415a-bb3c-c8ebc85ce270)
![image](https://github.com/user-attachments/assets/c0ed96d5-8916-488d-a952-103f04fdfe31)

## Data Dictionary

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

# Executive Summary
* A total of 7,299 reviews were collected between 2007 and 2018 from seven sources: Amazon, BestBuy, CDW, eBay, Home Depot, and Petco. The average rating across all reviews is 4.3 stars, with the highest rating (5 stars) accounting for 61.5% of all reviews.

* From 2007 to 2018, the average rating shows an upward trend, following a notable dip to 2.1 in 2009.

* Logitech received the highest number of 5-star reviews, with a total of 834 reviews, outperforming its competitors in volume. The top five brands with an average rating of 5 stars are House of Marley, SVS, Toshiba, Kicker, and Clarity-Telecom.

* The five lowest-rated brands, each with an average rating of 3 stars, are Bose, Dreamwave, Lenovo, Motorola, and Yamaha.

* The top five brands with a 100% recommendation rate are Peerless-AV, House of Marley, SVS, Toshiba, and Kicker. In contrast, the brands with the lowest average recommendation rate, at 23%, are Dreamwave, Motorola, Yamaha, Sony, and JVC.

# Recommendations

* Prioritize Partnerships with High-Performing Brands
Brands like Logitech, SVS, House of Marley, Toshiba, and Kicker consistently receive high ratings and 100% recommendation rates. Consider prioritizing or expanding partnerships with these brands to maintain customer satisfaction and trust.

* Reassess Low-Performing Brands
Brands such as Dreamwave, Motorola, Yamaha, Sony, and JVC show both low average ratings (around 3 stars) and low recommendation rates (~23%). These may need quality audits, improved customer support, or reevaluation in product listings.

* Investigate the 2009 Rating Dip
The sharp dip in average rating to 2.1 in 2009 suggests an issue that may have affected product or service quality during that year. Further investigation could provide lessons for avoiding similar downturns.

* Promote Top Recommended Brands
Use marketing campaigns to highlight the brands with 100% customer recommendation—this can build consumer confidence and drive conversions.

* Encourage Reviews for Less-Rated Brands
Some brands may be underrepresented in the data. Encouraging verified reviews for newer or niche brands can provide a fuller picture and uncover hidden strengths or weaknesses.



