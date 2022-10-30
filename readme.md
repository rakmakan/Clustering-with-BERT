# CSCI 6509 Winter Term Project

## Title: Deep Language Model Representation of Document Clustering

### Abstract : 
Powerful document clustering models are essential as they can efficiently process large sets of documents. These models can be helpful in many fields, including general research. Searching through large corpora of publications can be a slow and tedious task; such models can significantly reduce this time. We investigated different variations of a pre-trained BERT model to find which is best able to produce word embeddings to represent documents within a larger corpus. These embeddings are reduced in dimensionality using PCA and clustered with K-Means to gain insight into which model can best differentiate the topics within a corpus. We found that SBERT was the best model for this task out of the tested BERT variations.



### Code Implementations:
* Prerequisites:
    * Python 3.7 or later
    * Jupyter Notebook


* Dependencies:
    The project uses multiple python libraries, which are required to run this code. To install the code, please run the below code snippet in the anaconda prompt.

    `pip install -r requirements.txt`

* Python Notebook:  There are two python notebooks :[1] NLP_Final_Project_Code.ipynb and [2] BERT Cosine Similarity Test.ipynb

     *  The NLP_Final_Project_Code.ipynb contains the code base for evaluating the BERT textual embeddings for clustering. We have used PCA for dimensionality reduction and K-Means for clustering. The embeddings are calculated separately and stored in the CSV file in the **./data** folder. 
     
     * In BERT Cosine Similarity Test.ipynb, we are testing the ability of BERT embedding to capture the similarity between the documents. For this, we manually grouped files based on their content 1) Group of similar files and 2) Group of dissimilar files. Then we measured the cosine similarity between each group. We hypothesized that BERT embeddings could detect similarities among the document based on their pretrained representation. We also evaluated SBERT, which proved to provide a better representation than BERT's different variants. 
