# Unsupervised Learning: Feature extraction and clustering with NLP on texts to facilitate classification.
For this project, I scraped a number of fictional short stories from Tor.com, a publisher of speculative fiction usingi scrapy. 

I used several natural language processing techniques to preprocess and extract features, including lemmatizing,, TF\*IDF LDA, and SVD.

Using these features, I trialed several clustering algorithms to group similar stories and tried to evalute the clusterings.

The cluster labels were added to the td\*idf vector features and used for classification modeling.

The main notebook is [here.](../master/scifi_stories.ipynb)
