# Overview:

The importance of news is often difficult to interpret nowadays due to the abundance of peripheral information.
For hot topics like global warming and clean energy technology, there are a variety of information scattered all
over the web, which makes it a challenge to understand the topics of focus. Social media is a powerful resource 
with a wealth information, but must be carefully extracted in order to get information that are beneficial towards
the cause. This is not a simple task as social media data must be cleaned sufficiently to aggregate components that
can be used for comprehensive analysis.

This project uses natural language processing (NLP) to clean and analyze Twitter data. Unsupervised learning with 
vectorization and dimensionality reduction is utilized to cluster Twitter users by the most important topics. The most
interpretable set of clusters used term frequency- inverse document frequency (TF-IDF) vectorizer and latent semantic
analysis (LSA). The different five clusters were then visualized using several methods in order to understand the most 
important topics in each cluster. 

# Data:

The Twitter API was used to acquire tweets from Twitter handles of influencers in the clean energy industry. Between 2000 
to 3000 tweets were collected from each of the 100 users. These include journalists, authors, politicians, and clean energy
executives.

# Tools:

- `MongoDB` - stored Twitter data for each user
- `Spacy` - removed stopwords and special characters, lemmatized words
- `NLTK` - sentiment analysis using Vader library
- `Scikit-learn` - vectorization, dimensionality reduction, clustering
- `wordcloud` - created word cloud visualization of clusters
- `Plot.ly` - 3D plot of clusters
- `Seaborn` - kernel density estimation plots of sentiment analysis
