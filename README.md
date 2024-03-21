# Simple Neural Network in Python

This project demonstrates a simple implementation of a neural network using NumPy and Matplotlib in Python. The neural network is designed to learn from a small dataset of inputs and outputs to predict new inputs. The model uses a sigmoid activation function, backpropagation for learning, and incorporates learning rate and momentum for better convergence.

## Installation

Before running this project, ensure you have Python installed on your system. You will also need NumPy and Matplotlib libraries. You can install these dependencies using pip:

pip install numpy matplotlib


## Usage

To use the neural network, simply clone this repository and run the script:

git clone [<repository-url>](https://github.com/sujaanr/Neural-Network.git)

python neural_network.py


This will train the neural network using the predefined dataset and output the predictions for the given examples. Additionally, it will plot the error rate of the neural network over the training period.

## How It Works

The `NeuralNetwork` class in `neural_network.py` is initialized with input data, output data, a learning rate, and momentum. The network trains on the data for a specified number of epochs, adjusting its weights using the backpropagation algorithm to minimize prediction errors.

The neural network structure is straightforward:
- **Sigmoid Activation Function:** Used for both forward propagation and the gradient in backpropagation.
- **Learning Rate & Momentum:** These parameters help in controlling the weight update magnitude and stabilizing convergence.
- **Error History Visualization:** Post-training, the script plots the error history over epochs, allowing you to visualize the learning process.

After training, you can use the `predict` method to make predictions on new, unseen data.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests if you have ideas on how to improve this project. All contributions are welcome!

## License

This project is open source and available under the [MIT License](LICENSE).
