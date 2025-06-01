# AIResumeAnalyzer
About the Project 
A tool that parses information from resumes using NLP, identifies keywords, clusters them by sector, and provides recommendations, predictions, and analytics to applicants or recruiters.

Scope 
Convert resume data into structured tabular format for analytics.
Provide resume improvement tips and predictive feedback.
Increase user engagement through interactive features.
Useful for colleges to assess student resumes.
Generate analytics on desired roles.
Improve tool based on user feedback.

Tech Stack 
Frontend
Streamlit
HTML, CSS, JavaScript
Backend
Streamlit
Python
Database
MySQL
Modules
pandas
pyresparser
pdfminer3
Plotly
NLTK

Features 
Client:
Extract info: location, basic info, skills, keywords
Recommend skills, roles, courses, tips, videos
Provide resume score

Admin:
Tabular view of applicants
Download CSV of users
View uploaded resumes
Analyze feedback and ratings
Pie charts for ratings, roles, experience, location, etc.

Feedback:
Form submission
Rating system
Comment history

Requirements 
Python 3.9.12
MySQL
Visual Studio Code
Visual Studio Build Tools (C++)

Setup & Installation 
git clone https://github.com/SaiNiharikaYadav/AI-Resume-Analyzer.git

Create virtual environment and activate it:
python -m venv venvapp
cd venvapp/Scripts
activate

Install requirements:
cd../..
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm

Create MySQL database cv and update credentials in App.py
Replace resume_parser.py in pyresparser package with custom version from project folder.

To run the app:
streamlit run App.py
