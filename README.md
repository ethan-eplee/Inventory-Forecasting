# Inventory Forecasting

 - [Problem Statement](#Problem-Statement) 
 - [Data Sources](#Data-Sources)
 - [Executive Summary](#Executive-Summary)
 - [Reflections](#Reflections)


## Problem Statement
To accurately predict the stock levels of products based on sales data and sensor data on an hourly basis in order to more intelligently procure products from the client's suppliers

--- 
## Data Sources
The sources of the datasets used in this analysis are provided by the client:
- Sales transaction data, consisting 7800 rows and 9 columns
- Stock levels data from IoT sensors, consisting 15000 rows and 4 columns
- Warehouse temperature data from IoT sensors, consisting 23890 rows and 3 columns

---
## Executive Summary
**INTRODUCTION**

This project is part of Cognizant Digital Business, whose AI and Data Analytics Practice team provides advanced data collection and management expertise, as well as AI and analytics capabilities that help clients create highly personalized digital experiences, products and services at every touchpoint of the customer journey. The project focused on a business case involving a technology-led grocery store chain relying on IoT to collect sensor data. The client wishes to optimize their inventory to make their supply chain more efficient.

**Overview of Project**
- Data processing and cleaning on 3 datasets (sales data, inventory data and temperature sensor data)
- Performed EDA on sales dataset to get insights on customer behaviour
- Cleaned and merged datasets to predict the expected stock level as the target variable
- Used k-fold cross validation on a RandomForestRegressor model
- Evaluated best model on the Mean Squared Error with good generalization
- Used feature importance of ensemble model to interpret the results

**Skills Learnt**
- Using Google Colab to run notebooks to conduct EDA and modelling
- Understanding the data and build a strategic plan to communicate findings with the client
- Preparing a Python module to productionize a ML model
- Learnt tips on how to improve ML models

---
## Reflections
I had the opportunity to step into the shoes of a Cognizant team member for a day and complete tasks that replicate the work done by the AI team. It was refreshing as it provided a real life perspective of what to expect in a working environment, including EDA, communicating results of a ML model, implement algorithm production and to review the algorithm performance. While out of the scope of this project, it would have been interesting to see how to deal with streaming data from actual IoT sensors.  
