# deep-learning-challenge
Mod 22 challenge assignment

Analysis: 
    THe purpose of this report was to create a classification model using neural networks to predict the success of fund raising efforts for a non profit foundation. The model seeks to guide the non profit in choosing their campaigns. 

Result: 
Data Preprocessing

What variable(s) are the target(s) for your model?: IS SUCCESSFUL- this variable indicates whether the funding was sucessful
What variable(s) are the features for your model?: All variables were used except EIN and NAME
What variable(s) should be removed from the input data because they are neither targets nor features?: EIN and NAME, these two variables did not contribute to the predictive nature of the model.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?: I used two layers using the ReLU activation function and an output layer using the sigmoid function. I used 80 neurons for the first layer, and decreased to 30 in the second layer. This gradually reduces the complexity of the model and renders the model more effective. 
Were you able to achieve the target model performance?: Our model did not meet the target performance. It was 50% accurate, rendering it only slightly more effective than randomly guessing the success of a campaign. 
What steps did you take in your attempts to increase model performance? We preprocessed the data to ensure that the model receives properly formatted and normalized data, and used the 'StandardScaler' library to expedite the models convergence during training. We adjusted the number of neurons in each layer and tried different arcitectures to see if they could improve performance. 

Summary: Our model failed to achieve the desired 75% accuracy that the challenge desired. The model could be made more effective by using different numbers of neurons and more layers.