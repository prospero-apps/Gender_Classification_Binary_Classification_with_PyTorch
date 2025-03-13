# Gender Classification - Binary Classification with PyTorch
binary gender classification with PyTorch

In this notebook we'll use PyTorch to build a binary classification model to predict gender based on a couple features of the human body.

## Contents

### Data Preparation
The analysis will be based on the 'Gender Classification Dataset' dataset by Jifry Issadeen available on kaggle.com - https://www.kaggle.com/datasets/elakiricoder/gender-classification-dataset.

This dataset was created for educational purposes.

This dataset consists of 5001 records containing information on particular individuals, regarding hair length, forehead dimensions, nose dimensions, lips thickness and nose-to-lip distance.

![image](https://github.com/user-attachments/assets/fc8b705b-b26a-4015-9541-fdd9189b7a4a)

### Model Building
We have the data in place, it's time to build a model. Besides the model, we'll define a loss function and optimizer.

![image](https://github.com/user-attachments/assets/045c42e9-470c-46ea-ae9a-5e1677451aa4)

### Model Training
Training the model involves two loops: a training loop, where the model learns the relationships between the features and labels, and a testing loop, where the model is evaluated.

![image](https://github.com/user-attachments/assets/71f0d96b-43cb-4e84-8da8-6836fd130a3e)

### Model Evaluation
Let's evaluate the model and see how it performs on data it never saw.

![image](https://github.com/user-attachments/assets/5e728258-6f64-42d5-910d-9f6bf7cd3590)
