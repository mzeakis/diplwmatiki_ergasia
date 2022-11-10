# neural-networks-in-key-music-recognition
ARTIFICIAL NEURAL NETWORKS AND THEIR APPLICATIONS IN RECOGNIZING THE KEY OF A PIECE OF MUSIC 

Machine Learning and Neural Networks are a scientific field based on the way a person works and specifically the neurons of his brain. 
The latter simulate human experience through the process of education. 
Their learning is performed using large data sets in order to achieve problem solving and prediction execution. 
This dissertation deals with the creation of a model of neural networks in order to predict the key of a piece of music. 
In order to realize the model, it was deemed necessary to research music theory in order to identify terms such as musical scale, tonality and finally a musical key.
In addition, the convolutional neural  networks were the architecture of the networks developed. 
The latter provide the most effective training in images, and in particular the spectrograms, which were the data sets used. 
The model consists of two convolutional networks, one for predicting tonality and one for predicting the scale that constitute the musical key. 
The framework used to develop the model is PyTorch. In it, the codes (python) were created for data processing, training and evaluation of networks. 
During the training and evaluation process of the model, many experiments were performed in order to determine the optimal values of the hyperparameters 
that give the best possible prediction success rate. Finally, a program (keyFinder.ipyndb) was developed that uses the trained model to predict the music key of 
any track we want by having the corresponding mp3 file.

In this repository there are files that helped us find easier ways to perform some programming tasks such as 
