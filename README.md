<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# The price of living in Barcelona
*[Jorge González González]*

*[Data Analytics, Barcelona Oct 2020]*

## Content
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The goal of my project is to analyze the real estate market in Barcelona and create a machine learning model for predicting housing prices.

## Dataset
I have create my own database doing web scraping in Idealista.
I have collected data randomly from the 10 districs of Barcelona.
I have published my data base in Kaggle "Barcelona_Idealista_HousingPrices".

## Cleaning
I have use regular expessions and pandas for cleaning the data.
When information was missing and an assumption couldn't be done, I have decided to drop the data.
Outliers were also treated.

## Analysis
I have analyzed the data by districs and neighborhoods.
I have segregated the data based on the different variables I could extract from Idealista.
For visualization I used Tableau and matplotlib.
I used a geojson file to allocate data geographically.



## Model Training and Evaluation
I have trained five different models from two different libraries:

- K-Nearest Neighbors
- Linear Regression
- Random Forest
- Support Vector Regression
- XGB Regressor

I have use r2 as a metric.

## Conclusion
Predicting housing prices it's pretty complicated, there may be a lot of factors that may impact the final price.
However, having good quality data, I believe this tool may have real applications for Real Estate Agencies.
Looking at our dat, we gathered several insights:
-West and Central areas of Barcelona have higher prices. 
-Average prices are affected by extreme values which can be seen in most of the districs in Barcelona. Using the median statistic we can avoid this issue.
-The more expensive is a district, the wider the range of housing prices we will have.
-Detached and Semi-Detached houses have the higer average price.
-Sant Marti is the neighborhood where there are more new brand homes.

## Future Work
My next step would be compare Idealista prices which real selling prices in order to see if the idealista prices are in line with the market price.

## Workflow
- Web Scraping (Selenium)
- Data Cleaning
- Visualization
- Machine Learning

## Organization
I have used Trello for organizing my proyect.

Repository:
- Folders Structure:
	- Code (Python Files, .gitignore, )
	- Data (csv files & geojson files)	
	- README 

## Links
[Repository](https://github.com/code-Jyu/Real-Estate-Barcelona)  
[Slides](https://docs.google.com/presentation/d/1H6QvCdSc6cJSL3QJMT-gw5GrnjwGF1B49OrD5vKln6g/edit#slide=id.gb17d8b65db_0_92)  
[Trello](https://trello.com/b/Uk3rX5IR/final-project-bcn-real-state)  
