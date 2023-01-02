# Neural_Network_Charity_Analysis

## Overview
In this project, I helped the organization Alphabet Soup to make predictions about where to invest their money. Using knowledge of deep learning and neural networks, I used features in a provided dataset to create a binary classifier that helped predict whether applicants would be successful if they were funded. 

## Results

### Data Preprocessing
- Within the dataset, the target for the model was whether or not an applicant was successful. I wanted to train the model to predict if an applicant would be successful based off of other factors within their application.

- The features of the model included the application type, affiliation, use case, organization, income amount, and special considerations. 

- From the input data, I removed identifying variables such as EIN and name. Additionally, when I tried to improve the model, I removed ask amount from the model because it was a very busy variable that may be confusing the model. 

### Compiling, Training, and Evaluating the Model

- I chose 3 hidden layers and an activation layer for my model. In the first hidden layer, I chose 100 neurons. In the second, 50 neurons. In the third, 25 neurons. I chose the activation function ReLU because it is ideal for looking at posotive nonlinear input data. 

- I was not able to achieve the target model performance. After trying three different methods to optimize my model, I was not able to improve the model's performance.

- To try and increase my models performance I tried removing a busy variable (ask amount), adding a third hidden layer, and increasing the number of neurons in each layer. 

## Summary
Overall, the model resulted in a 72.5% accuracy in predicting if an applicant would be successful if they were given funding from Alphabet Soup. I would recommend changing the input data to include the ask amount by binning it based on amount. By putting that data into bins, it may make it easier for the model to use that data and make a more accurate prediction.



