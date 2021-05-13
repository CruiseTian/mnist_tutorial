# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).



# Results

|    Question    | Train accuracy | Test accuracy |
| :------------: | :------------: | :-----------: |
|       Q1       |     97.38%     |    88.30%     |
|       Q2       |     81.85%     |    81.20%     |
|       Q3       |     98.05%     |    86.00%     |
|       Q4       |     98.03%     |    86.00%     |
| Q5(last epoch) |     99.71%     |    99.00%     |

For Q5, I use Lenet as a model for training.