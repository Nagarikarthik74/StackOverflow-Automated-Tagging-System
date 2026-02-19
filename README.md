📌 Project Overview
The StackOverflow Automated Tagging System is an NLP-based machine learning project that automatically predicts relevant tags for programming questions based on their title and description. This system helps in organizing large volumes of developer queries efficiently and improves content discoverability.
This is a multi-label classification problem where a single question can have multiple relevant tags.

🎯 Problem Statement
Stack Overflow contains millions of programming-related questions. Manually tagging each question is time-consuming and inconsistent. The goal of this project is to build a machine learning model that can automatically predict appropriate tags using Natural Language Processing techniques.

📂 Dataset Description
The dataset consists of:
* Question Title
* Question Body (Description)
* Tags (Target variable – Multi-label)

The data was cleaned and preprocessed by:
* Removing HTML tags
* Removing special characters
* Lowercasing text
* Removing stopwords
* Tokenization

🛠️ Tech Stack
* Python
* Pandas & NumPy
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Scikit-learn
* Logistic Regression
* Random Forest
* Multi-label Classification
* Pickle (Model Saving)

📊 Model Performance
* Applied TF-IDF for feature extraction
* Implemented multi-label classification models
* Evaluated using:
Precision
Recall
F1-Score
* Selected the best-performing model after hyperparameter tuning
* The final model achieved strong performance in predicting relevant tags accurately.


📌 Author
Karthik N
Aspiring Data Scientist | Machine Learning Enthusiast


