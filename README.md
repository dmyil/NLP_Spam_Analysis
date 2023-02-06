# NLP_Spam_Analysis
Analyzing spam and fraud in text using NLP


In this project, I have performed basic EDA, Data Cleaning, Data Analysis classify text as spam or non spam using NLP.

The two models used in this experimentation are Naive Bayes and LSTM. Please refer the codebook for complete info.


FINAL THOUGHTS

To extend on this work, The training and test corpus has to be balanced w.r.t to the Y variable before modelling i.e., since most of our data is not spam, we can also perform model robustness tests with undersampling or oversampling.
We can also experiment with different vectorizers like TF-IDF to convert text into numeric form provided a large corpus exists to give more weightage to important words. The concern here is that spam transcripts have a lot of garbage words and hence I have used a simple count vectorizer for modeling in this simple use case.
We can deploy the model using Azure Web Service or AWS Endpoints or through JSON files embed into an application.
The deployed model can take in text as input and give out the predictions based on the probability of spam nature in the words.
