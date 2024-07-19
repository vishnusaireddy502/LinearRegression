# PyTorch Linear Regression Project

This project demonstrates a simple linear regression model implemented using PyTorch. It covers the entire machine learning workflow, including data generation, model creation, training, evaluation, and saving/loading the model.


### Data Generation

The project creates synthetic data using the equation y = wx + b, where:
- w (weight) = 0.7
- b (bias) = 0.3

- It produces 50 datapoints in which 40 data points are used for training and 10 for testing

### Model Architecture

A custom `LinearRegressionModel` class is defined, inheriting from `nn.Module`. It includes:
- Learnable parameters: weight (w) and bias (b)
- A forward method defining the linear regression equation

### Training

The model is trained using:
- Loss Function: L1Loss (Mean Absolute Error)
- Optimizer: Stochastic Gradient Descent (SGD)
- Number of epochs: 200

### Visualization

The project includes functions to visualize:
- Training and testing data
- Model predictions
- Loss curves during training


## Results

### loss curves
   ![image](https://github.com/user-attachments/assets/a00ed115-0286-4745-975a-c9f7becf980e) *


### prediction before training
  ![image](https://github.com/user-attachments/assets/fb9355c2-484c-43b3-beef-811b559edaa1)

### prediction after training
  ![image](https://github.com/user-attachments/assets/1e96b4eb-b809-402d-8aa8-1960ea164c8b)




