This project aims to visualize the word embeddings of a set of Spanish words using the Spacy library and the PCA (Principal Component Analysis) dimensionality reduction technique with the Scikit-Learn library.

First, the code begins by installing and loading the Spacy library in Python. Then, download the pre-trained model "es_core_news_lg" to convert the words into high-dimensional vectors.

The text is then rendered with space to remove punctuation, and some example words are selected from the text to reduce the dimensionality of their vectors.

The PCA technique is then used to reduce the dimensionality of the vectors to two dimensions, which makes it easier to visualize them in a 2D graph. The plot is created using the Matplotlib data visualization library.

Finally, the graph that visualizes the word embeddings of the selected words in two dimensions using the PCA technique is shown. The resulting visualization can help you better understand the relationship between the words and the similarity between them.