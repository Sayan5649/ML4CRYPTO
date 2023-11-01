# LOADING THE TRAINED MODEL:

You can load a previously saved model from "model.h5" file using the load_model() function.


# Concept behind the model:

since we have to distinguish random and pseudorandom strings of length 64 , so we have created numerical features from taking 4 bits consequtively from the starting of the string of length 64 and then shifting 2bits and for each 4bits calculated the probability of 1 and created input features of size 31 and used this data to trained some neural network model .
