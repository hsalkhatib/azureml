## Azure ML Tutorial

#### Register for a Microsoft ID at : http://login.live.com

#### Login to https://studio.azureml.net


#### ML Workflow

1. Create a new blank ML experiment
2. Add a Reader and link to URL https://raw.githubusercontent.com/pujari/azureml/master/titanic-passengers.csv
2. Add a Metadata Editor to map categorical features.
3. Clean up missing data - e.x. replace numbers by mean/median etc.
4. Project Columns - exclude columns that are not used for prediction.
5. Split data into Training and Validation
6. Add a TrainModel and use any two class algorithm to predict the model.
7. Add competing models if needed
8. Score model(s)
9. Evaluate model(s)

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML1.jpg).

#### ML Web Service Flow

10. Save a copy of the original workflow. 
11. Add Project Columns to remove output parameter (predicted value).
12. Extract the trained model. 
13. Add Web service inputs and outputs.
14. Publish Web Service

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML2.jpg).

#### ML Web Service Test Input

15. Test the web service and provide the inputs

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML3.jpg).

#### ML Web Service Test Output

15. View the prediction results

![alt tag](https://github.com/pujari/azureml/blob/master/TitanicML4.jpg).
