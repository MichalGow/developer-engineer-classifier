# Sklearn SVN Classifier in natural language processing
Python notebook, showing how to create an SVM Classifier distinguishing between software engineer and software developer job descriptions.

# What this is for?
The notebook shows how to create an SVM classifier to find out if a job description is for a software developer or a software engineer.

# Where is the training dataset taken from?
https://www.kaggle.com/PromptCloudHQ/us-technology-jobs-on-dicecom/data

# What does it do?
* Python NLTK library is used to perform data cleaning.
* Python Sklearn library is used to train the SVM classifier.
* Python Matplotlib library is used to visualize the data.

# How to use it?
The program works in two iterations.

1. It creates feature vectors from a dataset. To do this uncomment (6a) and comment (6b) and run the notebook.
1. It enables you to manually choose the features. To do this, after running the above, uncomment (6b) and run the notebook from there.

The created classifier is saved into the ‘model’ folder as a Python pickle.
