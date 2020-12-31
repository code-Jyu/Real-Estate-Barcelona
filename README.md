<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# The price of living in Barcelona
*[Jorge González González]*

*[Data Analytics, Barcelona Oct 2020]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
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
I would analize the prices of the houses through the different disctrics segregating the data by property type and condition.


## Dataset
I have create my own database doing web scraping in Idealista.
I have collected data randomly from the 10 districs of Barcelona.
I have published my data base in Kaggle "Barcelona_Idealista_HousingPrices"

## Cleaning
I have use regular expessions and pandas for cleaning the data. I have dropped missing values when I could not replace them.

## Analysis
I have used Tableau for data visualization.
I have a analyze the date by districs and segregating the data by property condition and property type.


## Model Training and Evaluation
I have trained five different models : 
- K-Nearest Neighbors
- Linear Regression
- Random Forest
- Support Vector Regression
- XGB Regressor

I have use r2 as a metric.

## Conclusion
Predicting house prices it's pretty complicated, there may be a lot of factors that may impact the final price.
West and Central areas of Barcelona have higher prices. 
Average prices are affected by extreme values which can be seen in most of the districs in Barcelona.
Sant Marti is the neighborhood where there are more new brand buildings.

## Future Work
My next step would be compare Idealista prices which real selling prices in order to see if the idealista prices are in line with the market price.

## Workflow
Outline the workflow you used in your project. What were the steps?
How did you test the accuracy of your analysis and/or machine learning algorithm?

## Organization
I have used Trello for organizing my proyect

Repository:
- I have two main folders:
	- Code (Python Files, .gitignore, )
	- Data (csv files & geojson files)
	- README 

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project.


[Repository](https://github.com/Jyu-as/Project-Week-8-Final-Project/blob/master/your-project/README.md)  
[Slides](https://docs.google.com/presentation/d/1H6QvCdSc6cJSL3QJMT-gw5GrnjwGF1B49OrD5vKln6g/edit#slide=id.gb17d8b65db_0_92)  
[Trello](https://trello.com/b/Uk3rX5IR/final-project-bcn-real-state)  
