# Neural_Network_Charity_Analysis

## Overview
The purpose of this project was to help the Alphabet Soup business team determine which charities to donate to by creating a nerual network. The neural network will help us to determine which of the organizations were successfully funded by Alphabet Soup rather the money going to something other than a charity.

## Results
### Data Processing
The variable that was considered the target for the model was the IS_SUCESSFUL variable as it represented which charity was successfully funded. All of the variables beside the EIN and NAME are the features for the model. I removed the EIN and NAME variable because they do not offer any significant data and did not help the model in any way.

### Compiling, Training, and Evaluating the Model
For the first layer, I used 40 neurons with the tanh function and for the second layer, I used 20 neurons with the tanh function as well. For the outer layer, I used the sigmoid function. With any different attempts are trying to optimize the model, I couldn't get it to perform better than 70%. The last attempt I made with the layers I described just before, the model only performed up to 50%. Anything I tried could not reach or surpass 75%. I tried optimizing the model by changing the number of neurons, the number of hidden layers, and the types of functions used.

## Summary 
After trying what I could to optimize my model, I could not get my model to reach a success point of 75%. In my last attempt, I got it to an accuracy of 50% and a loss of 7.34%. I would recommend using another model to determine which charities were sucessfully funded. The data may have been overfitted using neural networks so finding another model may be the better move for this data set. In additon, it took a good while to run the code so it was not the most effiecient model for trial and error.
