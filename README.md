# Electricity-Price-Forecasting

In this project I develop and back test a forecasting model that predicts the wholesale electricity price for the upper North Island of New Zealand

I am doing this from a financial market’s perspective. Using daily data, I averaged the price for the month. This was so I can forecast the next months price. An accurate forecast can be useful to participants buying/selling futures and forward contracts. 
Alongside using auto regressive features (past price affect on future price) I have selected some additional explanatory variables see if they are able to improve the model. These are supply and demand related, and include the following:

Supply:
o	Controlled storage – Hydro makes up approximately 60% of generation, when storage is low during low rain conditions prices are expected to rise. 

o	Gas – Is typically used as a back up supply, so if gas production increases there may be a supply shortage indicating an increase in price.

Demand:
o	Dummy variable for winter months: power demand is typically higher in winter months (Jun – August)

o	Monthly National Demand 
