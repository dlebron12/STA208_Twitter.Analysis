# STA208_Twitter.Analysis

Here is some fun statistics done with the Trump tweets were they see that most of the negative tweets come from an Samsung phone (him) and the positive/ white house news come from an Apple phone.  http://varianceexplained.org/r/trump-tweets/


Anywho! 

Welcome to this repository! In the papers section, you will find some of the literature read to do this project; it has papers adressing different type of approaches for the sentiment analysis.

The flow of the jupyter notebooks is:

$\textbf{Data_Processing.py.ipynb} where both the Trump and Sentiment Analysis 140 Tweets are processed to remove punctuation, stopwords, hashtags, urls, capitalizations between other grammatical issues that may arise in the tweets.  Also in this notebook, the sentiment data is subsetted to only include 50k tweets half of positive and negative sentiment.

![Tweets Descriptive Analysis.ipynb] in this notebook, you can find a little descriptive summary, such as the amount of words/token found in the set of tweets, how many url, hastags were removed from the text. So you have a sense of how important data prepping is.  Also here frequency of words were computed for both positive, negative sentiment and trump tweets and visualized in a word cloud.  

![Classification Models.ipynb] contains all the code that fits the baseline, svm, logistic regression and NN models, with parameter tuning and graphical visualization of model performance via ROC curves.  In addition, the best model was selected and validated using Trump Tweets.  After acquiring the predictive labels for this a cloud of words and content review is made to address that this labels could be legit. 


A lot still can be done regarding to this project, that could be continued in the future! Is a very interesting way of applying Machine Learning Methods into something that is actually used in the present. 



