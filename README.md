# Introduction
This project tackles the critical challenge of demand forecasting for a food delivery service.  Accurate predictions are essential for managing perishable inventory, minimizing waste, and avoiding stockouts that could drive customers away.  Using a real-world dataset, this repository provides a practical experience in demand forecasting.
### Link to hackathon: [Click here](https://www.analyticsvidhya.com/datahack/contest/genpact-machine-learning-hackathon-1/)
# Problem statement
Your client is a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful. Given the following information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set:  

- Historical data of demand for a product-center combination (Weeks: 1 to 145)
- Product(Meal) features such as category, sub-category, current price and discount
- Information for fulfillment center like center area, city information etc.
# Data dictionary

## Weekly Demand data (train.csv): Contains the historical demand data for all centers, test.csv contains all the following features except the target variable.
<div align='center'>
| Variable|Definition |
|---|---|
| id | Unique ID |
| week | Week No |
| center_id | Unique ID for fulfillment center |
| meal_id | Unique ID for Meal |
| checkout_price| Final price including discount, taxes & delivery charges |
| base_price | Base price of the meal |
| emailer_for_promotion | Emailer sent for promotion of meal |
| homepage_featured | Meal featured at homepage |
| num_orders | (Target) Orders Count |
</div>
# fulfilment_center_info.csv: Contains information for each fulfilment center

