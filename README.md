# Machine Learning on AWS

This is summary of workshop that is held on [Eventbrite](https://www.eventbrite.com/o/chris-fregly-10652590787).

AWS has a number of machine learning and artificial intelligence services and products that can be used in conjunction with each other to make smart applications. 

## In the first [notebook](https://github.com/VictoriaMaslova/Machine-Learning-on-AWS/blob/main/Introduction%20AWS%20SageMaker.ipynb) I learned how to:

* Create S3 bucket
* Update IAM Roles and Policies, for example, ```AmazonS3FullAccess```, ```AdministratorAccess```, ```AmazonComprehend```, ```AmazonAthenaFullAccess```, ```AmazonRedshiftFullAccess```, ```Amazon Athena```
* Handle some common errors such as Client Errors

## In the second [notebook](https://github.com/VictoriaMaslova/Machine-Learning-on-AWS/blob/main/AutoML.ipynb):

* I applied AutoML using Amazon SageMaker Autopilot for Efficient Preparing Dataset for Model Training and Evaluating 
* Learned how to:
  * Launch the SageMaker Autopilot Job
  * Track the Progress of the Autopilot Job
  * Review the SageMaker Processing Jobs
  * Implement Feature Engineering step
  * Train and Evaluate Model
  * Explore the Best Candidate (pipeline evaluations with different hyperparameter combinations)
  * Deploy the Model as a REST Endpoint
  * Test the Model with Some Example Reviews
