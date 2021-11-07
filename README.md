# Neural_Network_Charity_Analysis

## Overview: The purpose of this machine learning and neural network project is to use features within the dataset to create a bianry classifier that is capable of prediction whether or not an applicant will be successful if they are funded by Alphabet Soup. The dataset contains over 34000 organizations with Alphabet Soup funding containing metadata for each organization such as organization type and use of funding. There are three main steps associated with this project. These include preparing the neural network data, compiling/training/analyzing the machine learning model, and model optimization. 


## Results: 
- The model target variable is the "IS_SUCCESSFUL" column.
- The features of the model include ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, APPLICATION_TYPE, AFFILATION, CLASSIFICATION, USE_CASE.
- EIN and NAME are both features that will be dropped becuase they have little to do with the outcome variable. 
- The mdoel is configured with 43 input features, 80 neurons in the first hidden layer, and 30 neurons in the second hidden layer. 
- The model achieved 47% accuarcy and thus was not able to reach the 754% threshold.
- Some step taken to increase model performance include changing the number of hidden layers in the model and changing the number of epochs. 

<img width="1038" alt="Screen Shot 2021-11-07 at 6 15 11 PM" src="https://user-images.githubusercontent.com/85506567/140665507-f8dc7682-b9ed-4b81-9697-eb10faed419a.png">

## Summary:
The accuracy for this model was only 47%. Thus, the best way to increase the accuracy would be to have more data entries to test. Potentially, dropping so many of the features as we did casued the accuracy to go down, however, this may have affected the performance of the neural network. THe best way to increase the accuracy would be to add more features. 

