# spam_filter

In this project, we will be building a spam filter using a multinomial Naive Bayes algorithm to classify whether incoming SMS messages are spam or not.

The dataset used for both training and testing of the algorithm was created by Tiago A. Almeida and José María Gómez Hidalgo, and can be found at [The UCL Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). The dataset contains SMS messages that are already classified as being spam or not.

The Naive Bayes algorithm will assess whether each individual SMS message is spam or not by evaluating the word contents of the message. As the algorithm is 'Naive', it assumes there is conditional independence between the words in the message.
