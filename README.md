# Donor-Projects
This project was created as a final term project of Business Analytics & Machine Learning course. 
The project includes the folowing files:
1. A readme file named "final markdown.rmd" for an overview description. 
2. A RMD file containing the main codes and partial illustrations of this project.
3. An image showing the formula of profit measure
4. A pdf file 

## Project Description
In 1997, the Paralyzed Veterans of America (PVA) used a direct mailing to appeal to “lapsed” donors. Here is a brief summary of the numbers. On the Valuation data set:
96367 people were mailed
This cost was $0.68 per mailing
This totaled $65,280.
The total amount of donation: $76,100
Hence, the profit: $10,560.

**Question: How can we target a smaller group and yet produce greater profit?


## Profit Measure
![alt text](https://github.com/Locas5/Donor-Projects/blob/master/profit_measure.jpg)

## Prediction Process
In this problem, we developed a model to predict the nature of giving a person might have based on his/her characteristics. To do this, we formulated a KNN model and used the learning data set to estimate parameters.
With model in hand, we focus on the validation data set and select individuals whom we predict to give more than the marketing cost ($0.68).
