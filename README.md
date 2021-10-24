# Neural Network Charity Analysis
## Overview of the Analysis
The purpose of this analysis is to determine, through a robust neural network deep learning model, whether companies that are being donated to by the client will be successful given the new funds.

## Results
### Data Preprocessing
#### What variable(s) are considered the target(s) for your model?
- The variable to be considered as the target output is the IS_SUCCESSFUL column, representing whether the funding toward a certain cause was successful.
#### What variable(s) are considered to be the features for your model?
- Features in the model include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
#### What variable(s) are neither targets nor features, and should be removed from the input data?
- Variables that should be removed from the input data are EIN and NAME.

### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The initial model implemented two hidden layers with 80 and 30 neurons, respectively.
#### Were you able to achieve the target model performance?
- The initial model was not able to achieve target model performance of 75%.
#### What steps did you take to try and increase model performance?
- Steps taken to attempt to achieve increased model performance are as follows:
 -  Increase epochs from 100 to 200
 -  Increase initial hidden layers from 80 & 30 to 110 & 60.
 -  Add an additional hidden layer with 40 neurons.
 -  Regardless, the model was unable to reach an accuracy of the target 75%.

<img width="1100" alt="Screen Shot 2021-10-24 at 1 34 59 AM" src="https://user-images.githubusercontent.com/85330159/138587318-66627901-0117-4e5c-bf09-0081095e1904.png">

<img width="511" alt="Screen Shot 2021-10-24 at 1 37 22 AM" src="https://user-images.githubusercontent.com/85330159/138587324-9370e999-6c05-4207-9482-970d39c84b5d.png">

<img width="1099" alt="Screen Shot 2021-10-24 at 1 59 30 AM" src="https://user-images.githubusercontent.com/85330159/138587327-4f1800b6-5994-448f-9c43-9019825448c5.png">



## Summary
Based on the overall accuracy of the revised model (72.63%) as well as loss (56.16%), the model does not perform exceedingly well. Since the output of this model is a binary classifier, supervised machine learning can also be applied to the data. Therefore, a Random Forest Classifer model to create and synthesize various decision trees may be implemented to be compared against this deep learning neural network model. 
