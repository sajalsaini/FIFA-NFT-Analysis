# FIFA-NFT-Analysis ⚽
This [dashboard](https://app.flipsidecrypto.com/dashboard/fifa-nft-analysis-g5Lqha) is a way for novices to have a bird eye look at the FIFA NFTs released by FIFA+ Collect. A very important factor in designing this dashboard has been given to its business relevance. Each query has been placed and set up in a way to derive insights from the Algorand database provided on [Flipside Velocity](https://app.flipsidecrypto.com/velocity)

# Introduction 🚀
FIFA introduced [FIFA+ Collect](https://collect.fifa.com/), which is a platform which allows its fans to purchase digital collectables of some of the most memorable moments in the history of FIFA

# Process ⚡

## EDA 🔎
1. The analysis starts off with finding the number of drops and NFTs released in the FIFA NFT collection
2. Then we see the total sales for each drop, the number of purchasers and the number of NFTs for each drop
3. The previous process step will allow a novice in the NFT domain to find which collection is the most popular in terms of volume and purchasers

## Time-Series Analytics ⌚
1. A crucial step in analyzing a particular NFT is its growth (in terms of sales and volume) over time. Charting its growth will allow a newbie to really understand if the NFT is performing well. Hence, a further analysis to chart the previously mentioned variables has been performed.
2. A very important part of how well an NFT is performing is the difference in Mint and Secondary sales. To help the user with this variable, a log scale line chart with total and average sales for Mint and Secondary sales has been developed. For easy access to the time series graphs, the start data, end date and the type of sale can be customized by the end user of the dashboard.
3. We then proceed on to see the sales of NFT categorized by the player name over a period of time. This has been completed with the help of an animated bar chart, provided in Flipside. With the help of this bar chart we can see 3 variables at one time, and the selection of time is upto the end user of this dashboard. 

## Comparative Analytics 📊
1. A comparative analysis is then done on the sales count of the NFTs based on the type of world cup (that are Mens World Cup and Womens World Cup) and which years' NFTs were sold the most.

## Top🔟 - A fun and engaging way for the user to find insights about the NFT collection 
1. Three CTEs were created in the query, namely highest_sold, least_sold, first_sold, latest_sold. These views will help to create a customizable experience for the user. The end user can select among the previously mentioned 4 variables and find the answer. As simple as that.
2. The some values such as the total sales amoung in USD, the image, the drop name and many others are displayed to provide more thorough information. 

# Findings 👀
1. 4 collections have been released in FIFA Collect and a total of 0.745M NFTs have been released in these collections
2. The names of the collections are Genesis, Archives, South American Flair and Archives 2
3. In terms of volume and number of buyers the Genesis collection has been the most prominent
4. The Genesis collection has 606.71k number of NFTs, 14.078k purchasers and clocked in 1.38M USD in total sales
5. The sales volume peaked on 08th October 2022 with a sales volume of 72.066K and touched the lowest point on 18th October with a meagre sales volume of 4324
6. The total secondary sales were at the highest on 08th October 2022 (18.22K USD) and were the lowest on 18th October 2022 (1.4K USD)
7. The total mint sales also peaked om 08th October 2022 with a value of 119.251K USD and saw touched the bottom of the barrel on 18th October 2022 with just a sale number of 7065 USD
8. As the FIFA+ Collect NFTs started, Jo Hyeonwoo had the largest sale of 2.34K followed by Sophie Schmidt and Hassan Rowshan. As per 23rd November, Sun Wen has the highest NFTs sold for that day with a sale number of 16 followed by Cristiano Ronaldo with a sale count of 15
9. NFTs covering the Mens World Cup has sold 186% more NFTs that the Womens World Cup
10. The NFTs which covered the year 2018 sold the most with a count of 89.119K followed by the year 1994 with 84.032K number of sales
