# Where Care Localization Algorithm

This algorithm was developed for the 'Where Care' indoor localization system.
The neural network within this project is trained using Keras and Tensorflow. 
The data used to train the network was collected within UCC's Western Gateway Building.
A minute's worth of data was collected at each location node in the space.
Subsequently, the data was saved in Firebase Realtime Database in a JSON tree.
This data was downloaded and used for the creation of this feedforward neural network.
The L1 normalization procedure used to process input data ensures that the model is capable of providing accurate predictions across many devices. 
This extends such an algorithm beyond single-device use cases and enables 'Where Care' systems to be implemented in a wide variety of facilities. 

# How to Run
Open this code in Google Colab and ensure the neural network is saved under the following file path:

'/content/drive/My Drive/Colab Notebooks/neuralNetwork'

Run the code, ensuring all required files are available to the script.
