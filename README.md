# ChatGPT Sentiment Analysis Project

## Project Overview
- **Title:** ChatGPT Sentiment Analysis
- **Authors:** Mitchell Breeden, Rock Chan, Brian Monter, Eliza Punnoose
- **Course:** AIT-526-007
- **Institution:** George Mason University
- **Date:** July 10, 2023

## Project Description
Objective: This program aims to perform sentiment analysis on a dataset of tweets. It uses various natural language processing techniques and pre-trained models to analyze the sentiment of the tweets and generate insights. The program includes data preprocessing, sentiment analysis using different libraries, visualization of results, and comparison of sentiment scores from different models.

## Data Sources
- `chatgpt-tweets-data-20230310-20230322.csv`: Dataset used for sentiment analysis, containing tweets data.

## Methodology
- **Tools Used:** Python, Jupyter Notebook, Pandas, TextBlob, autocorrect, pyspellchecker, tweet-preprocessor, transformers, torch, xformers, pattern, numpy, string, emoji, matplotlib, wordcloud.
- **Features:** Sentiment analysis of tweets, visualization of sentiment trends.
- **Approach:** Data preprocessing, analysis using different libraries, visualization, and comparison of sentiment scores.
- **Notes:** If given AttributeError: module 'preprocessor' has no attribute 'clean', please complete these steps:  
	- pip uninstall preprocessor  
	- pip uninstall tweet-preprocessor  
	- pip install tweet-preprocessor  

## Results and Conclusions
- Insights into sentiment trends in tweets.
- Visualization of sentiment analysis results using word clouds, bar charts, scatter plots, and comparisons of different models.

## Additional Resources
- `Script.ipynb`: Python Jupyter Notebook for analysis.
- `Presentation.pptx`: Overview of project findings.
- `Report.pdf`: Detailed project report.

## Contact Information
- Mitchell Breeden, Student, George Mason University.
- Email: breedenmitch@gmail.com
  
## Acknowledgments
- Maryam Heidari, Course Instructor.
  
## Sources
- **Dataset Sources:**
	- ANIL. (2023, March 25). Twitter Sentiment Analysis for ChatGPT. _Kaggle_. [Link](https://www.kaggle.com/code/sanlian/twitter-sentiment-analysis-for-chatgpt)
- **References:**
	- Taecharungroj, V. (2023, February 16). “What Can ChatGPT Do?” Analyzing Early Reactions to the Innovative AI Chatbot on Twitter. _Big Data and Cognitive Computing_; MDPI. [DOI](https://doi.org/10.3390/bdcc7010035)
	- Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003, January). Latent Dirichlet Allocation - Journal of Machine Learning Research. _Latent Dirichlet Allocation_. [PDF](https://jmlr.org/papers/volume3/blei03a/blei03a.pdf)
	- GeeksforGeeks. (2023, April 6). What is sentiment analysis?. _GeeksforGeeks_. [Link](https://www.geeksforgeeks.org/what-is-sentiment-analysis/)
	- Sahagian, G. (2021, April 13). What NLP Library you should use for your sentimental analysis project. _Medium_. [Article](https://medium.com/geekculture/what-nlp-library-you-should-use-for-your-sentimental-analysis-project-bef6b357a6db)


