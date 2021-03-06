# Neural_Network_Charity_Analysis

## Overview: 
The purpose of this module was to build a model that would help a non-profit evaluate its past investments and grants in order to help them determine future investments and grants. 

## Results: 
What variable(s) are considered the target(s) for your model?
- We built a binary model which would help us determine in a 1 or 0 (yes or no) of an investment or grants was successful based on a number of features in our dataset. The featurs that we looked at were type of application, affiliation, classification, use case, organization, status, the organization's income amount. We removed both the name and ID column as this is not trainable data for our model. 


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I used three layers for my model with layer one having 24 nuerons, level 2 having 12 nuerons, and level 3 having 6 nuerons. 
- Used tanh activation.
- my reasoning behind landing on this setup for my model was simple trial and error. I had initially used a Relu activation with only two hidden layers which resulted in an Accuracy of: 0.7268804907798767. I then tried to optimize by model by adding another hidden layer with 6 nuerons and changing the activation sytem. After the adjustments the Accuracy was: 0.7278134226799011

Were you able to achieve the target model performance?
- After building our model we were not able to reach the 75% accuracy threshold, meaning that our model did not reach our target performance. 

<img width="385" alt="Screen Shot 2021-06-27 at 10 20 02 PM" src="https://user-images.githubusercontent.com/75695931/123570338-00000680-d796-11eb-807d-66c7881d13f9.png">

<img width="715" alt="Screen Shot 2021-06-27 at 10 19 56 PM" src="https://user-images.githubusercontent.com/75695931/123570339-00000680-d796-11eb-93f5-3db1e182e27a.png">

## Summary:
After doing what I could to try and improve the accuracy of the model I was not able to hit our target of 75%, so I might not suggest that the nonprofit trust my model entirely. That being said the model could give them a rough understanding of their past investments and grants so it is worthwile to consider. One angle that I did not consider, which could be a good way to improve the accuracy of the model is to run a random forest classifier on the data. Because the random forest classifier is not as strict and does not need to be tuned up as much it might lend itself more to our dataset due to the features and data we have in the csv. 
