# Spam-Identifier-By-Akash-sharma
Identifying SPAM on social media (twitter) using Natural Language Processing and Machine Learning.
Data consists of 0.74 GB of information with 656,000 observations. 
Each observation includes a tweet and information about the Twitter account.
The final dataset used for creating classification models includes 15,179 spam messages (produces by suspended accounts ornon-exact duplicates messages) and 222,962 ‘normal’ tweets. 
Therefore for every spam message, we have 15 ‘normal’ messages. 
We can see from the table that K Near- est Neighbour(KNN) and Gaussian Naive Bayes take the least training time and Linear Support Vector Machines(SVM) take the longest time to train. 
In terms of training scores Random Forest and Decision Tree show 100% accuracies which is a clear case of Overfitting and needs to be investigated further individually by K fold cross validation. 
However the test scores in each of these classifiers give expected results. Apart from the overfitted Classifers the highest accuracy is given by Gradient Boosting Classifier with 80% accuracy followed by K Nearest Neighbours (KNN). 
In terms of test scores Random Forest gives 75% accuracy closely followed by Gradient Boosting Classifier.Overall Gradient boosting classifier gives better results.
Dataset cannot be provided on github due to confidential nature and data protection rules.
