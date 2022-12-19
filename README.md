# Email-Classification-NLP

This is a beginner level NLP project. In this, I downloaded the dataset from Kaggle. I read the training data using pandas and check for any missing data. I then go on to read the testing data and again check for missing data. After this, I split it into X_train, X_test, y_train, y_test.

In this, I use TfidfVectorizer that does the work of CountVectorizer and TfidfTransformer. TfidfVectorizer considers the overall document weightage of a word. It helps in dealing with most frequent words. TfidfVectorizer weights the word counts by a measure of how often they appear in the documents.

I use the LinearSVC model and adjust the hyperparameters to get the best accuracy score. I use classification report and confusion matrix to check the accurcy of the machine learning model.
