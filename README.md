# Spam-Email-Classifier-With-Logistic-Regression
This project demonstrates the implementation of a spam email classifier using logistic regression and TF-IDF. The classifier is trained on a labeled dataset consisting of both "ham" (non-spam) and "spam" emails, https://www.kaggle.com/datasets/venky73/spam-mails-dataset. The goal of this project is to automatically classify emails as either spam or ham based on their content.
  
  Key Features:  
    
    * Text Preprocessing: The project preprocesses raw email text by performing tasks such as tokenization, stopword removal, and vectorization using TF-IDF.
      
    * Logistic Regression Model: A machine learning model is trained using logistic regression to classify emails.
      
    * Prediction Interface: Users can input email content, and the system will classify the email as spam or ham.
      
    * Model Saving: The trained model and vectorizer are saved as .pkl files for future use and deployment.

    TODO:
    Flask API: Can be extended to deploy the model as a RESTful API for real-time classification.



