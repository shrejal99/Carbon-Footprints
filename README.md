<p align="center">
  <img src="https://user-images.githubusercontent.com/84700316/136971993-760696ce-75b3-461c-bc88-31f5d4534998.jpg">
  </p>

<h1 align="center"> Carbon Footprint </h1>
<p align="center">Calculate your carbon footprint easily using a command line interface. </p>


## Getting started

First, clone the repository:

Now install all the dependencies:

```
pip3 install -r requirements.txt 
```

Now run the script 

```
python3 carbon_footprint.py
```

You can then answer all the questions provided:


After this, a  PDF report will pop up with your results.

## Assumptions in carbon footprint 
### Electricity:
- Electric bill - 11,698 kwh/year = average energy consumption / household.
- the U.S. average is 13.27 cents per kilowatt hour (kwh), 0.62 kilogramCO2 / kwh.
- 11,698 kwh/year * 0.62 kgCO2/kwh = 7,252.76 kg CO2/year.
### Flights per year:
- Flights per year - average is 2.1 trips per American (if fly).
- Assume 0.1304 kgCO2/km for medium-term flights (DEFRA model).
- Domestic flights ~2.5-3 hr, 2200km * 0.1304 kgCO2/km * 2.1 trips = 602.448 kg CO2/yr.
### Transportation:
- Average American drives around 15,000 per year (assume this is all forms of ground transport).
- Fuel efficiency on car - assume 30 mpg on road car now.
- 0.960 pounds = 0.435 kg CO2 per mile (driving) * 15,000 miles/year = 6,525.0 kg CO2 / year. 
- 0.657 pounds = 0.298 kg of CO2 per mile - 50% public transport, 50% single auto * 15,000 miles/year = 4470.0 kg CO2 /year.
- 0.354 pounds = 0.161 kg of CO2 per mile (public transportation) * 15,000 miles / year = 2,415.0 kg CO2 / year.
### Uber trips:
- (14 uber million trips / day * 0.50)9 / 325 million people (USA) * 365 days / year = 7.86 rides/person in the USA (assumes 50% of all uber rides are in the USA).
- Average ride length = 6 miles/trip * 7.86 trips / person / year * 0.960 kgCo2/mile = 45.27 kg Co2/uber rider/year.
### Food choices / nutrition:
- 1.7 US tons = 1,542.21406 kilograms of CO2/year - vegetarian.
- 2.5 US tons = 2,267.96185 kilograms of CO2/year - average.
- 3.3 US tons = 2,993.70964 kilograms of CO2/year - meat lover.
### Amazon supply chain:
- 0.1289 kg CO2e per dollar (USD).
- 3,300,000 boxes/day13 * 365 days/year / 325,000,000 Americans = 3.70 boxes/American.
- 3.70 boxes/year * $47 / box = ~$173.90/year * 0.1289 kg / $1 USD= 22.41 kg CO2/year.

## Getting involved
Here are some ways you can get more involved:

* register an account @ [Protea.Earth](http://start.protea.earth), a social network community designed to reduce your carbon footprint.
* give some feedback on this repository by opening up a [GitHub issue](https://github.com/protea-earth/carbon_footprint/issues).
* send me an email @ jim@protea.earth; I'm always interested to chat about voice computing and/or climate change!

## References
- [Shrinkthatfootprint.com](http://shrinkthatfootprint.com/average-household-electricity-consumption)
- [Chooseenergy.com](https://www.chooseenergy.com/electricity-rates-by-state/)
- [Quora](https://www.quora.com/How-much-CO2-is-produced-per-KWH-of-electricity)
- [Airlines.org](http://airlines.org/wp-content/uploads/2016/04/2016Survey.pdf)
- [Environmental Change Institute](https://www.eci.ox.ac.uk/research/energy/downloads/jardine09-carboninflights.pdf)
- [Reference.com](https://www.reference.com/vehicles/average-mileage-put-car-year-5c8f88fa02be73c8)
- [Wikipedia](https://en.wikipedia.org/wiki/Corporate_average_fuel_economy)
- [Tranistscreen.com](http://blog.transitscreen.com/how-public-transit-can-and-must-help-reduce-carbon-pollution)
- [Businesofapps.com](https://www.businessofapps.com/data/uber-statistics/)
- [Ride.guru](https://ride.guru/lounge/p/what-is-the-average-trip-distance-for-an-uber-or-lyft-ride)
- [Shrinkthatfootprint.com](http://shrinkthatfootprint.com/food-carbon-footprint-diet)
- [AboutAmazon.com](https://sustainability.aboutamazon.com/carbon-footprint)
- [Quora](https://www.quora.com/How-many-boxes-does-Amazon-ship-every-day)
