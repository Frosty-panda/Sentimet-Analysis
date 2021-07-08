# Sentimet-Analysis
This model is based on IMDB dataset provided along with the file which contains 50,000 reviews.
25,000 are positive reviews while rest are negative reviews.
The goal of the project was to develop Sentiment Analyzer based on a LSTM model which could determine if some review is positive or negative. IMDB dataset was used with train/test split already built in the IMDB class constructor. Train set is then split into train/validation split using (75-25)[%] ratio.
I took a batch size of 50 and learning rate of 0.001
I achieved an accuracy of 88.3% on the train set after 5 epochs.
