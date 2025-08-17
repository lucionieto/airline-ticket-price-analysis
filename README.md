# airline-ticket-price-analysis
## Dataset (India domestic routes)
- Rows: ~N (fill in)
- Features: 11 (6 categorical, 2 numeric + target)
- Scope: Flights between 6 Indian cities across 6 airlines
- Target: `price` (INR)
- Key features: `class`, `airline`, `source_city`, `destination_city`, `departure_time`, `arrival_time`, `stops`, `duration`, `days_left`
- Caveats: Scraped snapshot; binned time labels; no baggage/refundability fees



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




