# Text message analysis with NLP
   This study takes a deeper look into the historical text messages retrieved from students' communication system by applying various machine learning techniques. The purpose of the study is to identify communication trends, evaluate effectiveness of the existing process and to provide any insight from historical data.  

# Methodology and Data
   ABC University has been using third party text messaging system for text based communication. For this study, I am using Spring 2020 and Summer 2020 text message data which was pulled from that system. For the analysis of the data, I used Python as the programming language along with numerous software libraries such as pandas, math, numpy, sklearn, matplotlib and etc. In addition, I have used Natural Language Processing (NLP) which is a machine learning (ML) techniques that helps to understand, interpret and manipulate human language using artificial intelligence. Rather than a human reading all the text messages and identify different trends, key words and the sentiments, NLP helps with processing the raw data and extract meaningful information.
   
# Data Exploration 
   The focus here is to explore the large set of unstructured data and uncover any initial patterns, characteristics, and points of interest. It is not expected to reveal every bit of information the dataset holds in this step, but rather to help create a broad picture of important trends and major points to study in greater detail. A combination of manual and visualization methods were used during this step, and any irrelevant data was removed to facilitate the analysis in further steps. 

# Text Analysis with NLP
NLP is an excellent method to analyze and interpret textual data such as student responses. It is an ML technique that machines use to understand the human language like text, speech, emoji, and vastly used in the industry these days (i.e Siri and Alexa).

# Cleaning, removing stop words and stemming
It is important to clean your data by removing all the unnecessary words, symbols, and any text that will not help you to do meaningful analysis. Below functions will help us with cleaning, removing the stopwords but we also need a few libraries to help with that.After cleaning our data, we can populate the word cloud for our analysis. Word Cloud is one of the most effective ways to represent this data, which indicates the importance of the text by size, depth of the color, and the boldness of the word.

# Word Cloud extended — Ngram exploration
Ngrams are simply contiguous sequences of n words. Looking at most frequent n-grams can give us a better understanding of the context.
The below function presents the most frequent non-stop words in a bar chart.

# Sentiment Analysis
Sentiment analysis is a widely used tool with an NLP toolkit that classifies the sentiment of textual data such as student response in an automated way. First, we can find the distribution of sentiment using a polarity histogram. A polarity is a floating-point number that lies in the range of -1 to 1 where 1 means a positive statement and -1 means a negative statement.
