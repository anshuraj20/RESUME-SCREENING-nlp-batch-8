Resume Screening with Python 🧠📄

This project demonstrates a Resume Screening Application that uses Natural Language Processing (NLP) to automatically match candidate resumes with job descriptions. It helps HR departments or recruiters quickly filter and rank candidates based on required skills.

📌 Project Objective
To build a system that:

Extracts and cleans text from resumes.

Compares the resume content with job descriptions.

Calculates similarity scores using NLP and machine learning techniques.

Ranks resumes based on the match percentage.

🚀 Features
✅ Resume parsing and text extraction.

✅ Skill extraction using NLP.

✅ Text preprocessing (tokenization, stopword removal, etc.).

✅ Cosine similarity scoring between resumes and job descriptions.

✅ Output top matching resumes with match scores.

🧰 Technologies Used
Python

Pandas, NumPy

NLTK (Natural Language Toolkit)

Scikit-learn

TfidfVectorizer

Cosine Similarity

OS and re for file and text processing

🧪 How It Works
Load Resumes: The system loads .pdf or .txt files from a specified folder.

Extract Skills: Preprocesses text and extracts potential skill keywords.

TF-IDF Encoding: Converts text data into numerical form using TF-IDF vectorizer.

Compare with Job Description: The job description is also vectorized and compared against all resumes using cosine similarity.

Ranking: Resumes are sorted and displayed based on their match scores.
