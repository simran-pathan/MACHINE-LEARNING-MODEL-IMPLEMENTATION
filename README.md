# MACHINE-LEARNING-MODEL-IMPLEMENTATION
COMPANY: CODTECH IT SOLUTIONS

NAME: SIMRAN AYUBKHAN PATHAN

INTERN ID: CT08KSV

DOMAIN: PYTHON

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

*CODE EXPLANATION *: 

This Python script implements a Spam Detection System using Natural Language Processing (NLP) and Machine Learning with Scikit-Learn, Pandas, NumPy, and Seaborn. It processes a dataset of SMS messages to classify them as spam or ham (not spam) using the Naïve Bayes algorithm.

1. Libraries Used
Pandas & NumPy: Handle and process the dataset.
Seaborn & Matplotlib: Visualize the confusion matrix.
Scikit-Learn: Perform text processing, train-test split, and build the classifier.

2. Dataset Handling
Loads spam.csv and selects relevant columns (label and message).
Maps labels: "ham" → 0, "spam" → 1.
Splits data into training (80%) and testing (20%) sets using train_test_split().

3. Text Preprocessing
Converts messages into numerical form using CountVectorizer (converts text into a word count matrix).
Applies TF-IDF Transformer to weigh word importance based on frequency.

4. Model Training
Uses Multinomial Naïve Bayes (MultinomialNB), a common algorithm for text classification.
Fits the model on X_train_tfidf and y_train.

5. Model Evaluation
Predicts labels for X_test_tfidf.
Calculates accuracy score (accuracy_score()).
Generates a confusion matrix (true positives, false positives, etc.) using confusion_matrix().
Visualizes the confusion matrix with Seaborn’s heatmap().
Displays precision, recall, and F1-score with classification_report().

6. Output & Insights
Prints dataset details, model accuracy, and performance metrics.
The confusion matrix highlights classification performance.
The classification report shows how well the model differentiates spam from ham.

*OUTPUT*:

![image](https://github.com/user-attachments/assets/41979e99-4ef7-4ddc-8a40-ee286ca62d4c)

