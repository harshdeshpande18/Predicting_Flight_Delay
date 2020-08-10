# Predicting_Flight_Delay
Analysing the Duration and Factors affecting Delay of Flights of 6 Major Airlines on 5 Major Routes connecting 5 Major Cities in India and Devising an Algorithm to Predict Flight Delays of Next Journeys.
# **Flight-Delay-Prediction**

Flight Delay Prediction: Building a predictive model analyzing flight delay in Indian Airlines by preparing data from scratch using APIs (JSON) web scraping methods. Further engineering the data and using Machine Learning algorithms to predict flight delay time. The trained model can be used to predict the flight delay in new test sets. .

**Data**

Dataset has been prepared by from scratch by scraping and parsing Indian flight websites (namely Indigo, Air India, SpiceJet, GoAir, AirAsia) using the python package BeautifulSoup.
 Size of dataset: (10718, 29)

**Features**

1. Used Date: Date of departure
2. From: Deaparture place
3. To: Arrival place
4. Airline: Name of the Indian airline
5. Scehduled Departure: Time of scheduled departure
6. Departure: Actual time of departure
7. Scheduled Arrival: Time of scheduled arrival
8. Arrival: Time of actual arrival
9. Distance: Flight distance between departure and arrival point
10. Airline Rating: Average airline ratings (as quoted by [www.airlineratings.com](http://www.airlineratings.com/))
11. Weather attributes:
 a) weather\_\_hourly\_\_windspeedKmph
 b) weather\_\_hourly\_\_precipMM
 c) weather\_\_hourly\_\_humidity
 d) weather\_\_hourly\_\_visibility
 e) weather\_\_hourly\_\_pressure
 f) weather\_\_hourly\_\_cloudcover

**Machine Learning Used**

Dataset.csv was trained on two Machine Learning Models: RandomForestRegressor and XGradientBoost and the python code is stored in FLIGHT DELAY.ipynb and FLIGHT DELAY.py files.

**Dependencies**

- NumPy
- Pandas
- Matplotlib
- Scikit-learn
