# FYP-Genome_Modelling
 
This repository contains files used in my final year project for an MEng in Engineering Mathematics at the University of Bristol. This collection is unfortunately incomplete as a large proportion of the scripts used to generate results were stored on the University's HPC system, *Blue Crystal* 4, which I since have lost access to.

Will preface this by saying that since these are all my locally stored versions of scripts, they were generally used for testing of concepts and therefore are quite messy and in parts difficult to follow. I have made efforts to comment and explain things but send me an email if you are having trouble.

## Code

### Data manipulation

#### csv.ipynb - 
this file was just for testing out how to manipulate the data and understand how to extract the information I wanted from it.

### lstm

#### lstmtest.ipynb - 
follows https://www.tensorflow.org/tutorials/structured_data/time_series notebook on time series forecasting using neural network models in Tensorflow. This is an early version of the lstm model that doesn't produce great results but shows the overall structure of how it was used. 

## rf

#### combo.ipynb - 
Bringing ARIMA and RF models together to predict cell division on forecasted data


#### arimaClassification.csv and testClassification.csv - 
were made using the RF model on ARIMA forecasts and original data. The 'class' column is the RF binary predictions on whether the cell divides (1) at this point. (RF trained on full dataset of knockout data on BC4)

#### timeseriestest.ipynb - 
this is mostly testing for the ARIMA model but there is a key part in cell 20-86(?) that produces the output CSV of ARIMA predictions used for the combination model with RF. 

#### wildtypeplotting.ipynb - 
Making plots with and trialling ARIMA on wild-type data