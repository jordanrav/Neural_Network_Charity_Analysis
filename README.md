# Neural_Network_Charity_Analysis

## Overview

the purpose of this analysis is to see if a Neural Network can predict whether or not a charity will use the money given effectively

## Results

### Data Preprocessing

* the variables that were useless for this analysis were the EIN and the NAME because the identification columns wouldnt lead to a trend to be discovered by the neural network so they were taken out
* the target variable for this analysis was the IS_SUCCESSFUL variable to see whether or not the charity used there money effectively
* the features of this analysis were all the rest of the variables 


### Compiling, Training, and Evaluating the Model

I was not able to reach the target model performance of 75% and was only able to reach about 73% on average. these were the steps i took to try to reach the target model performance

#### Step 1

first i tried to raise the amount of Neurons, and layers and also changed the activation functions to see if this would improve my performance and it did but very slightly

<img width="1133" alt="Screenshot 2023-02-16 at 10 42 44 AM" src="https://user-images.githubusercontent.com/112649072/220656109-29ce3ec3-1f8d-4d44-b2cd-efc69d0c4d49.png">

#### Step 2
the next thing i tried to do was take out variables that didnt seem to be helping. the variable i tried to take out were Special_Considerations and Status because i felt that those variables werent helping much. this improved the model slightly

<img width="1134" alt="Screenshot 2023-02-16 at 10 42 35 AM" src="https://user-images.githubusercontent.com/112649072/220656733-78ce7d2e-f866-4654-ad9a-58dcda71f029.png">

#### Step 3
Finally i tried to change the Epoch value to 500 to see if that were to improve the performance but it only improved slightly

<img width="1124" alt="Screenshot 2023-02-16 at 10 43 51 AM" src="https://user-images.githubusercontent.com/112649072/220657056-91199141-dc56-4af1-8395-052443956b52.png">

## Summary
based on the results I was not able to reach the target model performance of 73% I tried multiple things but they would end up hurting the performance with the three steps above only being the steps that benefited the performance the most. if I were to use another model I think I would use the Random Forest model because I believe that its relatively more easy to use as well as less prone to overfitting.

