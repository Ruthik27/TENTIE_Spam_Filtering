# TENTIE - The Spam Filtering Program

## Project Description
With the increase in advanced technologies, it has revolutionized how people communicate. Communication done via electronic mail (e-mail) has become easier and faster. However, it has also contributed to rapid dissemination of unwanted messages, e.g. spam emails. Spam emails pose many threats, such as harm to personal devices and or theft of personal information. Inspired by Paul Graham's work, this project addresses this issue by creating a spam filter using state-of-the-art methods in machine learning and artificial intelligence: Naive Bayes and Deep Learning. 

## Results
Two Naive Bayesian classifiers are generated. The sensitivity and specificity scores for the Naive Bayesian classifier using CounterVectorizer is 90.6 percent and 96.8 percent, respectively. Its false positive rate is 12.5 percent. For the Naive Bayesian classifier using TfidfVectorizer, sensitivity and specificity scores are 86.9 percent and 98.2 percent, respectively with a false positive rate of 7.6 percent. 

The deep learning model achieved 95.2 percent and 99.6 percent, respectively, for sensitivity and specificity. It has a false positive rate of 1.4 percent. In comparison, deep learning model performed the best. While Naive Bayesian and deep learning methods explored in this paper did not outperform Graham's metrics, they still performed generally well (>$80 percent). 

## Resources
To download raw data used in this project, visit [Spam Assassin](https://spamassassin.apache.org/old/publiccorpus/). Downloaded versions are as follows:
- 20030228_easy_ham.tar.bz2
- 20030228_easy_ham_2.tar.bz2
- 20030228_hard_ham.tar.bz2
- 20030228_spam.tar.bz2
- 20050311_spam_2.tar.bz2
