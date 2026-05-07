# Smart ATS Resume Analyzer

An AI-powered ATS (Application Tracking System) Resume Analyzer developed using Python, Streamlit, and Google Gemini API.  
The application evaluates resumes against job descriptions and provides ATS match analysis, missing keyword detection, and profile feedback.

---

## Features

- Resume and Job Description comparison
- ATS Match Percentage analysis
- Missing keyword identification
- AI-generated profile summary
- PDF resume upload support
- Simple and interactive Streamlit interface

---

## Tech Stack

- Python
- Streamlit
- Google Gemini API
- PyPDF2
- python-dotenv

---

## Project Structure

smart-ats-resume-analyzer/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore

Application Workflow:
Upload a PDF resume
Paste the target job description
Submit the input
The system:
Extracts resume text
Sends data to Gemini API
Evaluates ATS compatibility
Generates:
Match Percentage
Missing Keywords
Profile Summary
