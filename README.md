# TensorflowMNIST - A simple Neural Network to classify handwritten digits from MNIST dataset

Note : I encountered The "ModuleNotFoundError: No module named 'tensorflow.examples' " 

when using "from tensorflow.examples.tutorials.mnist import input_data and mnist = input_data.read_data_sets("MNIST/", one_hot = True)"

this is because "tensorflow.examples.tutorials" module is not included in the pip package.

You will find it in Tensorflow GitHub repo. 
! git clone https://github.com/tensorflow/tensorflow.git

In the downloaded folders locate where the input_data.py file is then copy and paste it in the working directory of your project 

Then import input_data on your python terminal, it will sort it out for you. 

You're Welcome
