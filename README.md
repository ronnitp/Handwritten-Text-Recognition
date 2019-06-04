# Hand Written Text Recognition using CNN (Tensorflow)
Handwritten Text Recognition is implemented using Tensorflow and trained on the dataset from [I-AM Handwriting Database](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database). This model is used to recognize handwritten text. The current neural network model can only recognize the text contained in the images of the segemented words. As these are smaller compared to sentences the neural network can be small and it would be feasible to train on the CPU.

This is what the conversion from handwritten text to text recognition looks like:
![sample converted](https://github.com/ronnitp/Handwritten-Text-Recognition/blob/master/sample%20output.png?raw=true)

In order to run the program, execute the following instructions:
1. Download the following from the given [link](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database):
* data/ascii>>words.txt
* data/words>>words.tgz
2. Download this whole repository into your system.
3. Go to the model/ directory and unzip the file model.zip (pre-trained on the IAM dataset). Make sure that the unzipped files are placed directly into the model/ directory and not some subdirectory created by the unzip-program. Afterwards, go to the src/ directory and run python main.py.


This was run on a system with:

Python 3.7

Tensorflow 1.13.1

Mac OS - Mojave


