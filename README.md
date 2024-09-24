# Cornell Machine Learning Foundation NLP Project: AirBnB Analysis

This is the final project of the Cornell Machine Learning Foundation course. The goal was to explore common words and themes in Airbnb listing descriptions to better understand the characteristics of successful Airbnb listings. 

Due to constraints with the dataset we could use and limitations in NLP methods taught, this project was an attempt at applying the learned techniques. My understanding of various methods found online was limited, so I used subjective approaches to evaluate the models, which contain inaccuracies.

**Future Goals**: Rewrite the code and descriptions to enhance clarity and cohesion with the problem being addressed. Additionally, identify methods to evaluate NLP models.

**Note**: The data file was too large to be uploaded.

## Concepts

### Word Embeddings
Word embeddings are a way to represent words in a numerical format that captures their meanings, relationships, and context. Instead of treating words as individual entities, word embeddings place similar words closer together in a multi-dimensional space. This allows computers to understand the similarities and nuances in language.

### Word2Vec Model
Word2Vec is a popular model that creates word embeddings using neural networks. It predicts word associations based on context, helping to place similar words closer together in a multi-dimensional space.

### K-means Clustering
K-means clustering is an unsupervised learning technique that groups data points into clusters based on their features. In this project, it analyzes relationships between word embeddings, helping to identify patterns and themes in the data.

### Principal Component Analysis (PCA)
PCA is a statistical technique used for dimensionality reduction. It transforms high-dimensional data into a lower-dimensional space while preserving as much variance (information) as possible. In this project, PCA is used to visualize Word2Vec embeddings and their relationships by simplifying the complexity of the data.

### Summary of Techniques
- **Word Embeddings**: Representation of words in numerical format.
- **Word2Vec**: Model to create word embeddings using neural networks.
- **K-means Clustering**: Unsupervised method to group similar embeddings.
- **PCA**: Technique for reducing dimensions and visualizing embeddings.

#### Author: Ula Nguyen. August 2024.
