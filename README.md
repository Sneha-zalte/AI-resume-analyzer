# AI Resume Analyzer

An AI-powered Resume Analyzer built with Python, Streamlit Hugging Face Transformers.
This web app extracts text from resumes (PDF/DOCX) and analyzes them against a given job description to provide insights on skills match, missing keywords, and overall relevance.

# Features

- Upload PDF/DOCX resumes
- Paste any Job Description
- AI-powered analysis using BERT embeddings
- Detects missing skills & keywords
- Provides a match percentage
- Clean Flask-based dynamic UI

# Tech Stack

Frontend: HTML, CSS (Bootstrap for styling)
Backend: Python (streamlit)
AI Model: Hugging Face sentence-transformers
File Parsing: pdfplumber, docx2txt
Deployment Ready: Works locally or can be hosted on Render / Heroku / AWS

# Project Structure
AI-Resume-Analyzer/
│── app.py              # Flask backend
│── requirements.txt    # Dependencies
│── templates/
│    └── index.html     # Frontend UI
│── static/
│    └── style.css      # Styling
│── uploads/            # Uploaded resumes

# Installation & Usage

1- Clone the repository
git clone https://github.com/your-username/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer

2️- Install dependencies
pip install -r requirements.txt

3️- Run the app
streamlit run app.py

4️- Open in browser

# Deployment
You can deploy this app on:
Heroku
Render
PythonAnywhere
[AWS / GCP / Azure]

# Future Enhancements
Add ATS scoring system
Support for multiple resumes at once
Provide improvement suggestions

# Author
Sneha Zalte
Passionate about AI, NLP & Web Development

# If you like this project, don’t forget to ⭐ star the repo!
