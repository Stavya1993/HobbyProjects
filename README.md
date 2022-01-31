# HobbyProjects
I showcase several hobby projects and other works I have undertaken over the past 5 years. I will list each of them so that it is simpler for you to get a glimpse of my work without getting overwhelmed by technicalities.


*Note, you will have to download the projects to view them, as GitHub does not let one directly access HTML files as I have learnt today. While the .ipynb files can be rendered, viewing window seems small*

## Roombae:  
Roombae is a web application I built with a colleague of mine, and can be currently viewed at roombae.com. 
Once we set up the web app, we found the need to analyse how our users are using the application.
### Folders:
- SQL QUERIES:
For this purpose I queried my postgreSql database and created queries for visualizations in Tableau. 
Unfortunately, I am unable to access my dashboard. However, the **dumpcodes** files should still give you an insight on my SQL skills. 

- Web Scraper:
To initially comprehend the potential of Roombae, I scraped and analysed data from Facebook Groups. For this purpose, I used selenium, and further utilized python for a deep-dive analysis.
The web scraper code: **Facebook-scraper & File generator-NEWUI.html**
Overall Analysis: **FB_OverallAnalysis_Selenium.html**
Individual Deep Dive: **FB_MVP_Selenium-NEWUI.html**  _These codes are no longer functional as Facebook has altered its UI javascript codes_

## Thesis Results - Same-day Grocery Delivery Analysis::
As a part of my thesis, I developed a methodology to ensure grocery orders in Amsterdam are delivered well within 10 minutes. In particular, I used heuristics (read anticipate orders) to augment an existing algorithm and evaluated the performance against the base method.
The main simulator was built in C++ and is not shared in these files.

The files shared here highlight an analysis of my outputs and in particular my ability to visualize data in python.
- I first explored different anticipation approaches and highlighted them in Performance_methods.html. 
- Further, I deep dived on succesful approaches by implementing several alternative hacks to their computation. I analyse the results in Performance_methods.html.  
- Next, I analysed my solutions performance across several realistic instances that I had generated in Python (cannot share because of copyright issues). The results of the same can be seen in Performance_Comparison_Summary.html.  
- I further tested my method on extreme scenarios of demand distribution. I compare my method performance in Performance_Comparison_DatasetTypes_Detail.html. _But more importantly I perform a deep dive EDA on the impact of demand distribution on my system in Demand Data Performance DeepDive.html._

## Airline Predictions:  
I took part in one of Analytics India Magazines competitions in early 2019. The focus of the project was to build a high fidelity airline price predictor given a dataset.
I spent time learning nuances of the industry and used that knowledge to generate several hacks and features to augment the data set. 
In addition, I utilised machine learning packages to build a stacked regressor with a multiple cross validation mechanism. 
I stood first in the competition, and was felicitated at one of the annual analytics events counducted by the Magazine.

## Loan Default:
I took on another hobby project on machine learning modelling in 2018. 
The goal of the project was to predict whether an individual will default on loans or not. 
While I did not complete the competition, I did build a basic regressor and have added the codebase to give you a glimpse of my work

## Black Jack:
I built a game in python. I invite you to execute the code in jupyter and try winning from the computer. ;)

## Tensor Flow:
I explored a gradient descent optimizer using tensor flow as a hobby project.



