# Sentimental-Analysis-Project

Sentiment Analysis in python to determine the hidden expressions present in the unstructured text data format and representing as positive, negative or neutral.
Took scraped data .csv file as input raw data and used the headlines column.
Tokenized all the sentences into words using NLTK tokenizer, removed special characters and all the stopwords using NLTK "english" stopwords data.
Divided all the words into positive, negative and neutral using for loop and sentimental_analsyser of NLTK. 
Created wordcloud of most used positive,negative and neutral words. 
Checked polarity scores using sentimental_analyser of NLTK and created a new dataframe with polarity scores of all the headlines.
Finally, created visualization using matplotlib to get useful insights about the data.  


Libraries used - Python, Pandas, Matplotlib and NLTK.
