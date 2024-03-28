---
layout: post
title: "Find Data Source"
author: "Zhou Mozhe"
categories: journal
tags: [documentation,sample]
---
### Search for the Data Source  
  
The data source required for this dissertation encompasses news data, stock data, and knowledge graph data.  
  
#### News Data Source Options  
  
1. **Dataset Bloomberg and Reuters (2006-2013)**    
Used in the article "Knowledge-Driven Event Embedding for Stock Prediction" by Xiao Ding, Yue Zhang, Ting Liu, and Junwen Duan.    
Source: [philipperemy/financial-news-dataset: Reuters and Bloomberg](https://github.com/philipperemy/financial-news-dataset)    
Contains 450,341 news from Bloomberg and 109,110 news from Reuters.    
**Note**: These datasets are no longer publicly available due to copyright issues but have been requested and obtained from the author.  
2. **4.5 Million Headlines (2007-2022)**    
Sourced from the top 10 news outlets by internet viewership.    
Source: [4.5M headlines from 2007-2022 [10 largest sites]](https://www.kaggle.com/datasets)    
Includes: The New York Times, CNN, FOX News, New York Post, BBC, etc.  
3. **FNSPID: A Comprehensive Financial News Dataset in Time Series**    
By Zihan Dong and Fu Yuan.    
Comprises 29.7 million stock prices and 15.7 million time-aligned financial news records for 4,775 S&P500 companies, covering 1999 to 2023.    
Sourced from 4 stock market news websites.  
  
#### Stock Data Source Options  
  
1. **Standard & Poor's 500 (S&P 500) Index and Individual Stocks**    
Obtain indices and prices from Yahoo Finance.  
  
#### Knowledge Graph Data Source Options  
  
1. **YAGO**    
Used in the article "Knowledge-Driven Event Embedding for Stock Prediction" by the authors mentioned above.  
2. **Wikidata**    
Due to its close association with Wikipedia, Wikidata potentially contains a significant amount of structured data regarding publicly traded companies.  
  
#### Future Plans  
  
1. Develop a program to gain a clearer understanding of the knowledge base, integrate with knowledge graphs, and perform basic searches.  
2. Conduct a thorough review of the datasets and perform preliminary preprocessing.