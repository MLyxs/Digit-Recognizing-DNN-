# Digit-Recognizing-DNN-

Last Edited: 5/13/2018

This project is an adaptation of one of the NN created in the Neural Networks and Deep Learning textbook made by Michael Nielsen.
https://github.com/mnielsen/neural-networks-and-deep-learning

The original neural network script, "network2.py", by Michael allows a lot of customization of the NN (e.g. choosing hyperparamters, saving a NN, loading a NN). This adaptation,"Hand_Alg_2.py", adds more capabilities to the base NN. For CSV files that represent images in the MNIST format, they can be uploaded into the NN and used for testing (hopefully for training later on). I created a support file for this called "Extra_Test_Set_Maker.py". A CSV file, "mnist_test_10.csv", is provided in this repository. In addition, I have added a function,"start_up()", into the "Hand_Alg_2.py" that abstracts some of the NN creation process away from the user. This function is executed every time the "Hand_Alg_2.py" is ran. The user can enter their desired values while in interactive mode.

The "97_percent_Accuracy" is a deep neural net that I trained myself. It will be used for guessing the digits of unlabeled datasets and outputting the guesses to a text file.

The current version of this project is constructed for the RaspberryPi 3 Model B. It allows for the user to take a picture with the
PiCamera, and send that image to a preprocessing script. The preprocessing script will convert the image into a pixel data format
that resembles the MNIST data set. This data will then be passed into the DNN to be processed.

See the "Demonstration.py" script for more information.
