## Mental Health on Twitter

This repository includes all the code and data sources from my capstone project.

### Requirements
Find the requirements file under 'requirements.txt' and run it on your computer by pip-installing each of the libraries and packages in your virtual environment.

### Data Collection
This folder contains the pseudocode for retrieving the datasets from Twitter, and the three disorders datasets, and one dataset that uses all disorder dataset combined. For security reasons, I cannot include the authorization keys for data requests publicly, but you can retrieve yours on developer.twitter.com, if you'd like to collect the data with the same script. 

### Semantic Similarity
In this folder you will find the code for each semantic similarity per disorder. It is essentially the same code, but used with different datasets. If you would like to replicate this, please download the datasets and run the respective scripts. You will also find a subfolder which contains all the labelled data after the semantic similarity analysis has been conducted.

### Sentiment Analysis with LIWC
In this folder you will find all the labelled files outputted from LIWC in csv format as well as the notebook with visual plots.

### Topic Modeling
Much like in the previous folders, here you will find each dataset and their respective notebooks containing the code that performs topic modeling.
