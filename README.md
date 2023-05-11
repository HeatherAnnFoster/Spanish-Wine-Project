# Spanish-Wine-Project

The business problem for this dataset is the quality of the ratings. I will be investigating how the quality fo the ratings of the wines affect the price of the wine. I will also be looking at the body and acidity of the wine. Those will be compared to the rating of the wine to see if there is a correlation between a rise or fall of those two aspects in comparison with the rating of the wine. This could lead to a deeper understanding of how to make the wine's rating higher, if those two aspects are changed.

The stakeholders would be the wineries that make these wines and resturaunts that purchase these wines. They could also be private investors or buyers for liquid and grocery stores. If the line of distribution is followed, the customer could also be considered a stakeholder because they are the ultimate palate that the winery is trying to entice to buy their product.

The source of the data is from the website Kaggle and was complied from 7,500 different types of wines from Spain. These wines come only from Spain and are not from any other country in the world. However, the regions where the wine comes from is different.

The description of the data is that it is data collected from wineries from across Spain. This data is collected on red wines only. There is a great variety of wine in this dataset. This dataset is looking at the quality of the wine compared to others.

While looking at the scatterplot visualizaton for the two columns of price and rating, I noticed that as the rating went up, the price went up for the wine as well. However, there are wines in every rating that are under $500. One interesting thing was the 4 outliers in the 4.6 and 4.7 ratings. They were close to #3,000 dollars for their bottles of wine. That leads me to wonder if these are a limited edition wine, or if there was extenuating circumstances that lead to the increase in the price, as these are the only two ratings that have a wine that is that expensive. Was there a frost that year? Were these wines endosed by a celebrity? More research would be needed to know the answers to these questions. 

![download](https://github.com/HeatherAnnFoster/Spanish-Wine-Project/assets/126853678/a8169e84-bd8e-406f-b070-25164cfd843d)


If the barplot is looked at, there is an interesting comparison between the acidity of the wine and the body of the wine. As the acidity decreases, even if it is by small amounts, the body increases. This negative relationshp leads me to believe that if I want to try a wine, I would want one that is less acidic and more full bodied. As I am not a wine drinker at all, this information would help me decide what I would wantt to try first in order to get the best quality for my money.

![download](https://github.com/HeatherAnnFoster/Spanish-Wine-Project/assets/126853678/05c7db2d-f37d-4bcc-861f-2813ec477c84)


The metrics of my best model was the PCA for the Logsitical Regression model.  This model bright back the highest return for the 4.3 rated wine.  It was the highest rating for any of the wines included in this dataset.  It had a 75% positivity rate, showing that 75% of the time, a customer would pick a 4.3 rated bottle.

MY model would solve the business problem well because it was run well.  I used the original Logistical Regression Model and tuned it.  Then I compared it to the Random Forest Models, which were better than the Logistical Regression models.  Once the PCA model was run, that was the best one, so it was chosen to solve this problem.

Looking through the data gathered, I would recommend that the company uses the PCA Logistical Regression Model for their 4.3 rating. This was the highest rating that had the highest positive outcome with all the models used. It returned 75% that a wine would be rated 4.3 from the customers. If we look at the other data, the price point for this wine was constistently lower than the other ratings, with the exception of the 4.2 rating. It was still at a point where a customer like me, who does not drink wine, would feel comfortable spending that money to taste the wine and see if it was the type they would enjoy. That correlation was shown in the "Price v. Ratings" scatterplot.

If further analysis can be suggested, it would be to compare the price of the wine to the cost of making it. Then, compare the cost of the other wines and determine which wine is the most popular, which would be the ratings aspect, and less expensive to produce. The data suggests that the 4.3 rating would be the one that is most popular with wine drinkers. This could lead to the production costs of the 4.3 rated wines to lessen and be produced more.

