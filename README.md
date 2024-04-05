# SMS Spam Classification

This is a machine learning project for classifying SMS messages as spam or non-spam. The project uses two different vectorization techniques: CountVectorizer and TF-IDF Vectorizer, and compares their performance using K-Nearest Neighbors (KNN) classifier.

## Methodology
To begin, the initial step involved preprocessing the raw text messages, which included eliminating punctuation and stop words, and converting all text to lowercase. This preprocessing aimed to prepare the text messages for machine learning tasks. Subsequently, the preprocessed text messages were converted into numerical feature vectors using two distinct techniques: CountVectorizer and TF-IDF Vectorizer. These methods were employed to transform the text data into a suitable format for machine learning algorithms.

For the task of SMS spam classification, the K-Nearest Neighbors (KNN) classifier was selected as the model. This choice was made due to its simplicity and effectiveness in classification tasks. The models underwent training and evaluation using the accuracy metric on both the training and test datasets.

Finally, the models' performances were compared based on their accuracy on the training and test datasets. It was observed that the CountVectorizer with KNN classifier outperformed the TF-IDF Vectorizer with KNN classifier in terms of accuracy. Specifically, the CountVectorizer with KNN model attained an accuracy of 0.973 on the training set and 0.968 on the test set, whereas the TF-IDF Vectorizer with KNN achieved an accuracy of 0.920 on the training set and 0.916 on the test set. Consequently, it was deduced that the CountVectorizer with KNN classifier exhibits greater reliability and accuracy in predicting outcomes for the provided dataset.

## Results

The findings indicate that the CountVectorizer with KNN classifier surpasses the TF-IDF Vectorizer with KNN classifier. Specifically, the former achieved an accuracy of 0.973 on the training set and 0.968 on the test set, while the latter attained an accuracy of 0.920 on the training set and 0.916 on the test set.

## Conclusions

The results suggest that employing CountVectorizer with KNN classifier leads to greater reliability and accuracy in predicting the outcome of the provided dataset. This project could be expanded by investigating alternative vectorization techniques and machine learning algorithms.

## Dependencies

* matplotlib  
* scikit-learn  
* pandas  
* seaborn
