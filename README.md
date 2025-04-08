📧 Spam Mail Detection using Naive Bayes

This project demonstrates a machine learning approach to identifying and filtering out spam emails using the Naive Bayes algorithm. Built using Python, this solution walks through the complete pipeline of text preprocessing, feature extraction, model training, and performance evaluation, making it a strong beginner-to-intermediate level NLP project.

🔍 Project Highlights

Dataset: The project uses the well-known SMS Spam Collection Dataset, which contains labeled messages classified as either ham (not spam) or spam.

Text Preprocessing:

Conversion of all text to lowercase for uniformity

Removal of punctuation and non-alphabetic characters

Stopword removal to eliminate commonly used words with little predictive value

Stemming using NLTK's Porter Stemmer to reduce words to their root form

Feature extraction using TF-IDF Vectorization to convert text data into numerical format

Model Training:

Employed Multinomial Naive Bayes, a popular algorithm for text classification tasks due to its speed and effectiveness

Split the dataset into training and testing sets to evaluate generalization performance

Evaluation Metrics:

Accuracy Score to measure the overall correctness of the model

Precision Score to ensure fewer false positives (important for spam detection)

Confusion Matrix to visualize the classification results and error distribution

Visualization:

Used matplotlib and seaborn to create bar plots and heatmaps, providing visual insights into dataset balance and model performance

🛠️ Technologies & Libraries

Programming Language: Python

Libraries:

pandas, numpy – data manipulation

nltk – natural language processing (tokenization, stopwords, stemming)

scikit-learn – model training, TF-IDF vectorization, evaluation metrics

matplotlib, seaborn – data visualization

📈 Results

The model achieved a high level of accuracy and precision, successfully distinguishing spam messages from non-spam. The simplicity and interpretability of the Naive Bayes algorithm make it an excellent choice for this task.
