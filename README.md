# Resume-Job-Description-Matching-System
An NLP-based system that automatically evaluates how well a candidate’s resume aligns with a given job description. The project extracts skills, compares keywords, and calculates a match score using text similarity techniques.

🚀 Resume–Job Description Matching System

An NLP-based system that automatically evaluates how well a candidate’s resume aligns with a given job description. The project extracts skills, compares keywords, and calculates a match score using text similarity techniques.

🔍 Features

Skill Extraction from both Resume & JD (Python, SQL, Excel, Communication, etc.)

TF-IDF Text Similarity to calculate resume–JD match percentage

Automatic Skill Comparison → Finds matching, missing & extra skills

Clean, readable UI (Colab notebook)

Expandable architecture (easy to plug in BERT embeddings later)

🧠 How It Works

User uploads:

Resume text

Job description text

The system:

Cleans & preprocesses text

Extracts relevant skills from a predefined skills dataset

Calculates similarity using TF-IDF vectorization + cosine similarity

Outputs:

Match Score (%)

Skills found

Missing skills

Recommendation summary

📊 Tech Stack

Python

NLP (scikit-learn, NLTK/spacy)

TF-IDF Vectorization

Cosine Similarity

Pandas, NumPy

Optional: BERT models (for future upgrade)
