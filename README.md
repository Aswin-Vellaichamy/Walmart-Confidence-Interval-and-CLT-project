# Walmart - Confidence Interval and CLT
A scaler case study under which explored the Walmart dataset to gather insights on customer purchase pattern.

# About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

# Dataset 

- Datetime: datetime
- Season: season (1: spring, 2: summer, 3: fall, 4: winter)
- Holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
- Weather:
- 1: Clear, Few clouds, partly cloudy, partly cloudy
- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- Temp: temperature in Celsius
- Atemp: feeling temperature in Celsius
- Humidity: humidity
- Windspeed: wind speed
- Casual: count of casual users
- Registered: count of registered users
- Count: count of total rental bikes including both casual and registered
- 
# Business Problem

The company wants to know:

- Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
- How well those variables describe the electric cycle demands
