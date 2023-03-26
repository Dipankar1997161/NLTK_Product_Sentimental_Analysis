# NLTK_Product_Sentimental_Analysis

## Overview
Ratings analytics examine customer and product ratings from different channels to gain insights. These insights can be used to improve your products and services, create new products, or improve the overall customer experience.
Review analytics can also help you spot errors and customer complaints that can escalate and damage your brand. 

In this Repo, we will use 2 models along with NLTK to perform Review Analysis.


![image](https://user-images.githubusercontent.com/85514219/227402367-dec01317-eb25-438b-ae4a-8fdbdcfeb877.png)


## NLTK

NLTK is the primary platform for building Python programs that work with human language data. Classification, tokenization, stemming, tagging, parsing, semantic reasoning, industry-grade wrappers around his NLP libraries, and an active discussion forum.
NLTK has been called "a great tool for teaching and working with computational linguistics using Python" and "a great library for playing with natural languages".
Natural Language Processing with Python is a hands-on introduction to language processing programming. Written by the NLTK developers, it guides the reader through the basics of writing Python programs, manipulating corpora, classifying text, and analyzing language structures.

## VADER

VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains.

Check the repo for more information: https://github.com/cjhutto/vaderSentiment

    It uses "bag of words approach":
       1.Stop words are removed from here.
       2. Scoring of indiviual word refering to it as a positive or a negative.
       3. Finally combining all the words in the sentence for the final score.
       4. Relation between words isn't taken into account.

## RoBERTa

RoBERTa - Despite her name (Roberta is an Italian maiden name), she is not human, Roberta is an AI developed and can be downloaded from HuggingFace. Technically, from January 2018 to December 2021 she is a self-supervised natural language processing (NLP) model trained on over 124 million tweets.
The model I used is the base model trained on approx 58M tweets. The detailed description about the model can be found here: https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment

## Results
### Comparision on single ID
![plot compaision for vader and roberta](https://user-images.githubusercontent.com/85514219/227788285-caed2805-eb06-4848-862c-a2d8da2a7fff.png)

### Comparision on entire Dataset
![vader and roberta](https://user-images.githubusercontent.com/85514219/227788321-09ac0ad9-9fa2-4b86-8cf5-6f747a928038.png)


### Thank you
