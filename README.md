# Neural_Network_Charity_Analysis

## Purpose

With our knowledge of maching learning and neural networks. We are using features in a dataset that was provided to create a binary classifier that will be capable of predicting whether applicants will be succesful if funded by Alphabet Soup. In order to develop the machine learning model using neural networks, we preprocess the data, trained and evaluate the model and then optimized the model.

## Results 

## Preprocessing the Data

• We removed multiple variables because they dont add value to our model such as EIN and the name.

• The final feature for the model is as follow, Application Type, Affiliation, Classification, Use Case, Organization, Active Status, Income Amount, Special Considerations, and the Ask Amount.

• Our target for the model is Is_Successful column.

## Compiling, Training, and Evaluating the Model


In our orginal model, We achieved a performance level of 72% which was below the target model of 75%
[![Orginal](https://github.com/mhossain615/Neural_Network_Charity_Analysis/blob/main/A1.png)

I made three different attempts to achieve the target accurancy, First i dropped a column, then i tried increasing nuerons and then i tried adding a hidden layer 


[![Attempt 1](https://github.com/mhossain615/Neural_Network_Charity_Analysis/blob/main/A2.png)


[![Attempt 2](https://github.com/mhossain615/Neural_Network_Charity_Analysis/blob/main/A3.png)


[![Attempt 3](https://github.com/mhossain615/Neural_Network_Charity_Analysis/blob/main/A4.png)


## Summary

 In my first attempt i dropped a column and recieved a 52% which isn't want we need. In my second attempt i increased the number of neurons and got 72% which was still under our target. Our last attempt i added a hidden layer which resulted in 72% as well which was still lower then our target. based on our attempts, Our model only reached up to 72% which fails the target accurancy. Maybe utizlizing a basic supervised machine that can focus on binary classification may be better. 


