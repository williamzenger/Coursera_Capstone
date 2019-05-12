
## Real Estate & Venues Data Analysis of Wuxi City, China


#### I. 		Introduction


##### A. Description & Background information


#### II. 	Data Collection
  A.	Data Prepration
  
  1. I'll use python libraries like **Beautiful** and **Requests** to crawl our data and then import them with **'Name', 'Location', 'Address', 'Price'** columns from [BeiKe](https://wx.fang.ke.com/loupan/pg1) into Pandas DataFrame.
  
  2. After conmunication with my frined and searching information online, I have the following features conbination of venues: **'Parks,Supermarkets,Restaurants,Schools,Hospitals,Public Transiptation,Banks(ATM),Theaters'** which will be shown in the url= *'query=公园$超市$美食$学校$医院$公交车站$银行$电影院'* in the report. Their weight are the same.
  
  3. I'll use Baidu Maps 'Place API' to obtain the **Latitude** and **Longitude** information for each apartment and Baidu API *'Place Suggestion API'* to obtain the venues around nearby and import them into pandas dataframe as well.
  
  B.   Data processing
  
  1. Clean the data and remove the rows with prices are too small because some houses are selling not by the price per square.
  
  2. Calculate the average of the price(*mean*) and assign it to some apartments with unknown prices.

#### III. 	Methodology
  1. Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, and what machine learnings were used and why.


#### IV		Results section where you discuss the results.

#### V. 	Discussion section where you discuss any observations you noted and any recommendations you can make based on the results.


#### VI.	Conclusions
