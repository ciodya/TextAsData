Supervised text classification tasks(Based on Reddit datasets):
Thread subreddit classification (Part A), and comment discourse classification (Part B).  

·?Use the text of the thread including all of its posts to learn a classification model using on the Scikit Learn package. 
The labels to predict are the ?subreddit? for the thread. Experiments are condected using two vectorizers: 
(a) One hot encoding  (b) TfidfVectorizer 
and three classifiers: 
(a) LogisticRegression (b) SVC? Classifier (SVM with RBF kernel - not Linear kernel) (c) BernouliNB classifier

·Improve the effectiveness of a baseline LogisticRegression with TF-IDF vectorization by parameter tuning, error analysis,
and feature development.

·Build and evaluate a text classification model for comment discourse prediction. Use a                  
LogisticRegression classifier with TF-IDF features.

· Implement 6 additional features to improve discourse classification.Evaluate models using accuracy, precision,
recall and F1 measure.
