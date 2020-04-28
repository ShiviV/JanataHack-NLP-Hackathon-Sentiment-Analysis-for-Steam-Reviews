# JanataHack-NLP-Hackathon-Sentiment-Analysis-for-Steam-Reviews
NLP:Sentiment analysis

Imported necessary libraries like NLTK,Sklearn,pandas,numpy,seaborn and Loaded Dataset,Preprocessed data and checked
distributions of different variables ,Checked for null values ,duplicate values and statistical properties of data .
Visualized data using Wordcloud and did Text cleaning using Regular expressions,stemming and lemmatization
To check how well model is performing ,Splitted the dataset into Train and Test ,since models work on numbers and not strings
used Countvectorizer from scikit learn to represent them as count of words ,part of feature extraction.
Built a model with Logistic Regression,SVM,XGBoost,used K-Fold cross validation and Grid Search for parameter tuning and ensemble methods like Bagging ,AdaBoost, RandomForest to get better performance .
Improved performance from 60% to 85%.
