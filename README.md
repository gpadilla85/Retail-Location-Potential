# Retail-Location-Potential

## Problem Description

The problem to solve in this project is to determine the business potential for a specific type of food venue (restaurant / coffee shops) by inputting a set of parameters to our model.


## Background

While there are many factors that ultimately determine the success of a restaurant business, location is perhaps one of the most critical ones. To illustrate, all other things equal, consider A) a restaurant located in a quiet street in a residential neighborhood with no other venues nearby, will it have the same chances of succeeding as B) a restaurant located in a busy area with high loads of foot traffic and complementary venues nearby? The answer is probably not. But at the same time we cannot be 100% certain, population density can also play against the business success by making competition more fierce.

**Approach.** With this project we aim to look at this problem from a Data Science perspective, select the parameters that probably play a bigger influence in determining success studying their correlations with the target variable as well as their cross influence. Ideally we aim to weight the importance of each parameter so we can correctly model our function. We will gather data from location data providers on retail stores (such as Foursquares), clean it, prepare it and use it to train and test our Model. To make things simpler, we are going to restrict the study to coffee shops, leaving other cases left open for future analyses. Finally we will focus our study in a city with good number of coffee shops, economic activity and with a wealth of data. 

**Audience.** While this field of study might be interesting to any curious mind, it might be of particular appeal to restaurant business owners, food business entrepreneurs, investors, banks, governments, commerce chambers and all actors in general that have a stake in a food restaurant business and have shared interest in the success of it.

## Description of the Data

We will use location data and we will choose FourSquare as our Data Provider. Looking at their API documentation the following parameters will be strong candidates to use in our project: 

*>> Data from FourSquare*

**CORE DATA**
- venueId
- latitude
- longitude
- address
- city
- category_primary
- category_secondary

**RICH DATA**
- rating
- popularity_score
- price
 

## How will the Data be used

This data will be used to train a Linear Regression Model that will output a score that will give an idea of the business potential of opening a coffee shop in a given location. 
Prior to feeding the Model the data will be collected, inspected, cleaned and prepared to fit our particular Model. 

