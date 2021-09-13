# Energy Appliances Prediction
The energy consumption of the world is increasing with time. Being the pure and high-grade form of energy, nowadays’s share of electrical energy in total energy demand is increasing rapidly. Understanding energy usage in the form of electricity has been a subject of various studies. The supply of electrical energy is quite less than the demand. Moreover, electrical energy is to be supplied in real-time as it cannot be stored in its pure form and even if stored in devices such as battery packs, the conversion efficiency of the equipment comes into play. One way to meet the demand is to supply only the real-time required amount of electrical energy. This can be possible if somehow prediction of electrical energy load can be done. Understanding energy use in the form of electricity has been the subject of various studies. One of the significant sectors in electrical energy consumption is appliances. It represents a considerable portion of about 20–30% of the electrical energy demand. Considering the high demand and less supply of electrical energy, it is required to predict energy load. The consumption of electricity in domestic households depends mainly on two factors: the number and type of appliances and their use by the residents. Many factors such as building construction, weather conditions, dry-bulb temperature, wet bulb temperature occupancy, the behavior of occupancy, lighting, heating ventilation, and airconditioning systems, their usage pattern and performance, etc., influence the energy behavior of a building. Considering the complexity of the problem, accurate energy consumption prediction is not an easy task. Traditional analytical methods do not seem to be dominating here, as they become computationally very intensive and also very difficult to consider a huge number of variables. 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Data Discription
The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes (parameters). factors.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Data Attributes
* date - time year-month-day hour:minute:second
* Appliances - energy use in Wh (Dependent variable)
* lights - energy use of light fixtures in the house in Wh (Drop this column)
* T1 - Temperature in kitchen area, in Celsius
* RH1 - Humidity in kitchen area, in %
* T2 - Temperature in living room area, in Celsius
* RH2 - Humidity in living room area, in %
* T3 - Temperature in laundry room area
* RH3 - Humidity in laundry room area, in %
* T4 - Temperature in office room, in Celsius
* RH4 - Humidity in office room, in %
* T5 - Temperature in bathroom, in Celsius
* RH5 - Humidity in bathroom, in %
* T6 - Temperature outside the building (north side), in Celsius
* RH6 - Humidity outside the building (north side), in %
* T7 - Temperature in ironing room, in Celsius
* RH7 - Humidity in ironing room, in %
* T8 - Temperature in teenager room 2, in Celsius
* RH8 - Humidity in teenager room 2, in %
* T9 - Temperature in parents room, in Celsius
* RH9 - Humidity in parents room, in %
* T_out - Temperature outside (from Chievres weather station), in Celsius
* Pressure - (from Chievres weather station), in mm Hg RHout
* Humidity - outside (from Chievres weather station), in %
* Wind speed - (from Chievres weather station), in m/s
* Visibility - (from Chievres weather station), in km
* Tdewpoint - (from Chievres weather station), Â°C
* rv1 - Random variable 1, nondimensional
* rv2 - Random variable 2, nondimensional
