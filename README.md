**Summary**

This project aims to explore advanced techniques in medical text classification. Initially, the text data obtained from medical transcriptions is processed by removing transcriptions with specific category labels. Data preprocessing techniques are then applied for data preparation. During feature extraction, Bag-of-Words (CountVectorizer) and TF-IDF (TfidfVectorizer) methods are separately employed. Subsequently, traditional machine learning algorithms including Multinomial Naïve Bayes, Random Forest, XGBoost, and LightGBM are utilized for classification. Additionally, complex deep learning structures such as 1D CNN, LSTM, and GRU are implemented.

In the following phase, named entity recognition (NER) code applied in the initial stage is utilized to identify and categorize named entities, aiming to investigate their impact on text classification.

Finally, SMOTE (Synthetic Minority Over-sampling Technique) is applied for oversampling to enhance performance. This technique aids in balancing minority classes and potentially improving classification performance. The results are compared and analyzed using various classification metrics (accuracy, precision, recall, and F1-score). This study represents a comprehensive exploration of both traditional and deep learning techniques in the field of medical text classification.
