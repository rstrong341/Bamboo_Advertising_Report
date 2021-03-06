# Bamboo Advertising Report
Analysis of advertising campaign to reassess where to allocate resources

## Summary
This report is comprised of two datasets, one is total sales and the other is a report from Amazon on the effectiveness of an advertising campaign. The goal of this project is to summarize the two datasets and uncover any significant efficiencies/inefficiencies in order to optimize advertising spending in the future.

For the order report, I created several visualizations showcasing sales over time, how products are doing compared to each other and a geographical breakdown of where the bulk of sales are coming from.

For the advertising report, I focused more on trying to draw correlations between sales and the different metrics offered by Amazon.  

Moving forward, I will follow along as I receive new data to see how advertising efforts are affecting sales numbers.

## How to view project
* All cleaning was done in order report cleaning and ad report

* All visualizations were done in Orders_Viz and Advertising Viz

# Order Report
### Monthly Breakdown
* Looking at the monthly breakdown of sales we can see a steady increase in sales over time with a steep increase in May and June
* IMPORTNAT NOTE, both December and June are only half of a month
* Looking forward I will be updating as time goes on to determine if these rises are seasonal or if they are going to continue to rapidly increase.
![](https://user-images.githubusercontent.com/74929838/125850029-5aa5a478-5472-4abc-a345-9a0194cfac04.PNG)
### Product Breakdown
* Here we can see that Rainforest Bowls are outperforming Floral Bowls every month.  
* The one unique trend is the dip in Rainforest sales in March along with a steep rise in Floral sales.  It could be worth looking into the following year to see if a similar trend takes place.
![](https://github.com/rstrong341/Bamboo_Advertising_Report/blob/main/images/Montly_Product_Sales.PNG)

### Regional Breakdown
* Initially I wanted to see what states placed the most orders in order to hone in on what regional demographics are worth targeting.  However, the first thing I noticed was that all of the states with high order totals all have massive population sizes.  
* This led me to add a second visualization to show which states have the most sales in relation to their population size.
* After viewing both graphs I'd conclude that California, Vermont, Washington, Massachusetts and Colorado are the best states to market to.

Orders By State            |  Orders By State Per Capita
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/74929838/125850962-a78e9f97-0c1d-4cfc-8476-2f734256f8d4.PNG)  |  ![](https://user-images.githubusercontent.com/74929838/125850882-69ed4e26-ea8b-41a3-ae73-50c198c29a2a.PNG)

* Click this link to view a map that includes a pin for all purchases including international purchases
https://www.google.com/maps/d/edit?mid=1LwwXuNbNnIjzqFwPGB1MRaMHgiwj1_GA&usp=sharing
  
  

# Advertising Report
### Correlation Heatmap for Spending Per Day
* Here, I am trying to see what factors impact how much we spend.
* As expected, Clicks are almost a perfectively direct correlation.
* What I found interesting was that Sales had a clearer correlation than impressions.
![heatmap](https://user-images.githubusercontent.com/74929838/125853926-38712312-0773-4450-8448-796816e23da4.png)

## Impressions Vs. Sales
* With this visualization I wanted to see the difference between how Impressions and Sales effect how much we spend.

Impression and Spending            |  Sales and Spending
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/74929838/131764901-85cefd67-2e71-4a5f-9d2e-633f05735979.PNG)  |  ![](https://user-images.githubusercontent.com/74929838/131764913-ee9ce7be-73ea-40ba-ae69-a0bc3b32d861.PNG)

## Glossary

* ACoS (Advertising Cost of Sale): shows how much you spent on ads to gain a dollar from attributed sales. 
* ROAS (Return on Ad Spend): tells you how much money you earn for every dollar you spend on advertising. 

## Key Words to Continue Financing

### ACOS
![ACOS](https://user-images.githubusercontent.com/74929838/131765208-d083ba4c-7fa6-4656-a30b-3329e48efae8.PNG)

### ROAS
![ROAS](https://user-images.githubusercontent.com/74929838/131765223-710ea494-eb9a-4457-bd74-4d047fddc3cb.PNG)


## Identifying key words to avoid
* In order to effectively adjust how we spend our advertising money I wanted to look at what key words we're spending money on but yield zero profits.


![](https://user-images.githubusercontent.com/74929838/125853727-565b2911-6582-4cb5-8258-311892080d2f.PNG)

# Conclusion
* We can clearly see that profits are trending upwards and that if we continue to actively identify efficiencies as well as inefficiencies we can easily justify all adversising spending.
* We will look to monitor these trends over the upcomming months to make improvements.

