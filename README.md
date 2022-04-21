# Wind-Prediction-Visualization-Using-Seaborn


ABSTRACT


Climate is the average state of the atmosphere and related components of earth system. Latitude, distance from sea, presence or absence of mountains or other geographic information determines the climate of a place. Climate models are used to study the behavior, components and interactions of the climate systems. Climate data includes historical as well as real-time data. Machine Learning (ML) is the subset of Artificial Intelligence (AI) which has the ability to learn from 
the training data. This learning experience improves which helps in predicting future values. Mean Wind Speed (MWS) isone important characteristic which influences the climate. Prediction of mean wind speed using ML algorithms is described in this paper. It is useful for determining abnormal weather events and also the future potential for wind energy.

INTRODUCTION


The world’s climates is classified on the basis of Koppen Climate Classification System . There are mainly five types denoted by capital letters: A-Tropical Moist Climates, B - Dry Climates, C - Moist Mid-latitude Climates, D - Moist MidLatitude Climates, E - Polar Climates. The climate of a region is decided by a number of factors like latitude and its influence on solar radiation received, Air mass influences, location of global high and low pressure zones, heat exchange 
from ocean currents, distribution of mountain barriers, distribution of land and sea and altitude, pattern of prevailing winds

Direction of wind is measured in degrees whereas speed of wind is measured in miles per hour. Anemometer is used to measure wind speed and wind vane is another instrument which is used to measure the direction. Both the parameters are used to detect storms, dust storms, hurricanes.

EXISTING TECHNIQUES


John V Neuman in the year proposed the Meteorology Project for developing numerical weather prediction (NWP). The team developed a Binary Electronic Sequence Calculator (BESK) for real time barotropic forecasts. But the duration of forecast was less because the computers didn’t have the capacity to store longer forecast data. Later on capacity of computer was increased. Bert Bolin used this which resulted in extended forecast to cover a large area and also increase in the forecast duration. Analysis of numerical weather map was done after a few years

PROPOSED SYSTEM


Place The proposed system consists of the input data which is obtained from India Meteorological Department, Pune, India. It consists of parameters like sea level pressure, temperature, relative humidity, wind directions etc. Fig.1 shows the basic blocks of the proposed system

Model Diagram:

![image](https://user-images.githubusercontent.com/103196322/164488205-245e2e82-32ca-4e08-a495-989045088ff6.png)

Linear Regression: 

The requirement is to have a relationship between the dependent and independent variables. In this technique a straight line is fitted on the data. It assumes normal distribution of the dependent variable. The dependent variable is the Mean Wind Speed. The independent variables are temperature, pressure, wind direction, precipitation. All values of these independent variables are associated with the dependent variable. Since, the dependent variable is influenced by a number of independent variables so multivariate regression will be applicable here instead of univariate regression

It is formulated as follows:

y = β0+ β1x1+ β2x2+… βnxn+ ε 
y is the dependent variable, βi
is the parameter, xi
is the 
independent variable, ε is the error The error is obtained by the difference between actual and predicted value


CONCLUSION


The goal of Machine Learning is to develop algorithms, automated techniques, to detect patterns in data. The models developed using these techniques can learn from past data and use its learning to predict the future. Climate Models are data driven models built based on solving classification and regression problems

REFERENCES


Pidwirny, M, Climate Classification and Climatic Regions of the World, Fundamentals of Physical Geography, 2nd Edition, 2006. Accessed on: April 10, 2020. 
[Online]. Available:http://www.physicalgeography.net/fundamentals/7v.html


Fondriest Staff , Wind Speed and Direction, August 12,2010. Accessed on: March,11 , 2020. 
[Online]. \Available: https://www.fondriest.com/news/wind-speedanddirection.htm
