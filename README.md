# trip_advisor_sentiment_analysis
Trip Advisor had provided a dataset of its reviews with binary classification label of ‘Happy’ and ‘Not Happy’. For the word embeddings, I used GloVe provided by Stanford University. I used stop words from NLTK to remove sentence fillers that do not change the context. Then I used TF-IDF to remove the words that provide the least information. Then I used 1D convolution neural networks (CNN) to predict whether the statement was a ‘Happy’ or a ‘Not Happy’ one.
