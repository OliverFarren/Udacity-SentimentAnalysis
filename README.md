# Udacity-SentimentAnalysis
Sentiment Analysis Model using LSTM - developed during the Udacity Machine Learning Nanodegree

This guided Project looks at building a Sentiment Analysis Model using LSTM to predict whether the sentiment of a moview review is positive or negative.

The final model was tested on a test dataset using an sklearn accuracy score and had a final accuracy of 83%

This project was the culmination of the Machine Learning course that explored building and deploying several XGBoost models in Amazon SageMaker using clean datasets.

## Key learning outcomes:

- Build a corpus of words from a series of text files
- Building a simple PyTorch model and deploying as an endpoint in SageMaker
- SageMaker resource management 
- Connecting the deployed model to a REST API through AWS API Gateway and AWS Lambda.

## Project File Details

SageMaker Project.pynb - this is the notebook that documents the process of how the model was developed. All endpoints and notebooks instances since the project have ended have since been closed.

website/index.html - contains the Udacity provided index.html that connects to a deployed AWS API that sends off a user inputed review for sentiment analysis and returns the model prediction as a binary outcome: Positive or Negative.

serve/ - contains Udacity provided files that were used to construct the model ready for deployment. Additions were made to the predict.py to compute the result of an input text
train/ - contains Udacity provided files that were used to train the model in Sagemaker. Additions were made to train/train.py to train the model


