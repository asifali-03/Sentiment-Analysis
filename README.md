Python Sentiment Analysis Brief Description

Restaurant-Reviews-using-NLP
A simple project in python which reads a tsv file, cleans the restaurant reviews(text), geneartes a bag-of-words model and uses a classifier which tells whether the review is a positive one or a negative one. Getting Started Prerequisites Python 3.6+ NLTK TextBlob VADER Installation pip install nltk Use code with caution. Dataset The dataset contains the particular reviews about some topics. Usage Python import sentiment_analyzer # Assuming your main code is in 'sentiment_analyzer.py' text = "This is a great movie. I loved it!" result = sentiment_analyzer.analyze_sentiment(text) print(result)

Output example: {'sentiment': 'positive/negative'}
Use code with caution. Explanation of Techniques Preprocessing: Tokenization Stop word removal Sentiment Models: TextBlob (rule-based) VADER (rule-based)
