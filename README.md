20 NewsGroup Dataset

Apply BERT Topic Modeling on the 20 News group dataset to identify the topics and keywords associated with each topic.

Evaluated the topics generated and the words representing the topic along with the representative documents using LLM. An evaluation prompt was sent to rate the coherence between topic, topic key words and documents
The average of the coherence across all the topics was calculated

Also applied a modified version Topic Modeling using a similar approach to BERT.

Applied Gensim Doc2Vec for embedding
Applied PCA for dimensionality reduction
Applied Gaussian Mixture model clustering
Applied the reverse CF TFIDF to get the relevant keywords associated with each topic and the documents.
Also applied the same evaluation with LLM
