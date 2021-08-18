
# Store Sales Predictions

Store sales prediction aims at accurately predicting sales of particular items based on features like weight,price and also location at which it is been sold like a supermarket or a retail shop.This software system will be a Web application.This can be used by the warehouse management to forecast the sales for each of their items and take business decision accordingly 


## Steps taken to deliver end-to-end product

1. Performing EDA on the dataset to first understand every aspect of it.

2. Start designing the pipeline which will automate the process of data cleaning,data preprocessing,feature engineering,feature selection,transformation and scaling.

3. Once ready we perform train and test split and feed the training data to 3 separate models.

4. Using Gridsearchcv we get best model evaluated on our test set and we save that model.

5. This process is designed a pipeline and can be retrained anytime with necessary changes.

6. This model is using Flask API and is deployed on AWS EC2 & HEROKU.

7. User queries are stored within cassandra Nosql database which can be used later for retraining.

8. Logs are maintained in separate files for training and database operations

  
## Deployment

Heroku: food-preds.herokuapp.com

AWS EC2 : ec2-3-144-36-208.us-east-2.compute.amazonaws.com:8080/



  
## User interface for store sales prediction


![Annotation 2021-08-18 173818](https://user-images.githubusercontent.com/54542692/129899236-5086d0df-5254-47b8-9900-777cf422d504.png)

ABOUT 

![Annotation 2021-08-18 180828](https://user-images.githubusercontent.com/54542692/129899455-e15c03ee-03f9-424a-ada6-065bae355295.png)

FORM

![Annotation 2021-08-18 181005](https://user-images.githubusercontent.com/54542692/129899572-880dea21-2957-4fec-8e9a-ffdc5d2d3ce8.png)




  
## User Interface for Store Sales Predictio
