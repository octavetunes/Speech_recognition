# Introduction:

The .tsv (removed from the repo) file contains phoneme vectors, or phoneme embeddings, that were obtained from a neural model of grapheme-to-phoneme (g2p) conversion. Each line in the file is a phoneme embedding, where the first entry in each line is the phoneme symbol in IPA, the rest of the 236 entries in each line are real-value numbers that represent the corresponding 236-dimensional vector.
Tasks:

    Conduct a small research on phoneme embeddings (VSM).
    Read the dataset into a suitable data structure (e.g., Pandas data frame, Python dictionary, Numpy array, etc.)
    Computing the pair-wise cosine similarity between the phonemes represented by the embeddings and obtaining a confusion matrix of similarity scores.
    Exploring the embeddings space with at different techniques. Perhaps, using dimensionality reduction and visualization (e.g., PCA, t-SNE), as well as a different clustering analysis.

Execution Instruction:

    Install Python 3
    Install PIP
    Run "pip install -r requirements.txt"
    Run "python SLR.py"

Implemented Functions:

    Pairwise Cosine Similarity Heatmap/Confusion Matrix
    Agglomerative Clustering & Dendrogram Visualization
    Priniciple Component Analysis (PCA)
    Independent Component Analysis (ICA)
    t-Distributed Stochastic Neighbor Embedding (t-SNE)
    Multidimensional Scaling (MDS - Metric)
    PCA - DBSCAN Clustering
