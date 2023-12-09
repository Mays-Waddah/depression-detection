# depression-detection

This project focuses on developing a Machine Learning (ML) web application for depression detection using Natural Language Processing (NLP). The application integrates ASP.NET for the frontend and Python Flask for the backend API, providing user engagement features with therapists and progress tracking functionality.

# Motivation 

I am developing a user-friendly web application that connects individuals with therapists for accessible
mental health support. By utilizing advanced NLP techniques, the application analyzes users' thoughts
and provides valuable insights into their emotional state. Additionally, the application facilitates seamless
communication and connection with therapists, allowing individuals to seek professional help and support. My motivation is to bridge the gap in mental health awareness, reduce stigma, and create a supportive
environment for individuals to prioritize their psychological well-being. Through this project, I aim to
raise awareness, provide practical tools, and empower users to connect with therapists and improve their
mental health.

# Data Collection and Pre-processing

I used a cleaned dataset that uses Reddit relate texts.
The raw data is collected through web scrapping Subreddits and is cleaned using multiple NLP techniques. The data is only in English language. It mainly targets mental health classification.

# Dataset 

The "depression_dataset_reddit_cleaned.csv" dataset is employed for training and testing the machine
learning models. It consists of cleaned and preprocessed text fields representing input data, along with
binary labels indicating the presence or absence of depression. This dataset is essential for training the
models and enabling accurate predictions on new, unseen text samples.

# Feature Extraction

Utilize the CountVectorizer from the Scikit-learn library to convert the text data into numerical
representations. Transform the text data into a matrix of token counts, where each row represents a document or text
sample and each column represents a unique token.

# Model Training and Evaluation

Apply the Multinomial Naive Bayes algorithm for binary classification of depression-related text. Split the dataset into training and testing sets using the train_test_split function from Scikit-learn. Train the Multinomial Naive Bayes model using the training data to learn the underlying patterns and
relationships within the text data. Evaluate the model's performance by predicting the presence or absence of depression on the testing data.

# Algorithms

Multinomial Naive Bayes: A classification algorithm suitable for binary and multiclass classification, used for predicting the likelihood of depression based on text data.

# Key Features

Login, different user types, Text analysis, depression detection using AI, connect with therapists, show patients info for therapists, accept/reject them.

# Frameworks, Libraries, and Dependencies

ASP.NET: Web application framework for developing the ASP.NET web application.
.NET Framework: Provides necessary tools and libraries for ASP.NET development. Scikit-learn: Python library for machine learning, including the CountVectorizer and the Multinomial
Naive Bayes algorithm. Pandas: Python library for data manipulation and analysis, used for dataset import and preprocessing. Microsoft Visual Studio: Integrated development environment (IDE) used for ASP.NET development.

# Contibution 
contriputions are welcomed .

# Contact Info
LinkedIn : mais-zaid-5a65a51aa
