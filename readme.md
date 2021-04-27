# CSCI 6509 Winter Term Project

## Title: Deep Language Model Representation of Document Clustering

### Abstract : 
Powerful document clustering models are important as they are able to efficiently process large sets of documents. These models can be useful in many fields, including general research. Searching through large corpora of publications can be a slow and tedious task; such models can reduce the time of this significantly. We investigated different variations of a pre-trained BERT model to find which is best able to produce word embeddings to represent documents within a larger corpus. These embeddings are reduced in dimensionality using PCA and clustered with K-Means in order to gain insight into which model is able to best differentiate the topics within a corpus. It was found that out of the tested BERT variations, SBERT was the best model for this task.

### Developed by:
* Rakshit Makan



### Code Implementations:
* Prerequisites:
    * Python 3.7 or later
    * Anaconda 
    * Jupyter Notebook


* Dependencies:
    The project uses multiple python libraries which are required to run this code. To install the code please run below code snippit in anaconda prompt.

    `pip install -r requirements.txt`
    
* NLP_Final_Project_Code.ipynb ** Note: throughout this file, we import word embeddings for each model in its corresponding file in the data/ folder. These are the word embeddings produced by each model during testing, we import them from a saved file as generating them from the model itself uses a lot of memory (8GB+), and may risk crashing the testers computer.


* BERT_base_knowledge_colab.ipynb
