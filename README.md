# Neural_Network_Charity_Analysis
Neural Network - TensorFlow Platform, Neural networks (known as artificial neural networks – ANN), Perceptron model, Activation Function (Rectified Linear Unit (ReLU) function)

# Overview of the Project
The analysis applies a deep learning model to predict if companies that get funded by Alphabet Soup will succeed or not. The model pulls the data from around 34,300 historic records and utilizes the information including the affiliation and type of companies, the amount of fund, the income, the size of the company and other features as input to determine the success rate. Raw data gets pre-processed using Pandas first and then splits into training and testing groups. Three hidden layers with ReLU activation function are used to train the model and output categorical results. The neural network model achieves an accuracy of around 73%. 

# Results
1. Data preprocessing  
- The target of the model is that such a company funded by Alphabet Soup could succeed.
- The information except company identity is treated as input features for the model.
- Non-beneficial information such as company identity info should be removed from the input data.
  
2. Model  
- In total there are 3 hidden layers including 10, 8, 8 neurons respectively applied to the model. The activation function selected for the first hidden layer is "tanh" and the rest two hidden layers have the activation function as "ReLU". The output layer has the activation function as "Sigmoid" for categorical output purposes. 
- The target model performance (accuracy) is below 75%.  
- Attempts including adding the number of hidden layers, the number of neurons and changing the activation functions have been conducted potentially to achieve better model performance.
  
# Summary
Overall, the deep learning model performs adequately well in predicting whether a company funded by AlphabetSoup could succeed or not. Another less complex model (random forest model) could also be applied for such classification as the data comes as in tabular form. The random forest model could achieve a decent performance with fewer computational resources consumed.
