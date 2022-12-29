# Neural_Network_Charity_Analysis

***Overview of the analysis***

Create neural network model that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

***Results***

o	Data Preprocessing

1. What variable(s) are considered the target(s) for your model?

    •	IS_SUCCESSFUL
  
2.	What variable(s) are considered to be the features for your model?

    • APPLICATION_TYPE
    
    • AFFLIATION
    
    • CLASSIFICATION
    
    • USE_CASE
    
    • ORGANIZATION
    
    • STATUS
    
    • INCOME_AMT
    
    • SPECIAL_CONSIDERATIONS  
    
    • ASK_AMT
  
  3.	What variable(s) are neither targets nor features, and should be removed from the input data?

    • EIN
    • NAME
  
o	Compiling, Training, and Evaluating the Model

4.	How many neurons, layers, and activation functions did you select for your neural network model, and why?

    •	Neurons = 70, 40
    
    •	Layers = 2
    
    •	Activation function = reLu 
  
  [Attempt 1 Model ](https://user-images.githubusercontent.com/111043588/209889711-218f7b30-533a-446d-8968-ca7576246518.PNG)
  
5.	Were you able to achieve the target model performance?

    • No, unsuccessful at achieving target performance of 75% accuracy rate. 
    
  ![Attempt 1 Results ](https://user-images.githubusercontent.com/111043588/209889714-c0daf6cd-d379-4b2b-91fa-03418d56360c.PNG)
  
6.	What steps did you take to try and increase model performance?

    •	Adjusted activation from reLu to Tanh
    
 ![Attempt 2 Model](https://user-images.githubusercontent.com/111043588/209889715-c86e8e4b-65d0-460b-8913-a4757aa4d655.PNG)  
    
    • Add additional layers
    
  ![Attempt 2 Results ](https://user-images.githubusercontent.com/111043588/209889716-6d51723e-fd8f-406a-9c50-919e792ce609.PNG)
  
    •	Adjust epoch
  
***Summary***

In closing the overall results of the deep learning model was unsuccessful. The model was able to predict 72% of the time based off the charity_data.csv. Unfortunately, I was unable to meet the 75% accuracy target. I was curious if using Random Forest model would improve prediction rate. Sadly, the results were similar, 72%. In short my recommendation would be to have additional data to hopefully increase the accuracy of the original model with reLu. 

