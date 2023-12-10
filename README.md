Code is provided as jupyter notebook and python file.

Don't forget to decompress data.zip and adjust paths of data files in the second code cell.

## Code functionality
### Data preparation
* Splitting the data into an 80% training set and a 20% validation set in stratified fashion using scikit learn train_test_split function.
* Utilizing the Torch data loader to efficiently load and manage the dataset.
### Training process 
* Creating custom neural network architecture.
* Developing custom training loop.
* Training model using:
  * Optimizer: Gradient stochastic descent
  * Learning rate: 0.01
  * Loss Function: Cross Entropy
### Creating plots for
* Training and validation loss.
* Training and validation accuracy.
### Analysis
* Evaluating the impact on the model's training and final performance based on the following factors:
  * Changing the learning rate, try 5 different learning rates at least.
  * Changing the batch size, try 5 different batch sizes at least.
### Extra
* Introducing dropout layer and layer normalization to your model and analysis the effect of adding them on the training and final performance.
