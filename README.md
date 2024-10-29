# Customer-Churn-Prediction-Using-ANN-
Overview

This project leverages Artificial Neural Networks (ANN) to predict bank customer churn. By using a dataset with demographic and financial information about customers, the model aims to classify whether a customer is likely to leave the bank. Early identification of at-risk customers enables banks to apply targeted retention strategies.

## Dataset Details

The project uses the Churn_Modelling.csv dataset, containing data on 10,000 bank customers with the following features:

- CreditScore: Customer's credit rating
- Geography: Customer’s country
- Gender: Customer’s gender
- Age: Age of the customer
- Tenure: Number of years with the bank
- Balance: Account balance
- NumOfProducts: Total products the customer has with the bank
- HasCrCard: Whether the customer has a credit card
- IsActiveMember: If the customer is active
- EstimatedSalary: Customer's estimated salary
- Exited: Target variable, where 1 indicates churn and 0 indicates retention

## Project Workflow
1. Data Preprocessing
- Data Cleaning: Removed non-informative columns (e.g., RowNumber, CustomerId, Surname).
- Encoding: Transformed categorical features like Geography and Gender into numeric values.
- Scaling: Standardized numerical features for better model performance.

  2. Model Architecture
- Developed an ANN using the TensorFlow and Keras libraries.
- Defined layers, including input, hidden, and output layers.
- Utilized ReLU activation for hidden layers and Sigmoid for output layer.
- Compiled the model with binary cross-entropy loss and optimized with the Adam optimizer.

  3. Model Training and Evaluation
- Split the data into training and test sets.
- Trained the ANN on the processed dataset.
- Evaluated the model using accuracy and other metrics on the test data to assess predictive performance.

## Results and Insights

The ANN model accurately predicts customer churn, giving banks insights into which customers may need additional engagement. This can guide customer retention strategies effectively.
