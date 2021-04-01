# spam_filter

In this project, we will be building a spam filter using a multinomial Naive Bayes algorithm to classify whether incoming SMS messages are spam or not.

The dataset used for both training and testing of the algorithm was created by Tiago A. Almeida and José María Gómez Hidalgo, and can be found at [The UCL Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). The dataset contains SMS messages that are already classified as being spam or not.

The Naive Bayes algorithm will assess whether each individual SMS message is spam or not by evaluating the word contents of the message. As the algorithm is 'Naive', it assumes there is conditional independence between the words in the message which allows the following probability relationships to be developed (full derivation of the relationships can be found in the Appendix):

$$P(Spam|w_{1},w_{2},...w_{3}) \ = \ P(Spam) \ \Pi_{i=1}^{n} \ P(w_{i}|Spam)$$
$$P(Non-Spam|w_{1}, w_{2},...w_{3}) \ = \ P(Non-Spam) \ \Pi_{i=1}^{n} \ P(w_{i}|Non-Spam)$$

Where:

$w_{i}$ - the ith word of the message
