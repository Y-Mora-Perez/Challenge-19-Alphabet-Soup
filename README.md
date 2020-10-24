# Challenge-19-Alphabet-Soup

Build a machine learning model that will predict the success of a venture paid by Alphabet Soup to ensure funding.


_**How many Neurons and layers did you select for your neural network model?**_

The number of input features equal to the number of variables were added in the feature DataFrame. 
There were two hidden layers; the first with 8 neurons and the second layer with 5 neurons. 
Each input layer used the ReLu activation function and the output layer used the sigmoid activation function. 
The sigmoid function is helpful to predict whether the applicant will be successful if funded by Alphabet Soup. 

 _**Were you able to achieve target model performance of 75%? What steps did you take to try and increase model performance?**_
 
The target model performance of 75% was not met.

  **I took three steps to increase model performance.**
  
  - The first step was to add neurons to my hidden layers. I increased the first hidden layer to 12 neurons and increased the second hidden layer to 6 neurons. This produced a model that could predict accuracy at 72.93%
  - The second step I took was to add a third hidden layer. I kept the first two hidden layer neurons at 12 and 6, then added a third hidden layer with 3 neurons. This decreased neurons in each hidden layer by half. This model could predict accuracy at 72.64%
  - The third optimization step I took was to change the activation function in hidden layers. I reverted back to two hidden layers with 8 and 5 neurons respectively. I also changed the input layers to sigmoid activation. This produced an accuracy of 72.58%. 
  
 Overall, all three models were remarkably close in accuracy but the model with 3 hidden layers was marginally better at 72.64%. 

_**If you were to implement a different model to solve this classification problem, which would you choose and why?**_

Random forest classifiers are a type of ensemble learning model that combines multiple smaller models into a more robust and accurate model. They use several learner algorithms and combine their output to make a final classification decision. Random forest models have been popular in machine learning algorithms for many years due to their robustness and scalability. Both output and feature selection of random forest models are easy to interpret, and they can easily handle outliers and nonlinear data. So Random forest classifiers would be my next option. 
