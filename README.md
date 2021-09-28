# Reddit-Sentiment-Analysis
It is a Natural Language Processing Problem where Sentiment Analysis is done by classifying the sentences showing and not showing anxious behaviour as 1 and 0 respectively by machine learning models for classification, text mining, text analysis, data analysis and data visualization. 
The objective is to detect anxiety in a sentence.

# Process Flow

1. Using web scrapping tools, data from Reddit (https://www.reddit.com/r/Anxiety/) is extracted. 
2. A database of only 500 sentences from the body of the reddit posts is created. 
3. First 200 sentences from the database are annotated with 0-1 indicators. 0 means not anxious, and 1 means anxious.
4. 4 different models that learns on the annotated portion of the database are built.  
   Algorithms used are:
   1. Random Forest Classifier
   2. Logistic Regression
   3. Decision Tree Classifier
   4. Naive Bayes Classifier
5. From the most accurate model, anxiety of the 300 other sentences is predicted.
