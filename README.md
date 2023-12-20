# ChatGPT-Sentiment-Analysis

Introduction:
    This program aims to perform sentiment analysis on a dataset of tweets. It uses various natural language processing techniques and pre-trained models to analyze the sentiment of the tweets and generate insights. The program includes data preprocessing, sentiment analysis using different libraries, visualization of results, and comparison of sentiment scores from different models.

Outline of Solution:

    Installation:
        Ensure that Python is installed on your system (version 3.6 or higher).
        Install the required packages by running the following commands:
        !pip install emoji --upgrade
        !pip install TextBlob
        !pip install autocorrect
        !pip install pyspellchecker
        !pip install tweet-preprocessor
        !pip install transformers
        !pip3 install torch torchvision
        !pip install xformers
        !pip install pattern
        !pip install pandas
        !pip install nltk
        !pip install numpy
        !pip install string
        !pip install emoji
        !pip install textblob
        !pip install wordcloud
        !pip install matplotlib

    Dataset:
        The dataset used for sentiment analysis is stored in a CSV file, "chatgpt-tweets-data-20230310-20230322.csv".
        
    Running the Program:
        Open the code file "FinalProject 20230714 0322.ipynb" in a Python environment (e.g., Jupyter Notebook, Google Colab).
        Execute each code cell in sequence.
        The program will install the required packages, load the dataset, perform data preprocessing, sentiment analysis, and generate visualizations.
        The final results and visualizations will be displayed in the output.
    
    Example Input and Output:
        Input: CSV file containing tweets data
        Output: Sentiment analysis results, word clouds, bar charts, scatter plots, and comparison of sentiment scores from different models.
    
    Setup and Execution:
        Download the code file "FinalProject 20230714 0322.ipynb".
        Open the code file in a Python environment (e.g., Jupyter Notebook, Google Colab).
        Upload the dataset file ("chatgpt-tweets-data-20230310-20230322.csv") to the same directory as the code file.
        Execute each code cell in sequence by running them one by one.
        The program will generate the results and visualizations, which will be displayed in the output.
    
    Dataset Link:
        The dataset used in this program can be found at the following link:
        https://www.kaggle.com/datasets/sanlian/tweets-about-chatgpt-march-2023/download?datasetVersionNumber=2
    
    Additional Information:
	If given AttributeError: module 'preprocessor' has no attribute 'clean', please complete these steps:
		pip uninstall preprocessor
		pip uninstall tweet-preprocessor
		pip install tweet-preprocessor

        The code file includes comments explaining the purpose of each code block and function.
        Enjoy analyzing sentiment in tweets using this program!
