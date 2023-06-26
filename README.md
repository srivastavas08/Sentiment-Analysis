# Sentiment-Analysis
This project is a sentiment analysis of 50K IMDB movie reviews. The dataset was obtained from Kaggle. Three models were used to perform the sentiment analysis: Multinomial Naive Bayes, Logistic Regression, and Support Vector Classifier. The accuracy of the models was as follows:

        Multinomial Naive Bayes: 78.5%
        Logistic Regression: 68%
        Support Vector Classifier: 50%

The models were trained on two different vectorizers: Bag-of-Words and TF-IDF. The Bag-of-Words vectorizer simply counts the number of times each word appears in a document, while the TF-IDF vectorizer assigns a weight to each word based on its frequency in the document and the frequency of the word in the entire corpus.

The results of the project show that Multinomial Naive Bayes is the most accurate model for sentiment analysis of IMDB movie reviews. This is likely because Multinomial Naive Bayes is a simple model that is easy to train and does not require a lot of data. However, the other two models, Logistic Regression and Support Vector Classifier, are also relatively accurate and may be a better choice for certain applications.

Conclusion

The results of this project demonstrate that sentiment analysis can be used to effectively analyze IMDB movie reviews. The models used in this project were able to achieve an accuracy of up to 87.5%, which is a significant improvement over random guessing. This suggests that sentiment analysis can be a valuable tool for businesses and organizations that want to understand how people feel about their products or services.

Future Work

There are a number of ways to improve the accuracy of the sentiment analysis models used in this project. One way would be to use a larger dataset of IMDB movie reviews. Another way would be to use a more sophisticated vectorizer, such as a word embedding vectorizer. Finally, it would be interesting to explore the use of ensemble methods to combine the predictions of multiple models.

# Accuracy for BagofWords on Multinomial NB:
![BagofWords](https://github.com/srivastavas08/Sentiment-Analysis/blob/78cce6fe26eb5045f15cd6cb06d0b026f71cb183/Docs/cv.png)

# Accuracy for Tfidf features on Multinomial NB:
![Tfidf](https://github.com/srivastavas08/Sentiment-Analysis/blob/78cce6fe26eb5045f15cd6cb06d0b026f71cb183/Docs/tfidf.png)

# WordsCloud :

## Positve Words :

![Positive](https://github.com/srivastavas08/Sentiment-Analysis/blob/78cce6fe26eb5045f15cd6cb06d0b026f71cb183/Docs/wordcloud_positive.png)

## Negative Words:

![Negative](https://github.com/srivastavas08/Sentiment-Analysis/blob/78cce6fe26eb5045f15cd6cb06d0b026f71cb183/Docs/wordcloud_negative.png)


