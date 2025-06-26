# Twitter Sentiment Analysis

## Introduction

The main goal of the task is to identify and analyse the sentiments of tweets adressed to California Department of Motor Vehicles(DMV). California DMV performs many day to day tasks, to name a few

* Licenses
* Registrations
* License plates


Twitter being an active source for people to express their opinions and experiences with any organisation, this analysis will be crucial for DMV to assess their performance. 

## Datasets

In the data folder you will find, 

* twitter_final_extract_cadmv.p - Contains about 200 sample tweets adressed to @CA_DMV twitter handle
* emotions_train.csv - Contains a set of prelabeled tweets with their corresponding emotions
* training_senti.csv - Contains a set of pre-classified tweets with their corresponding polarity (0- negative, 4- positive)

The file twitter_final_extract_cadmv.p is a python pickle file. You can open it through pandas as a dataframe by the following commands

```
import pandas as pd

tweet_df = pd.read_pickle('data/twitter_final_extract_cadmv.p')
```


## Task

With the above datasets, you would need to build models which can predict the emotions and sentiments of the tweets on twitter_final_extract_cadmv dataset. 

Once the predictions are made, you can analyse the following metrics by extracting the topics from the tweet,

* Average polarity per topic
* Top 3 most popular sentiments for each topic
* Overall average sentiment of the most popular tweets (you can combine the likes and retweet counts for this)
* Most discussed topics

#### Hint

You can extract the topic through python based keyword extractors such as yake (https://pypi.org/project/yake/)


## Deliverables

You can take upto 4 days from the time you receive this task. 

After you have completed the task, you can email us the Jupyter notebooks (training and analysis) and we will have a disucssion over the notebooks during the final round of interview. 

## Bonus

If you have time, you can try build a dashboard with all analytics that you have done in the task. 


Please reach out to balaji@stacknexus.io, if you have any question related to the task. 

Good luck! :)