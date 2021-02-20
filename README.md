# Sentiment Analysis model on IMDB reviews

### Data description :
This data contains 50K movie reviews posted on IMDB website. The data is divided into 2 folders train and test each containing 25K observation. train and test are further divided in to two folder pos (positive obs) and neg (negative obs) each containing 12.5K observations while consolidating the data into one file (i.e. single file containing all train and other containing all test data) I have put first 12.5K as pos observations and next 12.5K as neg observation.

## Goal : Create a model for 'Sentiment Analysis'
* Process the data.
    - Remove unwanted characters (eg. ",.[]() etc.) and HTML tags (if present)
    - Remove stopwords (eg. a an the in if etc.)
    - Normalize the data by stemming (PorterStemmer is used here)
    - Vectorize the data (CountVectorizer is used here)
    - Scale the data if required.
* Build a suitable model.
    - Use Binary Classification model for classifying +ve and -ve words
    - Train the model on Train data.
* Test the model against the Test data
* Perform sanity check.
-----
Large Movie Review Dataset<br>
Source : http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
