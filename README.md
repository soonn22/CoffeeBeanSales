# Coffee Bean Sales in Saudi Arabia in 2023 and 2024 Data Analysis ##
----------------------------------------------
## Data Resource
Data set was downloaded from Kaggle. you can find the data [here.](https://www.kaggle.com/datasets/halaturkialotaibi/coffee-bean-sales-dataset)\
The data contains sales, amount and discount of data of coffee bean in 10 cities in Saudi Arabia from 2023 and 2024.

## Purpose and Tasks
The main goals of this analysis to build a model to predict final sales of coffee beans in Saudi Arabia and find the impact of discounts.

## EDA summary
1. top 3 big customers: Found outliers of final sales
and this tells us that there are
three customers who purchase
more than other.

2. Sales trends: Coffee bean sales fluctuate yearly,
rising early in the year, dipping in
spring, increasing in summer, and
dropping again. The decline from
March to April may be linked to
Ramadan, which influences
consumption patterns.

4. City has difference preference
of products such as, Guatemala
for Hail and Costa Rica for
Riyadh.


## Building a model

1. An analysis was conducted to
evaluate the impact of discounts
on quantity and sales. However, it
was not possible to construct a
reliable model with the given
variables, as the results showed
a low AUC score and poor
performance metrics, including
accuracy, recall, and precision, all
around 0.55

2. The multivariate linear regression
model, incorporating two
variables—quantity and sales
amount—was developed to
predict final sales. Although the
model achieved a high R-squared
value of 0.95, it failed to satisfy
key assumptions, particularly
linearity


## Conclusion
The model building process was ultimately unsuccessful. Recognizing the limitations of the given data, I sought open data sources related to coffee sales in Saudi Arabia from 2023 to 2024 but was unable to locate relevant datasets. Given this situation, I recommend collecting additional data to enhance the modeling process. Specifically, collecting sales/inventory data, market/customer data, and geographic/location data could prove valuable for building better predictive models in the future.

## Data examples
1. Sales and Inventory Data\
- Historical Inventory Levels: Add information on past inventory amounts and stock-outs to capture supply-demand dynamics.\
- Waste/Expiration Data: Include the number of products that spoiled or went unsold to refine inventory predictions.\
- Sales Time Data: Record timestamps more granularly (e.g., daily/hourly sales) to account for short-term trends.\

2. Market/Customer Data\
- Promotions/Events: Track promotional activities and local events, which could impact sales spikes.\
- Customer Feedback: Add review/rating data or customer preferences for specific products\

3. Geographic/Location Data\
- Foot Traffic: If sales locations are physical stores, include data on customer foot traffic\
- Regional Patterns: Consider adding broader regional economic indicators, such as population or income\


