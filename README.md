# GeoAI-Challenge-Estimating-Soil-Parameters-from-Hyperspectral-Images-
Can you predict soil parameters from hyperspectral earth observation data?

The objective of this challenge is to automate the process of estimating the soil parameters, specifically, potassium (K), phosphorus pentoxide (P2O5), magnesium (Mg) and pH, through extracting them from the airborne hyperspectral images captured over agricultural areas in Poland (the exact locations are not revealed). To make the solution applicable in real-life use cases, all the parameters should be estimated as precisely as possible.

https://zindi.africa/competitions/geoai-challenge-estimating-soil-parameters-from-hyperspectral-images/data

Experiment1----> use basic dense layers and relu activation, get same output for all input --> not working
Experiment2---> use conv,pooling,dropout multiple times, imporove a liitle --> keep working 
Experiment3---> use LSTM,GRU RNN, run it for 20 epochs --> this model work better
