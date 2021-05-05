# sentiment_analysis_bert
Transfer learning with BERT to perform sentiment analysis on hotel reviews. The model perform multi-class classification: positive, negative and neutral. 
The project is based on https://curiousily.com/posts/sentiment-analysis-with-bert-and-hugging-face-using-pytorch-and-python/. Initially, the code in the article did not work due to recent updates to Pytorch libaries. Several code changes were required. The code is working as of April 2021. 
A dataset of over 16000 hotel reviews (https://www.kaggle.com/datafiniti/hotel-reviews?select=Datafiniti_Hotel_Reviews.csv) from Kaggle were used. 

The model achieved 66% accuracy on custom test data which consists of 178 manually labelled reviews which showed significant improvement to neural networks with Universal Sentence Encoder (https://curiousily.com/posts/sentiment-analysis-with-tensorflow-2-and-keras-using-python/) and VADER model which only hover around 55% and face difficulty in classifying neutral reviews.
