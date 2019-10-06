# Predictive-Hindi-Keyboard
This is a Predictive keyboard for Hindi Language which is made using Recurrent Neural Networks
We will build a model that predicts the next word based on a few of the previous. We will try to predict 5 suggestions instead of only 1 at a given instance to give a better variety and choice to the user to increase the chances of getting the right choice for him.
A Recurrent Neural Network is used to build the model. It can be defined by a relation over time steps given by :
St = (St-1 * Wrnn  +  Xt * Wx)
Where St is the state at time step t, Xt is the input and W specifies the weight matrix.
This type of neural network is preferred because it remembers the past information through a feedback mechanism.
The Dataset used is a hindi Translation of the bible ( kaggle datasets download -d kapilverma/hindi-bible ).Training on such a dataset can help us predict words in a similar context as that of the bible. This can be altered as per the requirements and other files can be used to train the model to improve the veritality of the model.
The model based upon a single LSTM layer having 128 neurons that is fully connected to a softmax activation layer having 57 neurons.
The training takes place over 20 epochs with RMS prop optimiser using 5% data for validation.
The model finished training with an Accuracy of 76.54%.
The plots of model accuracy and model loss are attached 
