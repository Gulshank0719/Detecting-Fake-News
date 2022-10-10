# Detecting-Fake-News
To build a model to accurately classify a piece of news as REAL or FAKE.
DataSet : https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view

What is Fake News?
A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

TFIDF works by proportionally increasing the number of times a word appears in the document but is counterbalanced by the number of documents in which it is present. Hence, words like 'this', 'are' etc., that are commonly present in all the documents are not given a very high rank.

Passive-Aggressive Algorithms:
Passive-Aggressive algorithms are called so because :
Passive: If the prediction is correct, keep the model and do not make any changes. i.e., the data in the example is not enough to cause any changes in the model. 
Aggressive: If the prediction is incorrect, make changes to the model. i.e., some change to the model may correct it.

Important parameters:
C : This is the regularization parameter, and denotes the penalization the model will make on an incorrect prediction.
max_iter : The maximum number of iterations the model makes over the training data.
tol : The stopping criterion. If it is set to None, the model will stop when (loss > previous_loss  –  tol). By default, it is set to 1e-3.
