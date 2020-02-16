# Different-MLP-Architectures
In this mini project I have tried different MLP Architectures on MNIST dataset 

### PROCEDURE:

__Following steps were followed__:

- Data is imported and one hot encoded for each of the classes.


- Primarily we are considering 3 different neural network architecture here:
    - MLP with 2 hidden layers
    - MLP with 3 hidden layers
    - MLP with 5 hidden layers
    
    
- In each of the architecture we have tried 4 different for understanding the intricate working of the model and how to avoid overfitting and underfitting of the data.
    - Simple MLP
    - MLP + dropout with dropout rate = 0.5
    - MLP with Batch Normalization
    - MLP with Batch Normalization and Dropout(dropout rate = 0.5)
    
- After implementing each of the 4 techniques in each architecture we plot the violin plots to see the distribution of weights that we get after the implementation of optimization Algorithm.

- Finally we plot the graphs of loss vs epochs in each architecture to see how regularization is affected by adding different layers in the model.

## 1. Architecture1: Model with 2 hidden layers:
### input(784)-Relu(512)-Relu(256)-Output(10)
<img src = https://github.com/yatscool007/Different-MLP-Architectures/blob/master/mlp_images/arc1.PNG >

## 2. ARCHITECTURE 2: Model with 3 hidden layers
### Input(786) - relu(1000) - relu(500)-relu(250)-softmax(10)
<img src = https://github.com/yatscool007/Different-MLP-Architectures/blob/master/mlp_images/arc2.PNG >

##  Architecture 3: Model with 5 hidden layers
 ### Input(786) - relu(200) - relu(300) - relu (400) - relu(500) - relu(600) - softmax(10)
 <img src = https://github.com/yatscool007/Different-MLP-Architectures/blob/master/mlp_images/arc3.PNG >


