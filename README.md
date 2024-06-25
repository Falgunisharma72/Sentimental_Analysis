# Sentimental_Analysis
Overview
This repository contains a project focused on sentiment analysis, specifically detecting depression from Twitter (now X) tweets. The project explores two different approaches:

Traditional Machine Learning Approach
Advanced Deep Learning Approach
Approaches

1. Traditional Machine Learning Approach
In the file sentimental_analysis.py, a traditional machine learning approach is implemented. This method uses the following techniques:

Feature Extraction: TF-IDF (Term Frequency-Inverse Document Frequency)
Model: Multinomial Naive Bayes from Scikit-Learn
Performance:
Accuracy: 91% (0.91)

2. Advanced Deep Learning Approach
To improve the model's performance, a more advanced script is provided using Natural Language Processing (NLP) techniques. This method leverages the following:

Model: LSTM (Long Short-Term Memory)
Embeddings: Pre-trained Word Embeddings
Performance:
Loss Score: 0.72
Accuracy: 98%

Note: The exceptionally high accuracy is attributed to the limited dataset size of 10,000 samples. As the dataset size increases, the accuracy is expected to adjust accordingly.

Files
sentimental_analysis.py: Contains the traditional machine learning approach using TF-IDF and Multinomial Naive Bayes.
advanced_sentimental_analysis.py: Contains the advanced deep learning approach using LSTM and pre-trained word embeddings.
Dataset
The dataset used in this project consists of 10,000 samples of tweets. It is important to note that the performance metrics, particularly the accuracy, are influenced by the limited dataset size.

Contributions
Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
