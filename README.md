# ML_DocumentModeling

This repository consists of visualizations and results of different document modeling and clustering techniques performed on 20Newsgroups dataset. 

20Newsgroups dataset has almost 20,000 documents.

First Dataset is cleaned by removing stop words , lowering the words and lemmatization. Second, two vocabularies are created – one with all the words and the other 
with the most frequent 2000 words. Built Bag Of Words (BOW) model, TFIDF model, LDA model, and Doc2Vec model on both the vocabularies.

Topics are visualized using PyLDAvis and Word cloud visualization techniques. Word embeddings and Document embeddings are visualized using PCA and t-SNE.
K-means clustering is performed on all these document models (BOW, TF-IDF, Doc2Vec, LDA).
The results of different vocabularies, different topic models, and various clustering outputs are analysed and compared.

Sklearn, genism, nltk, seaborn, and matplot libraries are used.

**Visualization of topics using PyLDAvis and Word Cloud**

![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/PyLDAvis.png?raw=true)

![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/WordCloud.png?raw=true)

**Document Embeddings**

![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/DocEmbeddings.png?raw=true)

***K-means of different document models***

**k-means on BOW**
![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/K-means_BOW.png?raw=true)
**k-means on TF-IDF**
![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/K-means_TFIDF.png?raw=true)
**k-means on LDA**
![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/K-means_LDA.png?raw=true)
**k-means on Doc2Vec**
![alt text](https://github.com/JayavardhaniKathika/ML_DocumentModeling/blob/main/K-meansDoc2Vec.png?raw=true)

