This repository is about the project of "Coding for data science applications" university course.
The project is about image recognition. I have chosen the "MNIST hand-written digits" dataset simply available with the Keras framework. Dataset contains 70000 28 x 28 pixels images of handw-ritten digits in gray scale.
The aim of the project is to build a model able to correctly classify those images.
I wanted to remain stick to the algorithms seen in class:
- K-nearest neighbours
- Logistic regression
- Random Forest
  
File description:
- Notebook EDA contains a brief exploratory data analysis;
- Notebooks "KNN_mnist", "LOGISTIC_mnist", "RANDOM_FORSET_mnist" are used for hyperparameter tuning;
- Notebook "models_mnist", is used to build models with the optimal paramaters, save predictions and also make a speed comparison;
- Notebook "results" is used to show differences between models.
