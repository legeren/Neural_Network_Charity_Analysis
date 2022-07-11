# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis is to predict whether charitable applicants will be successful if funded by Alphabet Soup.  Using knowledge learned from the module of machine learning and neural networks, I used the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 
https://github.com/legeren/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.ipynb
https://github.com/legeren/Neural_Network_Charity_Analysis/blob/9536edc75a002467ba7c216640ac18d1c06e961a/AlphabetSoupCharity.h5
https://github.com/legeren/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimzation.ipynb

### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
   - The target variable is the IS_SUCCESSFUL column.

2. What variable(s) are considered to be the features for your model?
   - The feature variables are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, ASK_AMT

3. What variable(s) are neither targets nor features, and should be removed from the input data?
   - The variables that are neither targets nor features are: EIN, NAME

### Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - Following the sample done in the module, I selected 8 as my initial hidden_nodes_layer1 and 5 as my hidden_nodes_layer_2
   - ![image](https://user-images.githubusercontent.com/100737452/178166800-dff9472c-c6ad-469b-805e-cab5c7544b53.png)


2. Were you able to achieve the target model performance?
   - No.  The highest accuracy I achieved was 63.5%.
   
3. What steps did you take to try and increase model performance?
   - ***Attempt#1 - Increase epoch to 50***
   
      ![image](https://user-images.githubusercontent.com/100737452/178166860-f2fbcdd8-b18b-4b0c-b235-957a7488eca8.png)

   - ***Attempt#2 - Decrease epoch to 20***
   
      ![image](https://user-images.githubusercontent.com/100737452/178166870-443ce1aa-0696-4b54-8e21-3000e27ebbaa.png)


   - ***Attempt#3 - Increase hidden_nodes_layer2 to 50***
      ![image](https://user-images.githubusercontent.com/100737452/178166874-2a6791b0-04fb-48e2-99b8-7ca63ed49f3e.png)



## Summary: 
Overall, despite different attempts to optimize the deep learning model, I was only able to improve to 63.5%.  Playing around with the number of hidden nodes could increase opportunities for our model to find trends in the dataset which might solve this classification problem.
