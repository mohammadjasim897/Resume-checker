# 🚀 Resume Analyzer based on Job Description (JD)

This project is a resume analysis tool that uses OCR, NLP, and ATS (Applicant Tracking System) scoring to help candidates assess how well their resume matches a given job description. It provides insights into relevant skills, matched roles, and improvement suggestions.

## 📦 Features

- Upload resume (PDF/Image format)
- Extracts text using OCR (Tesseract)
- Extracts keywords from the job description
- Matches resume content with predefined role-based skills
- Calculates ATS score
- Displays a pie chart of match percentage
- Suggests the best-fit role
- Built using Gradio for user-friendly interface

## 🧠 Tech Stack

- Python
- Gradio
- PyMuPDF
- pdf2image
- pytesseract
- nltk
- matplotlib

## 🛠️ Installation

Run the following commands before executing the app:

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
apt-get install -y poppler-utils
