The model in the given code is saved into our personal google drive to prevent it from training everytime everytime a new google colab
session is alloted to us. 

This means that in order to run the code, the user will have to mount his/her own google drive into google colab and load the dataset into
their google drive. 

If visual code is being used to run the code, the code may have to be changed a little specially where the model is being loaded to the
google drive. That piece of code will have to be removed and the section where the model is giving predictions, the model is being loaded
from the google drive as well. That piece of code will also need a few alterations. Hence it is better to use google colab while running
the code. 

