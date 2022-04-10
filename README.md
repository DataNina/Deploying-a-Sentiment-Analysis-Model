# Deploying-a-Sentiment-Analysis-Model

### Hint
This project was completed as part of Udacity's nanodegree program 

### Goal 
The notebook and Python files provided generate  a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. Making use of SageMaker to construct a complete project from end to end, this project aims at having a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

### Instructions
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6 (again): Deploy the model for the web app
- Step 7 (again): Use the model for the web app
- Libraries

Necessary libraries:
Amazon SageMaker (Build, train, and deploy a model)
PyTorch (LSTM classifier)

Important note:
Remember to always SHUT DOWN YOUR ENDPOINT if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.

	predictor.delete_endpoint()
