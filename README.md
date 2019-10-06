# Predictive-Hindi-Keyboard
This is a Predictive keyboard for Hindi Language which is made using Recurrent Neural Networks
We will build a model that predicts the next word based on a few of the previous. We will try to predict 5 suggestions instead of only 1 at a given instance to give a better variety and choice to the user to increase the chances of getting the right choice for him.
A Recurrent Neural Network is used to build the model. It can be defined by a relation over time steps given by :
St = (St-1 * Wrnn  +  Xt * Wx)
Where St is the state at time step t, Xt is the input and W specifies the weight matrix.
This type of neural network is preferred because it remembers the past information through a feedback mechanism.
