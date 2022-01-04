# Predicting Electricity Outages in Osun, Nigeria
Unreliable power is a common problem among African business and households. Most existing research on power outages has focused on the causes and impacts of outages, rather than patterns in outage occurences. Understanding when, where, and how power outages will occur can assist utilities in preventing outages and planning for more rapid restoration. This project sought to explore hourly outage data obtained for Osun, Nigeria at the distribution feeder level to create predicitve models for power outages in time and space based on previous records, electrical connections, and weather among others.

The project involved gathering various datasets, including power outage data, weather data, transmission line and power plant spatial data, demographic data, and more. Exploratory data analysis was then performed, and the data were cleaned; substantial data cleaning was needed as several datasets contained manually entered data. Models were then developed and tuned to answer three questions, being:
  (1) How many outages will occur on a given day? 
  (2) How long will a given outage last? and 
  (3) Will a power outage occur in a given hour? 

For questions 1 and 2, four different regression models were built and compared, being: ordinary least aquares (OLS), ridge, LASSO, and random forest. For question 1 the Ridge model performed best in terms of MSE, while for question 2, Random Forest outperformed the others. For question 3, three different classifications models were built: boosting, random forest, and support vector machine (SVM). Among these, the random forest had the highest accuracy. 
