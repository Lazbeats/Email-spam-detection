This project involves building an email spam detection system using machine learning. The system processes raw email text,
extracts meaningful features, and trains a Random Forest classifier to classify emails as either spam or ham (not spam).

The project follows these structured steps:

Data Loading and Inspection:
A dataset of emails was loaded from spam_ham_dataset.csv.
Text and labels were examined for structure and cleaning.

Text Preprocessing:
Emails were cleaned to remove punctuation, stopwords, and newline characters.
Words were stemmed using the Porter Stemmer for normalization.

Feature Extraction:
Bag-of-Words representation was created using CountVectorizer, converting text into a numerical matrix of word counts.

Model Training:
Data was split into training and testing sets using train_test_split.
A Random Forest Classifier was trained on the feature matrix and corresponding labels.

Model Evaluation:
The classifier was evaluated using its accuracy score on the test set.
A specific email was processed and classified to test the model in action.

What are the results and their implications?
Accuracy:
The model achieved an accuracy of 97.87%, indicating excellent performance in identifying spam and ham emails.

Specific Classification:
A test email was classified successfully, demonstrating the model’s ability to generalize to unseen data.

Real-World Applicability:
This spam detection system can be integrated into email services to automatically filter spam, saving users time and enhancing productivity.

Key Takeaways:
The preprocessing pipeline (stopword removal, stemming, vectorization) ensures robust feature representation.
Random Forest Classifier is effective for spam detection, balancing accuracy and interpretability.
The methodology demonstrates how machine learning transforms textual data into actionable insights.
