# Bayesian Classifier from Scratch on MNIST
This project implements a Bayesian classifier from scratch and tests it on the MNIST dataset, a well-known dataset for handwritten digit classification. The goal is to apply a multivariate continuous distribution approach to classify digits, then evaluate the classifier using metrics like the confusion matrix and F1 score.

## Project Overview

* **Objective:** Implement a Bayesian classifier without using machine learning libraries for the core algorithm, and test it on the MNIST dataset.
* **Dataset:** MNIST - a collection of 70,000 images of handwritten digits (0-9) with each image being 28x28 pixels.
* **Metrics:** Confusion matrix, F1 score, and overall accuracy.

## Installation
Ensure you have the following Python libraries installed:
```ini
pip install numpy seaborn matplotlib scikit-learn keras
```
## Implementation Details
### Bayesian Classifier
The Bayesian classifier is built using a continuous multivariate distribution. The steps include:

#### Model Training:
The classifier calculates the mean and covariance matrix for each class based on the training data.
#### Prediction: 
The model uses the trained parameters to predict the class of new samples by applying discriminant functions.
#### Evaluation:
The performance of the model is evaluated using accuracy, confusion matrix, and F1 scores.
#### Key Functions
* **fit():** Trains the model by calculating the mean and covariance matrix for each class.
* **predict():** Classifies the input data based on the trained model.
#### How to Run
Load the notebook: **Bayesian_Classifier_Project_II.ipynb**.

Follow the cells sequentially to train the classifier, predict results, and evaluate performance.
Visualize the results using the provided plots and metrics.
#### Results
The notebook generates the confusion matrix and calculates the F1 score for each class.
Performance metrics are discussed at the end of the notebook.
Contributing
Feel free to fork this repository, make improvements, and submit a pull request. Contributions that enhance the model’s performance or add new features are welcome.

## License
This project is licensed under the MIT License.

