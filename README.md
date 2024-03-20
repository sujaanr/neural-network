# simple neural network in python

this project demonstrates a simple implementation of a neural network using numpy and matplotlib in python. the neural network is designed to learn from a small dataset of inputs and outputs to predict new inputs. the model uses a sigmoid activation function, backpropagation for learning, and incorporates learning rate and momentum for better convergence.

## installation

before running this project, ensure you have python installed on your system. you will also need numpy and matplotlib libraries. you can install these dependencies using pip:

pip install numpy matplotlib

## usage

to use the neural network, simply clone this repository and run the script:

git clone [<repository-url>](https://github.com/sujaanr/Neural-Network.git)

python neural_network.py



this will train the neural network using the predefined dataset and output the predictions for the given examples. additionally, it will plot the error rate of the neural network over the training period.

## how it works

the `neuralnetwork` class in `neural_network.py` is initialized with input data, output data, a learning rate, and momentum. the network trains on the data for a specified number of epochs, adjusting its weights using the backpropagation algorithm to minimize prediction errors.

the neural network structure is straightforward:
- **sigmoid activation function:** used for both forward propagation and the gradient in backpropagation.
- **learning rate & momentum:** these parameters help in controlling the weight update magnitude and stabilizing convergence.
- **error history visualization:** post-training, the script plots the error history over epochs, allowing you to visualize the learning process.

after training, you can use the `predict` method to make predictions on new, unseen data.

## contributing

feel free to fork this repository, make changes, and submit pull requests if you have ideas on how to improve this project. all contributions are welcome!

## license

this project is open source and available under the [mit license](LICENSE).

