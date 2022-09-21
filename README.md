# Neural_Network_Charity_Analysis

## **Overview**
The purpose of this analysis was to apply machine learning and knowledge of neural networks to create a binary classifier that predicts whether or not applicants will be successful if funded by the Alphabet Soup team. 

## **Results**
**1. Data Processing**
    - *What variable(s) are considered the target(s) for the model?*
        - The 'IS_SUCCESSFUL' column was the target for my model. 
    - *What variable(s) are consdered to be the features for the model?*
        - The following columns were considred features for my model: 'APPLICATION_TYPE'and 'CLASSIFICATION'
    - *What variable(s) are neither targets nor features, and should be removed from the input data?*
        - The columns 'EIN' and 'NAME' were neither targets nor features, and thus were removed from the model. 

!["TargetVariable"](https://github.com/mhenson1989/Neural_Network_Charity_Analysis/blob/main/Images/TargetVariable.PNG)

**2. Compiling, Training, and Evalating the Model** 
    - *How many neurons, layers, and activation functions did you select for your neural network model, and why?*
        - Within my first model, I choise two layers with 80 and 30 neurons, respectively, and a relu activation function for both layers. Additionally, I ran my model for 100 epochs. I chose this as my first model, because I wanted a fairly simple baseline model. Relu activations also seem to have higher overall accuracy rates. 
    - *Were you able to achieve the target model performance?*
        - Unfortunately, I was unable to achieve a target model performance, but reached an accuracy level of approximately 72%.
    - *What steps did you take to try and increase model performance?* 
        - I tried additional hidden layers, number of neurons and activation functions on each model, however, each time, an optimization of 72% was achieved. I think that with a significant amount of epochs run, I could get a slightly higher accuracy rate, however, with the time spent, I did not think it was an optimized model for one additional percentage point of accuracy. 

!["Model"](https://github.com/mhenson1989/Neural_Network_Charity_Analysis/blob/main/Images/TrainedModel.PNG)


## **Summary**

Overall, the model proved to be reasonably accurate for the features and targets picked. In future models, I might recommend adding additional features, such as affiliation and income amount. 