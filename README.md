# Beginner's Introduction to NLP - Building a Spam Filter

## Introduction 
Natural language processing (NLP) refers to the field within artificial intelligence that deals with the interaction between
computers and humans using the natural language. This includes enabling computers to manipulate, analyse, interpret and generate
human language. 

This beginner's notebook was heavily inspired by [NLP with Python for Machine Learning Essential Training](https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training),
a LinkedIn course given by [Derek Jedamski](https://www.linkedin.com/in/derek-jedamski-8a887045/?trk=lil_course). I would like to hereby give him full credits and reference to his work and I also highly
recommend checking out his other courses on machine learning in Python.

## Problem statement
The goal for this repository is to summarise what I have have learned as well as recreate the the main project that was introduced in the course, a spam filter. 

The spam filter is a binary classifier that is capable of reading a random string of text and subsequently classify the text as one of two outcomes: 
either ham or spam. 

## Data description 
The spam filter was built using the SMS spam collection [dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) which contains a set of 5,572 SMS messages in English.

## Notebook content 
**0. Import libraries**

**1. Import and read data**

**2. Exploratory data analysis (EDA)**

**3. Feature engineering**

**4. Cleaning text**
- 4.1 Turn words into lowercase letters only 
- 4.2 Remove punctuation
- 4.3 Tokenise words
- 4.4 Remove stopwords
- 4.5 Stemming vs lemmatisation (word normalisation)
- 4.6 Putting everything together into a single *clean_text* function

**5. Vectorisation**
- 5.1 How (CountVectorizer + TfidfTransformer) works
- 5.2 How TfidfVectorizer works

**6. Modelling**
- 6.1 Train-test-split approach (using RandomForestClassifier and GradientBoostingClassifier)
- 6.2 Pipeline approach 

## Medium article 
Link to the full project write-up on Towards Data Science [here](https://towardsdatascience.com/a-beginners-introduction-to-nlp-building-a-spam-classifier-cf0973c7f42c).

## Project inspiration & reference
[NLP with Python for Machine Learning Essential Training](https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training) by [Derek Jedamski](https://www.linkedin.com/in/derek-jedamski-8a887045/?trk=lil_course)

## Follow me
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/jasonchong914)
- [Medium](https://www.medium.com/@chongjason)
