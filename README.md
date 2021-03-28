# Twitter sentiment analysis related to Covid-19 (2020-07-24 to 2020-08-30)
### Mainly use nltk library
### Datasource: https://www.kaggle.com/gpreda/covid19-tweets
### <li>clean the text by:<br> remove url;<br>convert to lower case;<br>remove punctuations,stopwords(from nltk library package),numbers
### <li>SentimentIntensityAnalyzer() to generate polarity value and hence label it as:
### <li>-- positive<br><li>-- neutral<br><li>-- negative 
### All 3 sentiments are roughly contributes of 1/3 of population
### <li> daily sentiment trend lines 
### <li> word cloud (top 100 words)


## <li>Highest freq word
![highest freq word](https://github.com/eduhkdcx/COVID-19-tweets-sentiment-analysis/blob/main/high_freq_word.png)
## <li>Sentiment barplot
![sentiment](https://github.com/eduhkdcx/COVID-19-tweets-sentiment-analysis/blob/main/sentiment.png)
## <li>Sentiment change trend
![trend](https://github.com/eduhkdcx/COVID-19-tweets-sentiment-analysis/blob/main/trend_line.png)
## <li>Word Cloud
![wordcloud](https://github.com/eduhkdcx/COVID-19-tweets-sentiment-analysis/blob/main/wordcloud.png)
  
## <li>Naive Bayes Model Result
![nb cm](https://github.com/chenx-git/COVID-19-tweets-sentiment-analysis/blob/main/nb_cm.png)
![class report](https://github.com/chenx-git/COVID-19-tweets-sentiment-analysis/blob/main/nb_class_report.PNG)
