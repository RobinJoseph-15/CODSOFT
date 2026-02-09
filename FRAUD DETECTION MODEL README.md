
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. 
The dataset contains real-world transaction data with a highly imbalanced target variable, where fraudulent transactions represent a very small percentage of the total. 
The workflow includes loading the dataset from Google Drive in a Google Colab environment, cleaning and preprocessing the data by removing irrelevant and 
high-cardinality features, extracting time-based features such as hour, day, and month from transaction timestamps, and encoding categorical variables using label encoding. 
The data is then split into training and testing sets using a stratified approach to preserve the class distribution. A Logistic Regression model with class balancing is 
trained as a baseline classifier, and model performance is evaluated using precision, recall, F1-score, and ROC-AUC to account for class imbalance. This project demonstrates 
a practical end-to-end fraud detection pipeline and serves as a foundation for further enhancements such as ensemble models, resampling techniques, and model explainability.
