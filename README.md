# Sentiment-Analysis-on-Amazon-Reviews
Classifying the reviews into positive and negative using the sentiment analysis.
Using some common machine learning models and deep learning models to classify the reviews

Machine Learning models used are:-
- KNN
- Random Forest Classifier

Deep Learning models used are:-
- LSTM
- mini batch LSTM
- CNN+LSTM

Preprocessing is performed on text and they are stored as documents in model.bin file.
Text normalization is performed after text tokenization
For text normalization we are performing 
- Stemming (Porter Stemmer)
- Lemmatization

For word embedding we are using pretrained Word2Vec model for better results.
