This project classifies messages as spam or ham (non-spam) using a text-based machine-learning approach. 
The dataset was preprocessed with tokenization, stop-word removal, and stemming. 
Text was converted into numeric features using CountVectorizer, and a Multinomial Naive Bayes classifier was trained to learn text patterns that differentiate spam from legitimate messages.
The model achieved an accuracy score of 98% , demonstrating highly effective spam detection performance. Model performance was further evaluated using a confusion matrix.

Technologies & Libraries Used:
Python, Pandas, NumPy, Scikit-learn, re(regex), CountVectorizer, Naive Bayes
