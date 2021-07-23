# nlp_project

## Abstract

------------

Anxiety disorders are the most common mental illness in the U.S. 40 million adults or 18.1% of the population are affected every year.
Anxiety disorders are highly treatable, yet only 36.9% of those suffering receive treatment. People with an anxiety disorder are three to five times more likely to go to the doctor and six times more likely to be hospitalized for psychiatric disorders than those who do not suffer from anxiety disorders. Giving loved ones the ability to identify signs and help them reach out could make a huge difference.


------------
### Data

[Kaggle - Sentimental Analysis for Tweets](https://www.kaggle.com/gargmanas/sentimental-analysis-for-tweets)

### Algorithmn 

I used TDIF from sklearn to vectorize the corpus to extract the weight of each word on the entire document and then performed topic modelling using NMF. What NMF did was create topics based of words that occur together in the documents of the corpus. Each topic has the weight of the words that make up the topic, so it's easier to interpret which words had the impact on a specific topic. 