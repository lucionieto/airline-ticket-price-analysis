# airline-ticket-price-analysis

This project explores an airlines flights dataset and builds a machine learning model to predict ticket prices. The analysis covers how different factors — such as airline, source/destination city, travel class, departure/arrival times, and days left before departure — impact flight pricing.  



## Dataset Description  

The dataset contains information on commercial flight bookings between major Indian cities. Each row represents one flight option, with details about the airline, route, class, timing, and price.  

### Features  

| Column            | Description                                                                 | Type        |
|-------------------|-----------------------------------------------------------------------------|-------------|
| **Airline**       | Carrier operating the flight (6 unique airlines).                           | Categorical |
| **Flight**        | Alphanumeric flight code identifying the specific flight.                   | Categorical |
| **Source City**   | City of departure (6 unique cities).                                        | Categorical |
| **Destination City** | City of arrival (6 unique cities).                                       | Categorical |
| **Departure Time**| Time of departure, grouped into 6 categories (Early Morning, Morning, etc.).| Categorical |
| **Arrival Time**  | Time of arrival, grouped into 6 categories.                                 | Categorical |
| **Stops**         | Number of stops (Non-stop, 1 Stop, 2+ Stops).                               | Categorical |
| **Class**         | Ticket class (Economy or Business).                                         | Categorical |
| **Duration**      | Total travel time in hours.                                                 | Numerical   |
| **Days Left**     | Days between booking date and flight date.                                  | Numerical   |
| **Price**         | Ticket price (target variable).                                             | Numerical   |




#Results
### Average Airline Price
![Average Airline Price](figs/Average_airline_price.png)

#### Average Price by Airline and Class
![Average Price](figs/Average_ticket_price_class.png)

### Average price at Departure and Arrival Times
![Arrival & Departure price](figs/Dep_vs_Arr_price.png)

### Average ticket price in days before departure
![Price Before Departure](figs/Average_price_before_departure.png)

### Model Feature Permunation Importance
![Feature Permutation](figs/Feature_importance.png)




