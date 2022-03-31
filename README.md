# Extractive Text Summarization


### Intoduction
Text Summarization is the process of creating a summary of a certain document that contains the most important information of the original one, the purpose of it is to get a summary of the main points of the document.

### Overview
* Automatic text summarization methods are greatly needed to address the ever-growing amount of text data available online to both better help discover relevant information and to consume relevant information faster.

* Our project is based on Extractive Text summarization. 
Extractive text summarization involves the selection of phrases and sentences from the source document to make up the new summary. Techniques involve ranking the relevance of phrases in order to choose only those most relevant to the meaning of the source.

* The main objective is to develop a model to summarize single as well as multiple documents entered by user in txt files as well as through Wikipedia Articles using various natural language processing techniques.

### Libraries Used

* [Numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [beautifulsoup](https://pypi.org/project/beautifulsoup4/)
* [Natural Language Toolkit](https://pandas.pydata.org/)
* [Rouge](https://pypi.org/project/rouge/)
* [Sumy](https://pypi.org/project/sumy/)

### Algorithms and concepts used

* TextRank
	* GloVe vector embeddings
	* Cosine similarity
* TF-IDF
* Luhn

### How to run

* Install the required libraries using pip, virtual environment or conda.
* Download the GloVe embeddings, extract and import the .txt file.
* Run `jupyter notebook`  in the terminal.

### Code Description

The various code files and folders are described here.

**Project code dataset:** Folder containing all the project codes, dataset and glove .txt file.

* **Algorithms:** Folder containing codes of all the three algorithms used for text summarization.
* **Evaluation text summarization:** Contains code to evaluate summaries and calculate the ROUGE-N metric.
* **Final with GUI:** Contains code with final GUI and textrank algorithm for text summarization.
