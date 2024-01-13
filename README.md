# Neural-Network-1
Neural Network

How to run the files:
You can run code on jupyter and google colab.
Libraries used: numpy, matplotlib, pandas, seaborn, sklearn.model_selection,
sklearn.neural_network, sklearn.metrics

## 1. Data Loading and Initialization
Loaded data from a CSV file using pandas.

Renamed columns for better clarity.

## 2. Data Preprocessing:
Converted categorical labels in the "Classes" column to numerical values.

Checked for null values in the dataset.

Calculated and printed the correlation matrix.

Normalized selected independent variables.

Neural Network Training and Evaluation:

## 3. Utilized scikit-learn's MLPClassifier for training neural networks.

Implemented nested loops to iterate over various hyperparameters (activations, learning rates, max iterations, and hidden layers).

Displayed training and testing accuracy, mean squared error (MSE), and plotted accuracy/MSE curves over epochs for each combination of hyperparameters.

Used a random permutation and mini-batch training approach.

## 4. Visualization:
Generated plots for training and testing accuracy/MSE over epochs, color-coded for different hyperparameter combinations.
Used matplotlib for visualization.

<img src = "https://github.com/Nikita-Chorghe/Neural-Network-1/blob/master/img1.png"  width="500" height="500"></img>
