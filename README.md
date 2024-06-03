# deep-learning-challenge

Charity Success Prediction Model

Overview

This project aims to develop a machine learning model using deep neural networks to predict the success of charitable organizations based on various features. The dataset used for training and evaluation is sourced from the Alphabet Soup Charity dataset. The model utilizes TensorFlow and scikit-learn libraries for development and evaluation.

- Dependencies

scikit-learn

pandas

TensorFlow

- Data Preprocessing

Non-beneficial ID columns ('EIN' and 'NAME') were dropped from the dataset.

Categorical variables were converted into numerical format using one-hot encoding.

Columns with low variance or containing a high number of unique values were replaced or merged to enhance model performance.

The dataset was split into training and testing sets, and features were scaled using StandardScaler.

- Model Architecture

Sequential deep neural network with two hidden layers and an output layer.

The input layer size is determined by the number of features in the dataset.

ReLU activation function is used in hidden layers, while the output layer utilizes a sigmoid activation function.

The model was compiled with binary cross-entropy loss and the Adam optimizer.

- Training and Evaluation

The model was trained for 100 epochs using the training dataset.

Model performance was evaluated using the testing dataset, yielding an accuracy of approximately 72.27%.

The trained model was saved in HDF5 format for future use.

- Files

AlphabetSoupCharity_Model.h5: Saved trained model file.

For detailed implementation, refer to the code provided in the project.




