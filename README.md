# Handwritten-Text-Recognition
Handwritten Text Recognition is implemented using Tensorflow and trained on the dataset from [I-AM Handwriting Database](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database). This model is used to recognize handwritten text. The current neural network model can only recognize the text contained in the images of the segemented words. As these are smaller compared to sentences the neural network can be small and it would be feasible to train on the CPU.

This is what the conversion from handwritten text to text recognition looks like:


In order to run the program, execute the following instructions:
1. Download the following from the given [link](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database):
* data/ascii>>words.txt
* data/words>>words.tgz
