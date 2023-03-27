# Twitter-Text-Classification
As a part of our final project for the Introduction to Text Mining course, my colleagues, Giovanna Chaves, Lucas Costa Santos, and I, Tobias Pfeiffer, conducted a study utilising Tweets to examine the potential impact of the congress insurrections in Brazil on citizens in Brasilia, where the events took place on January 8, 2023.


To collect data, we utilized the Twitter API (*twarc2*), to retrieve nearly 900,000 Tweets from the five largest cities in Brazil, namely Sao Paulo, Rio de Janeiro, Brasilia, Fortaleza, and Salvador. We focused on a period spanning one week before and after the aforementioned date. 
As a first step we preprocessed the data, namely tokensizing, stopword removal, and lower-casing. To classify the tweets we used two Machine Learning techniques: Latent Dirichlet Allocation (LDA) and the Naive Bayesian Classifier. After classifying the tweets into political, pro/contra Bolsonaro, and negative categories respectively, we used these labels to conduct various Difference-in-Difference regressions to test our hypothesis that citizens in Brasilia are more politically active, negative, and so on.
Our findings show that the proportion of political tweets or the Average Treatment Effect (ATE) in Brasilia is 1% higher compared to the control cities, although this difference is only significant at the 10% level. 


This project primarily focuses on utilizing natural language processing (NLP) techniques in the context of the Portuguese language. However, the task at hand was accompanied by significant challenges, particularly in regards to pre-processing and analyzing a substantial corpus of non-English tweets and textual data. Despite these challenges, our team proactively devised alternative approaches that deviate from traditional dictionary-based methods.


This repository contains a Jupyter Notebook with the code (*TermPaper-Final.ipynb*), a final paper (*paper.pdf*), and a preliminary presentation (*presentation.pdf*).
