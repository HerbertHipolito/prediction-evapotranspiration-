# Evapotranspiration
The reference evapotranspiration(ET0) is an important agrometeorological variable which is
necessary in water and irrigation management, being the focus of many studies worldwide. The
ET0 prediction is a huge challenge once its estimation through the direct methods(lysimeters)
needs special care for use and the main indirect method Penman-Monteith (PM-FAO), recognized
and standardized as one of the best ones in terms of accuracy, demands several climatic variables.
These requirements make PM-FAO unusable for many situations. Therefore, in this paper, I am
going to use one of the most famous and established machine learning algorithms, Artificial
Neural Network(RNA), to predict the ET0 from Ceará by using a data set of 16 weather stations
and setting up the model with only maximum, minimum and average temperature and humidity
as climatic features. Therefore, it is performed 80 simulations in order to discover the most
suited neural network topology and whether just the temperature is enough or not to build a
robust model. Finally, the topology which provided the best outcomes is going to be compared to
another indirect method named Hargreaves-Samani(HS) also uses only temperature as a climatic
variable. The most accurate ANN topology overcame the HS results in the test data set and
obtained a r2 =0.9478 and MSE = 0.0456. Applying the model for each weather station, 10
received smaller MSE and 11 greater r2. Therefore, the RNA is a machine learning algorithm to
be considered in ET0 prediction.


