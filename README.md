### NLP
## Project Overview
This project implements a Natural Launguage Processing using TensorFlow & Keras for sentiment analysis.
The model is trained on twitter data set which has different tweets from users.
Technologies Used
Backend: Python
Model Building: Tensor Flow, Keras, LSTM
Features
Used Tokenizer,Padded seuqence to translate text data
Used Embedding layer to create dense vectors
RandomOverSampler is needed to balance the data set
LabelEncoder is required to translate sentiments column
Created LSTM , Drop out for model building
softmax function is used in dense output layer to classify sentiments
Uses ReLU activation for hidden layers and Sigmoid for classification
Trained using Adamw optimizer & categorical_crossentropy loss
Evaluates model performance using accuracy and loss curves
Loads the trained model for future predictions
