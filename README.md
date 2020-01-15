# Basic-stock-prediction-using-ML-models-SVM-LR
-> Read the data and define adj.close column to the variable
-> We have to predict the next 30 days price so we set forecat_out as 30
-> In predict variable we will fill the next 30 days data and at the end there will be 30 days with NaN value.Now we have to find the that 30 days value
-> For that we will load the adj.close  and predict cloumns in train and test 
-> After training we will declare other variable and we will load last  30 days of adjust.close column
-> Now we will send that variables to our model which is already train with adj.close and we will predict the last 30 days data also 
-> Here we use two algorithms which lLinear regression and support vector regression 
