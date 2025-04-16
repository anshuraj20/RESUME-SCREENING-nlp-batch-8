# Resume Screening

This project focuses on building an automated Resume Screening system using Python and Machine Learning. The system helps classify resumes into appropriate job categories by analyzing the text content of resumes.

---

## 📌 Project Overview

The Resume Screening System is designed to assist recruiters by automatically categorizing resumes based on their content, allowing faster shortlisting of candidates. The project leverages Natural Language Processing (NLP) techniques for text preprocessing and a machine learning model for classification.

---

## 🚀 Features

- Automatic text cleaning of resumes
- Balancing of imbalanced categories
- Vectorization of text using TF-IDF
- Training a machine learning model for multi-class classification
- Generation of classification reports to evaluate performance
- Saving trained models for future prediction

---

## 🧠 Workflow

1. **Data Loading:**  
   - Load the dataset of resumes and their categories.

2. **Data Exploration:**  
   - Explore the distribution of categories.
   - Sample visualizations of resumes.

3. **Data Preprocessing:**  
   - Clean the text by removing:
     - URLs
     - Hashtags
     - Mentions
     - Special characters
     - Punctuations

4. **Class Balancing:**  
   - Balance classes to avoid bias during training.

5. **Text Vectorization:**  
   - Convert cleaned text into numerical format using TF-IDF.

6. **Model Training:**  
   - Split data into training and testing sets.
   - Train the model and evaluate using a classification report.

7. **Saving the Model:**  
   - Save trained models for later use.

8. **Prediction System:**  
   - Predict the category of new unseen resumes.

---

## 🛠️ Tech Stack

- Python 🤖
- Pandas & NumPy for data handling
- Scikit-learn for machine learning
- Natural Language Processing (NLP) techniques

---

## ✅ Results

The trained model can predict the category of new resumes with promising accuracy, helping recruiters automate the first layer of candidate screening.

---

