# Mushroom Classification
CS423: Intro to AI

-----------
Description
-----------
This project implements Neural Network and Support Vector Machine models in order to classify the mushrooms dataset from the University of California, Irvine. A coarse grid search and fine grid search are implemented to select the best-performing model, which is evaluated using K-Fold Cross Validation. The mushrooms dataset is managed with the pandas library. The implementation and evaluation of Neural Networks uses the Keras and Tensorflow libraries, and the implementation and evaluation of Support Vector Machines uses the Scikit-learn library.

------
Usage:
------

    python svm_search.py|svm_best.py|nn_search.py|nn_best.py
    
    
--------------------
Files in this folder
--------------------
**nn_search.py**: Explores various neural network models.

**nn_best.py**: Contains a static implementation of the best performing model found in nn_search.py.

**svm_search.py**: Explores various support vector machine models.

**svm_best.py**: Contains a static implementation of the best performing model found in svm_search.py.

**mushrooms.csv**: Contains the mushroom dataset.

