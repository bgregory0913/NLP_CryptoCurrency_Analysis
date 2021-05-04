# NLP & NER Cryptocurrency Analysis


## Purpose:
To demonstrate the use of Natural Language Processing (NLP) and Named Entity Recognition (NER), I used 'nltk' (Natural Language Tool Kit) to run sentiment analysis on Bitcoin and Ethereum news articles then generate WordClouds for each coin on a matplotlib base. 

Using the 'spaCy' library and its 'displaCy' module, the news articles for each coin underwent NER processing to display an Entitiy Recognition model of the text.

This project uses [NewsAPI.org](https://newsapi.org/) to retrieve the latest news articles, specifically, articles focused around Bitcoin and Ethereum.


### Built With:
   * [Python](https://www.python.org/)
   * [JupyterNotebook](https://jupyter.org/)
   * [Pandas](https://pandas.pydata.org/)
   * [NaturalLanguageToolkit](https://www.nltk.org/)
   * [spaCy](https://spacy.io/)
   * [spaCy Visualizers](https://spacy.io/usage/visualizers)


### Installation
This project was written in Python on Jupyter Notebook. To setup an instance of this project on your own, you need to install Jupyter Notebook [JupyterNotebook](https://jupyter.org/), as well as the following Python modules (using pip demonstrated below):
    * pip install newsapi-python
    * pip install nltk
    * pip install wordcloud
    * pip install spacy
    * pip install matplotlib
    

### About the API:
Newsapi.org was used to import articles on Bitcoin and Ethereum. You can setup an account to get an API key for free and pull any article from the web on a specific topic, keyword, category, or all news articles in general. The developer version is free but limits the total daily requests, so don't exceed the API call limit. Visit [NewsAPI.org](https://newsapi.org/) for more information.
