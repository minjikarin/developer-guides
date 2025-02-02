# Free test data collection of Self-Service APIs

Amadeus for Developers offers a `test environment` with free limited data. This allows developers to build and test their applications before deploying them to production. To access real-time data, you will need to move to the [production environment](/docs/API-Keys/moving-to-production.md){:target="\_blank"}.

!!! warning
    It is important to note that the test environment protects our customers and data and it's exclusively intended for development purposes.

### Test vs Production

The test environment has the following differences with the production:

| |**Billing** | **Rate Limits** | **Data** | **Base URL** |
| ----------- | ----------- | ----------- | ----------- |  ----------- |
| **Test**  | Free monthly quota | 10 TPS | Limited, cached | test.api.amadeus.com
| **Production**  | Unlimited | 40 TPS | Unlimited, real-time | api.amadeus.com

Check out the [rate limits guide](/docs/api-rate-limits.md){:target="\_blank"} and [pricing page](https://developers.amadeus.com/pricing){:target="\_blank"} if you want to get more information on the specific topics. In this tutorial you can learn how to build a [mock server](./developer-tools/mock-server.md){:target="\_blank"} in Postman to help you consume less of your free quota.

### API usage

To make sure you don't pass your monthly quota, you can go to **My Self-Service Workspace > API usage and quota** and review how many transactions you've performed. In case you pass the limit, you will need to wait for the new month and your quota will be renewed.

!!! information
    It may take up to 12 minutes to display your most recent API calls.

The table below details the available test data for each Self-Service API:

## Air


| **API**      | **Test data** |
| ----------- | ----------- |
| [Flight Inspiration Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-inspiration-search){:target="\_blank"} | Cached data including most origin and destination cities. |
| [Flight Cheapest Date Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-cheapest-date-search){:target="\_blank"} | Cached data including most origin and destination cities. |
| [Flight Availabilities Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-availabilities-search){:target="\_blank"}  | Cached data including most origin and destination cities/airports. |
| [Airport Routes](https://developers.amadeus.com/self-service/category/air/api-doc/airport-routes){:target="\_blank"} |  Static dataset containing all airport routes in November 2021. |
| [Airline Routes](https://developers.amadeus.com/self-service/category/air/api-doc/airline-routes){:target="\_blank"} |  Static dataset containing all airport routes in November 2021. |
| [Flight Offers Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-offers-search){:target="\_blank"} |  Cached data including most origin and destination cities/airports. |
| [Flight Offers Price](https://developers.amadeus.com/self-service/category/air/api-doc/flight-offers-price){:target="\_blank"} |  Cached data including most origin and destination cities/airports. |
| [Branded Fares Upsell](https://developers.amadeus.com/self-service/category/air/api-doc/branded-fares-upsell){:target="\_blank"} |  Cached data including most airlines. |
| [SeatMap Display](https://developers.amadeus.com/self-service/category/air/api-doc/seatmap-display){:target="\_blank"} |  Works with the response of Flight Offers Search. |
| [Flight Create Orders](https://developers.amadeus.com/self-service/category/air/api-doc/flight-create-orders){:target="\_blank"} |  Works with the response of Flight Offers Price. |
| [Flight Order Management](https://developers.amadeus.com/self-service/category/air/api-doc/flight-order-management){:target="\_blank"}  | Works with the response of Flight Create Orders. |
| [Flight Price Analysis](https://developers.amadeus.com/self-service/category/air/api-doc/flight-price-analysis){:target="\_blank"} |  No data restrictions in test. |
| [Flight Delay Prediction](https://developers.amadeus.com/self-service/category/air/api-doc/flight-delay-prediction){:target="\_blank"} | No data restrictions in test. |
| [Airport On-time Performance](https://developers.amadeus.com/self-service/category/air/api-doc/airport-on-time-performance){:target="\_blank"} |  No data restrictions in test. |
| [Flight Choice Prediction](https://developers.amadeus.com/self-service/category/air/api-doc/flight-choice-prediction){:target="\_blank"} | No data restrictions in test. |
| [On Demand Flight Status](https://developers.amadeus.com/self-service/category/air/api-doc/on-demand-flight-status){:target="\_blank"}  | Cached data including most flights returned by Flight Offers Search. |
| [Flight Most Traveled Destinations](https://developers.amadeus.com/self-service/category/air/api-doc/flight-most-traveled-destinations){:target="\_blank"} |  See list of [origin and destination cities/airports](https://github.com/amadeus4dev/data-collection/blob/master/data/ti.md){:target="\_blank"}. |
| [Flight Busiest Traveling Period](https://developers.amadeus.com/self-service/category/air/api-doc/flight-busiest-traveling-period){:target="\_blank"} |  See list of [origin and destination cities/airports](https://github.com/amadeus4dev/data-collection/blob/master/data/ti.md){:target="\_blank"}. |
| [Flight Most Booked Destinations](https://developers.amadeus.com/self-service/category/air/api-doc/flight-most-booked-destinations){:target="\_blank"} |  See list of [origin and destination cities/airports](https://github.com/amadeus4dev/data-collection/blob/master/data/ti.md){:target="\_blank"}. |
| [Airline Code Lookup](https://developers.amadeus.com/self-service/category/air/api-doc/airline-code-lookup){:target="\_blank"} |  No data restrictions in test. |
| [Airport & City Search](https://developers.amadeus.com/self-service/category/air/api-doc/airport-and-city-search){:target="\_blank"} |  Cities/airports in the United States, Spain, the United Kingdom, Germany and India. |
| [Airport Nearest Relevant](https://developers.amadeus.com/self-service/category/air/api-doc/airport-nearest-relevant){:target="\_blank"}  | Cities/airports in the United States, Spain, the United Kingdom, Germany and India. |
| [Flight Check-in Links](https://developers.amadeus.com/self-service/category/air/api-doc/flight-check-in-links){:target="\_blank"} |  See list of [valid airlines](https://github.com/amadeus4dev/data-collection/blob/master/data/checkinlinks.md){:target="\_blank"}. |


## Hotel


| **API**      | **Test data** |
| ----------- | ----------- |
| [Hotel Search](https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-search){:target="\_blank"} |  See list of [valid hotel chains](https://github.com/amadeus4dev/data-collection/blob/master/data/hotelchains.md){:target="\_blank"}. Test with major cities like `LON` or `NYC`. |
| [Hotel Booking](https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-booking){:target="\_blank"} |  Works with the response of `Hotel Search`. |
| [Hotel Ratings](https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-ratings){:target="\_blank"} |  See list of [valid hotels](https://github.com/amadeus4dev/data-collection/blob/master/data/hotelratings.md){:target="\_blank"}. |
| [Hotel Name Autocomplete](https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-name-autocomplete){:target="\_blank"} | Cached data including most hotels available through Amadeus |


## Destination Content

| **API**      | **Test data** |
| ----------- | ----------- |
| [Safe Place](https://developers.amadeus.com/self-service/category/destination-content/api-doc/safe-place){:target="\_blank"} |  See list of [valid cities](https://github.com/amadeus4dev/data-collection/blob/master/data/pois.md){:target="\_blank"}. |
| [Travel Restrictions](https://developers.amadeus.com/self-service/category/destination-content/api-doc/travel-restrictions){:target="\_blank"} | Cached data for all available countries/cities. |
| [Points of Interest](https://developers.amadeus.com/self-service/category/destination-content/api-doc/points-of-interest){:target="\_blank"} | See list of [valid cities](https://github.com/amadeus4dev/data-collection/blob/master/data/pois.md){:target="\_blank"}. |
| [Location Score](https://developers.amadeus.com/self-service/category/destination-content/api-doc/location-score){:target="\_blank"} |  See list of [valid cities](https://github.com/amadeus4dev/data-collection/blob/master/data/pois.md){:target="\_blank"}. |
| [Tours and Activities](https://developers.amadeus.com/self-service/category/destination-content/api-doc/tours-and-activities){:target="\_blank"} |  See list of [valid cities](https://github.com/amadeus4dev/data-collection/blob/master/data/pois.md){:target="\_blank"}. |


## Trip

| **API**      | **Test data** |
| ----------- | ----------- |
| [Trip Parser](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-parser){:target="\_blank"} |  No data restrictions in test. |
| [Trip Purpose Prediction](https://developers.amadeus.com/self-service/category/trip/api-doc/trip-purpose-prediction){:target="\_blank"}  | No data restrictions in test. |
| [Travel Recommendations](https://developers.amadeus.com/self-service/category/trip/api-doc/travel-recommendations){:target="\_blank"}  | No data restrictions in test. |
| [City Search](https://developers.amadeus.com/self-service/category/trip/api-doc/city-search){:target="\_blank"}  | No data restrictions in test. |




