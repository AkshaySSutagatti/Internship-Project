# Internship-Project
State wise Stock Market Sentiment Analysis using Web Scrapping 

Aim of the Project:

The main aim of the project is to find state-wise sentiment analysis on stock 
market for planning of social media keywords and kind of advertisement. This 
particular project requires web scrapping tools to collect text data from social 
media platforms like Facebook, Instagram, Twitter, Pinterest. The collected data 
is then processed using NLP Algorithm for specific keywords and creating 
WordCloud for graphical representation of Keyword frequencies, so that we get 
an idea which keywords are appearing more frequently. At the end, output will 
be a list of keywords that can be used for statewise sentiment analysis regarding 
Stock Market for social media marketing and Advertisements.

Approach:

a. Data Collection by Web Scrapping:
It is a automated process that runs on chrome driver and opens social 
searcher, which links to google search, Facebook, Instagram, Twitter, and 
Pinterest domains. Search keywords are provided state-wise like ‘Stock 
Market Learn Karnataka.’ Websites of the platforms opened sequentially 
according to search keywords and data is extracted from all the 
mentioned platforms. The output would be a .txt file that consists of textbased data.

b. Data Cleaning, Keywords Extraction and Word 
Cloud:
Merged all the text files which were generated on each search keyword 
using merging tools. Further the merged .txt file is processed through 
KeyBERT to get Keywords and building WordCloud using the keywords.
Using the word cloud we can understand the sentiment of the particular 
state regarding Stock Market. Using this sentiment analysis the client 
channelized the ads accordingly to each states.

Expected Results:
The result is a list of keywords that can be used for state-wise sentiment 
analysis of the stock market. By analyzing the keywords output by keyBERT, a 
user can better plan their social media advertising by understanding what types 
of keywords they need to use on Facebook, Twitter, Pinterest, and Instagram, as 
well as the way people from different states view the stock market, and by using 
Word Cloud, the keywords are visualized based on word frequency extracted 
from the input text file. The word cloud (image) is used to understand the 
overall sentiment of an individual state towards the stock market in a single 
image whereas KeyBERT helps in determining the specific keywords that need 
to be considered before selecting keywords and designing advertisement 
creatives
