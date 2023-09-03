# Multi-Instance Learning with DeliciousMILDataset

### Description:

This notebook presents an implementation of Multi-Instance Learning (MIL) using the DeliciousMILDataset, a dataset consisting of text documents and their associated binary labels. The primary objective of this notebook is to explore and experiment with MIL approaches, comparing their effectiveness at both the document and sentence levels.
<br>
### Key Experiments:
<b>Document-Level Experiment</b>:
In this experiment, we work with vectorized text input at the document level. Multiple classifiers and hyperparameter settings are evaluated to assess their performance on the 
<br>
<br>
<b>DeliciousMILDataset</b>.
Sentence-Level Experiment with Clusters-Based Input:
In the second experiment, we introduce a unique approach by leveraging k-means clustering to extract features from bags of words and sentences. This replaces the standard feature extraction method commonly found in scikit-learn. This innovative approach offers more interpretability and customization in feature extraction while maintaining scalability for handling large datasets.
<br>
<br>
<b>Performance Metrics:</b>
The notebook reports the results of these experiments in terms of key performance metrics, including accuracy, precision, and recall. These metrics provide insights into the effectiveness of different MIL techniques and feature extraction methods on the DeliciousMILDataset.
<br>
<br>
This project serves as a valuable resource for those interested in Multi-Instance Learning and its practical applications in text classification tasks. By examining both document-level and sentence-level approaches, and comparing various classifiers and hyperparameters, it offers a comprehensive overview of MIL techniques and their impact on model performance.
<br>
<br>
Explore this notebook to delve into the world of Multi-Instance Learning and gain insights into how innovative feature extraction methods can enhance the interpretability and scalability of your machine learning models.
