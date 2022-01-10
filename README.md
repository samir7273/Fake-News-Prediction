# Fake-News-Prediction
first you need to import the dependencies to perform on dataset.
download stopwords from here:- import nltk
                               nltk.download("stopwords")
after that you need to load dataset file from here:-
https://www.kaggle.com/c/fake-news/data?select=train.csv
Then perform preprocessing which will help in good prediction.
After Preprocessing perform Stemming process which is used for reducing a word to its Root word
ex:- actor, actress, acting --> act

after Stemming process use TfidfVectorizer which will help in converting the textual data to numerical data.

after that you need to split dataset in train and test data.
then apply LogisticRegression model.
after than you can make prediction.


