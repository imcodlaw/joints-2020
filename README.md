# joints-2020
A binary text classification task using Bag of Words

The goal of this task is to classify e-mails into 2 classes (spam or not spam). Spam e-mails are labeled as 'Result' equals to 1 and non spam e-mails are labeled as 'Result' equals 0.

The obtained dataset has training and testing set which consist of 3620 and 1552 e-mails respectively. The dataset has only Bag of Words features which is basically number of occurences of each words at each e-mails. 

There are some problems that need to be solved in order to make a good classification. Some major problems :
- All of the words are labeled as word-1 to word-40, no information about what kind of words they possibly are
- Imbalanced class
- Outliers
- Missing values

In this notebook all of the problems are going to be treated step by step so machine learning model(s) are able to make an accurate prediction.
