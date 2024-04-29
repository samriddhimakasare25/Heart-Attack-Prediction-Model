## Heart Attack Prediction Model
This project aims to predict the likeliness of a patient having a heart attack based on basic information such as age, sex, blood pressure, cholesterol levels, etc.

## Dataset
The dataset used in this project is obtained from Kaggle. It contains various features including:
- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trtbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalachh)
- Exercise induced angina (exng)
- ST depression induced by exercise relative to rest (oldpeak)
- Slope of the peak exercise ST segment (slp)
- Number of major vessels colored by fluoroscopy (caa)
- Thalassemia (thall)

## Model Architecture
The model architecture is a simple neural network implemented using TensorFlow. It consists of:
- Input layer
- Dense hidden layer with ReLU activation
- Dropout layer
- Output layer with sigmoid activation

## Usage
Clone the repository:
- git clone https://github.com/samriddhimakasare25/heart-attack-prediction.git

## Install the required dependencies:
- pip install -r requirements.txt
- Run the Jupyter notebook or Python script to train and evaluate the model.

## Results
The model achieved an accuracy of approximately 86.89% on the test data.

