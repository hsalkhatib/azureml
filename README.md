## Azure ML Tutorial

#### ML Workflow

1) Add a Reader and link to URL https://raw.githubusercontent.com/pujari/azureml/master/titanic-passengers.csv
2) Add a Metadata Editor to map categorical features.
3) Clean up missing data - e.x. replace numbers by mean/median etc.
4) Project Columns - exclude columns that are not used for prediction.
5) Split data into Training and Validation
6) Add a TrainModel and use a two-class algorithm to predict the model.
7) Add competing models if needed
8) Score and evaluate models.

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML1.jpg)

10) Save a copy of the original workflow. 
11) Extract the trained model. 
12) Add Web service inputs and outputs.
13) Publish Web Service

#### ML Web Service Flow

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML2.jpg)

14) Test the web service and provide the inputs

#### ML Web Service Test Input

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML3.jpg)

15) View the prediction results

#### ML Web Service Test Output

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML4.jpg)
