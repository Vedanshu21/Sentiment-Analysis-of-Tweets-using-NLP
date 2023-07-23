# Sentiment-Analysis-of-Tweets-using-NLP
It is an NLP-based Twitter sentiment analysis model that aids in overcoming the difficulties associated with tweet sentiment classification. The tweets will be categorized as having positive or negative sentiments. For this analysis, Sentiment140 Dataset is used to contain 1,600000 tweets categorized as positive and negative.
Below is a snapshot of the dataset.<br><br>
<img width="596" alt="image" src="https://github.com/Vedanshu21/Sentiment-Analysis-of-Tweets-using-NLP/assets/83238429/accb6fe1-c190-4bb1-b44f-cbfe7ba28158">

## Step-wise explanation of the techniques used :

1. Data Preprocessing <br>
2. Transforming Dataset using TF-IDF Vectorizer<br>
3. Building Model<br><br>

### Processes Involved in Data Preprocessing
1. Removing stopwords,<br>
2. Removing special characters like emojis, hashtags, etc.<br>
3. The text document is then converted into lowercase for better generalization.<br>
4. Punctuations were cleaned and removed, thereby reducing the unnecessary noise from the dataset.<br>
5. After that, we also removed the repeating characters from the words along with removing the URLs as they do not have any significant importance.<br>
6. At last, we then performed Stemming(reducing the words to their derived stems) and Lemmatization(reducing the derived words to their root form, known as lemma) for better results.<br>

### Transforming Dataset using TF-IDF Vectorizer

TF-IDF is an abbreviation for Term Frequency Inverse Document Frequency. This is a very common algorithm to transform the text into a meaningful representation of numbers which is used to fit machine algorithms for prediction.

### Model Used

For the classification of tweets, we have used the Bernaulli Bayes model
The Bernoulli or “Multivariate Bernoulli”  Naive Bayes may be expressed as the statistical method that generates outputs on a boolean basis by exploiting the desired text’s existence. This classifier feeds from Bernoulli Distribution which has a discrete nature.


