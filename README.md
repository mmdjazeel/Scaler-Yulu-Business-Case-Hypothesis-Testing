# Scaler-Yulu-Business-Case-Hypothesis-Testing

### About Yulu

Yulu is India's leading micro-mobility service provider, offering innovative vehicles for daily commuting. Initially launched to address traffic congestion, Yulu provides a safe, user-friendly, and sustainable commute option via a mobile app for shared, solo journeys. Yulu zones are strategically located at key points such as metro stations, bus stands, offices, and residential areas to make first and last-mile travel smooth, affordable, and convenient.

### Business Problem

Recently, Yulu has experienced a significant decline in revenues. To address this, they have hired a consulting firm to analyze the factors influencing the demand for their shared electric cycles in the Indian market. The primary goal is to identify the variables that significantly impact demand and understand how well these variables explain the overall demand for Yulu's electric cycles.

### How You Can Help

The company needs insights on:

- Which variables are significant in predicting the demand for shared electric cycles in India?
- How effectively these variables describe the demand for electric cycles.

### Dataset

The dataset includes various features relevant to the demand for Yulu's electric cycles. 

Dataset Link: [yulu_data.csv](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089)

**Column Profiling:**

- **datetime:** Date and time
- **season:** Season (1: spring, 2: summer, 3: fall, 4: winter)
- **holiday:** Whether the day is a holiday (sourced from the [DC HR holiday schedule](http://dchr.dc.gov/page/holiday-schedule))
- **workingday:** Whether the day is a working day (1 for working days, 0 for weekends/holidays)
- **weather:**
  - 1: Clear, Few clouds, partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds
  - 3: Light Snow, Light Rain + Thunderstorm
  - 4: Heavy Rain, Ice Pellets, Thunderstorm, Snow + Fog
- **temp:** Temperature in Celsius
- **atemp:** Feels-like temperature in Celsius
- **humidity:** Humidity level
- **windspeed:** Wind speed
- **casual:** Count of casual users
- **registered:** Count of registered users
- **count:** Total count of rental bikes (casual + registered)
