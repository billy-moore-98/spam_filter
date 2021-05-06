# spam_filter

In this project I have explored the multinomial Naive Bayes' algorithm and applied it to build a text SMS spam filter. The model has an accuracy of over 90%.

The dataset used for both training and testing of the algorithm was created by Tiago A. Almeida and José María Gómez Hidalgo, and can be found at [The UCL Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). The dataset contains SMS messages that are already classified as being spam or not.

The Naive Bayes algorithm will assess whether each individual SMS message is spam or not by evaluating the word contents of the message. As the algorithm is 'Naive', it assumes there is conditional independence between the words in the message.

Overall, the algorithm correctly predicts 98.7% of the test data. The messages which were wrongly predicted contained various elements which may have escaped the algorithm capabilities such as punctual emojis, abbreviations and acronyms.
