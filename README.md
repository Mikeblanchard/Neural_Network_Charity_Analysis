# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis was to determine the success of organizations that have been funded by Alphabet. We will be preprocessing the data, then compile, train and evaluate the model, then finally optimize it.

## Results
### Data Preprocessing
Our focus was on the "IS_SUCCESSFUL" column of the data, for obvious reasons. We dropped columns:

- "EIN"
- "NAME"

Because we felt they did not affect our outcome. Everything else was considered. 

### Compiling, Training and Evaluating the model. 

Our first iteration had 80 and 30 neurons in 2 hidden layers. We used Relu and Sigmoid activation two layers. 

![](https://github.com/Mikeblanchard/Neural_Network_Charity_Analysis/blob/main/Resources/neural.png)
![](https://github.com/Mikeblanchard/Neural_Network_Charity_Analysis/blob/main/Resources/neural1.png)

We achieved a target proformance of around 72%, not quite getting to 75%, as expected. We added additional hidden layers in effort to do so.

![](https://github.com/Mikeblanchard/Neural_Network_Charity_Analysis/blob/main/Resources/neural3.png)
![](https://github.com/Mikeblanchard/Neural_Network_Charity_Analysis/blob/main/Resources/neural4.png)

## Summary

The models accuracy ended up being 72.3% - we started with a data set and tried to predict whether or not the project would be successful on all of the features that we used after dropping two features that we figured to be irrelevant. Although we did not get to the accuracy of 75% desired, it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data, if add more solid data to this model, the accuracy of this model will be much more concrete and accurate. 
