# Customized-Sentiment-Analysis-using-Hugging-face-dataset
While working with text data for sentiment analysis transfer learning/fine tuning give most accurate results. As it uses pretrained model we can achieve a reliable accuracy score while using fewer computational resources.
Transfer learning usually has the following steps:

1. Choose a pretrained model that was trained on a large dataset.
2. Delete the output layer of the pretrained model and the weights and bias feeding into the output layer.
3. Create a set of randomly initialized weights and biases for the new output layer with the sentiment analysis task. The sentiment analysis task is a classifier with two outputs, positive and negative.
4. Retrain the weights and biases.

After train-test split, the resultant dataset is balanced so I chose the accuracy matrix.

Model Accuracy achieved 92%
