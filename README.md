# Twitter-Profanity-Analysis

A file consist full of twitter tweets by various users and there are many tweets consisting of racial slur words.

So Writing a program that can indicate the degree of profanity for each sentence in that file.


## Getting Started
 
Firstly Downloaded Dataset consisting of twitter tweets with the name of "tweet.csv" and a csv file consisting of bad-words with the name of "bad-words.csv".


## Built With

* Jupyter Notebook
* Python 3.6
* Pandas
* seaborn
* matplotlib
* wordcloud

## Results 

Profanity score of each line is calculated with this formula : (Total number of abusive words / length of the tweet) .
A csv file named "profanity_score.csv" is generated with the degree of profanity score for each tweet in the range of 0 to 1 , where 0 indicates that the tweets are normal and as we go towards 1 there are some racial slur present in the tweet.

## Author

Atharva Shirgave

