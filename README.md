# _Neural_Network_Charity_Analysis_

## Purpose of the analysis 

With the abilities of machine learning and neural networks, we will use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing

- The model has a variable that is considered the target if a given company is successful, or the "IS_SUCCESSFUL" column.
- We removed the "EIN" and "NAME" columns as they did not offer any relevant information for our analysis because they would not be helpful in making predictions as we can not draw any evident conclusions from an ID number or the name of the organization.
- All other variables are used as features.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

- For the first attempt at this the model, we considered 8 neurons in the first layer and 5 in the second, they both had a 'relu' activation function, since relu does a good job with nonlinear data, and the output layer had a sigmoid activation function since the outcome is binary in this case (successful or not successful)

Were you able to achieve the target model performance?

- The Accuracy of the first model is 72.34%. Hence the model did not achieve the intended performace level. 

![alt text](https://github.com/Yoditatr/Neural_Network_Charity_Analysis/blob/main/Resources/fit.PNG?raw=true)

## Summary 

Overall, the model was unsuccessful in achieving the 75% target predictive accuracy. With an initial accuracy of 72.34% and a second optimization of 71.8%. The next step could be looking into the dataset to figure out if there are any outliers. 

![alt text](https://github.com/Yoditatr/Neural_Network_Charity_Analysis/blob/main/Resources/optimization.PNG?raw=true)
