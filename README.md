# AI Resume Screening & Candidate Ranking System

## Overview
The **AI Resume Screening & Candidate Ranking System** is a Streamlit-based application that automates resume evaluation. It compares resumes against a given job description using **TF-IDF vectorization** and **cosine similarity**, ranking candidates based on relevance.

## Features
- **Automated Resume Screening**: Extracts text from PDF resumes using `PyPDF2`.
- **AI-Powered Ranking**: Uses `TfidfVectorizer` from `scikit-learn` to evaluate candidate resumes.
- **Streamlit Web Interface**: Simple and intuitive UI for job description input and resume upload.
- **Real-Time Results**: Displays ranked resumes with similarity scores.

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed.

### Setup
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo/resume-screening.git
   cd resume-screening
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application**:
   ```sh
   streamlit run app.py
   ```

## Usage
1. **Enter the job description** in the provided text box.
2. **Upload multiple resumes** (PDF format).
3. **View ranked resumes** based on their similarity to the job description.

## Technologies Used
- **Python** (Data Processing)
- **Streamlit** (UI Framework)
- **PyPDF2** (PDF Parsing)
- **scikit-learn** (TF-IDF & Cosine Similarity)
- **Pandas** (Data Handling)

## Potential Improvements
- Add **support for DOCX resumes**.
- Implement **keyword extraction** for better ranking.
- Integrate **machine learning models** for enhanced screening.
- Develop an **API for external integration**.


