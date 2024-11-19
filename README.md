# spam_detection_classification_analysis
**Overview**
This project focuses on building a machine learning model to classify text messages as either spam or ham (non-spam). The model leverages the Multinomial Naive Bayes algorithm, which is effective for text-based classification tasks.
**Features**
Preprocessing text data to clean and standardize messages.
Visualizing the distribution of spam and ham messages.
Feature extraction using TF-IDF Vectorization.
Training and evaluating a Multinomial Naive Bayes model for classification.
Generating performance metrics like accuracy and confusion matrix with visualization.
**Technologies Used**
Python: Programming language for implementation.
Libraries:
pandas - Data manipulation and analysis.
numpy - Numerical operations.
matplotlib & seaborn - Data visualization.
scikit-learn - Machine learning tools and utilities.
re - Regular expressions for text preprocessing.
**Dataset**
The dataset (spam.csv) contains text messages labeled as:

ham: Non-spam messages.
spam: Unwanted promotional or malicious messages.
Dataset Columns:
v1: Category (spam/ham).
v2: Message content.

**Project Workflow**

**Data Cleaning:**
Removed unnecessary columns.
Renamed columns for better clarity.
Handled missing data and duplicates.

**Exploratory Data Analysis (EDA):**
Analyzed the distribution of spam and ham messages.
Visualized average word counts by category.

**Text Preprocessing:**
Standardized messages by removing special characters and converting to lowercase.

**Feature Extraction:**
Transformed text data into numerical format using TF-IDF Vectorization.

**Model Training:**
Trained a Multinomial Naive Bayes classifier on preprocessed data.

**Model Evaluation:**
Evaluated model performance with accuracy and confusion matrix.

**Results**
Accuracy: Achieved a high classification accuracy on the test set.
Confusion Matrix: Demonstrated strong performance in distinguishing spam from ham messages.


**Visualization**
The project includes:
Bar plot for spam vs. ham distribution.
Average word count comparison.
Heatmap of confusion matrix.

**Future Improvements**
Experiment with other classification algorithms like Logistic Regression or Support Vector Machines.
Enhance text preprocessing with techniques like lemmatization or stopword removal.
Handle imbalanced datasets using oversampling or undersampling methods.
