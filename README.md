## Spam-News-Detection
#Tools Used:  (Mention the tools used in this project)
●	Jupyter Notebook
●	A fake news dataset
●	A real news dataset

# Working Procedure: 
●	Importing important libraries such as numpy and pandas.
●	Importing the fake and real news datasets.
●	Data cleaning which includes dropping all irrelevant columns such as title, subject and date from the datasets as they’re not crucial in determining the authenticity of the news.
●	Adding labels, that is, 0 to the real news rows, and 1 to the fake news rows.
●	Combining the first dataset which contains only the text and label columns from fake news, with the second dataset which contains these attributes only. A combined dataset is made.
●	Check for null values in the dataset.
●	Shuffling the dataset so there isn’t biasing towards 0 or 1 values.
●	Cleaning and preprocessing data by importing libraries such as nltk and re. re works on fuzzy logic.
●	Writing a function which contains reject code, used to remove special characters and stopwords from the dataset, since these aren’t of any use.
●	Applying this function to every individual row in the dataset to clean them all.
●	Importing Tfidfvectorizer from sklearn library.
●	Creating a vectorizer instance to vectorize all the data in the dataset.
●	Creating a separate x and y 2D array from the dataset. X contains the text while y contains the label.
●	Creating training and testing data from x and y, testing size is 20% of overall data.
●	Converting the vectorized x and y training and testing datasets to pandas dataframe format.
●	Importing models such as naïve bayes and applying them to the dataset.
●	Checking the accuracy score of the models pertaining to the predicted y dataset and the actual y testing dataset.
●	Testing an example of a text to see whether its fake or real by converting it to an array and vectorizing it.
●	Predicting whether this news is fake or not.
●	The predicted outcome must be the same as the actual outcome. 

# Learning Outcomes: 
●	Learnt the importance and usage of libraries such as NumPy and Pandas. Also learnt how to manipulate the data using these libraries, eg, dropping unnecessary columns and combing different sets of data.
●	Learnt how to add labels to the dataset to classify it properly(0 for real news, 1 for fake news). Learnt how to transform and merge datasets on the basis of certain attributes.
●	Learnt how to preprocess the data and remove unnecessary characters, often called as stopwords by using libraries such as NLTK for data cleaning.
●	Briefly implementing the concept of TF-IDF vectorization using TfidfVectorizer from scikit-learn library. With this, we converted textual data into numerical values.
●	Learnt to apply machine learning models such as Naïve Bayes model to the dataset and calculating the accuracy of these models for the dataset.
●	Testing the model on news text examples to determine the authenticity of news text.
