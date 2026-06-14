# Resume-Screening-AI-Project
AI-powered Resume Screening System that extracts skills from resumes, matches them with job descriptions, and ranks candidates based on relevance scores.
## Overview

Resume Screening AI is a Python-based application that automatically analyzes resumes, extracts important information such as skills, education, and experience, and ranks candidates based on their relevance to a given job description.

## Features

* Upload resumes in PDF format
* Extract candidate information
* Identify key skills from resumes
* Match resumes with job descriptions
* Calculate similarity scores
* Rank candidates based on relevance
* Generate candidate summary reports

## Tech Stack

* Python 3.x
* Streamlit
* PyPDF2
* Pandas
* Scikit-learn

## Project Structure

Resume-Screening-AI/

├── app.py

├── resume_parser.py

├── ranking.py

├── requirements.txt

├── README.md

└── sample_resumes/

## Installation

1. Clone the repository:

git clone https://github.com/your-username/Resume-Screening-AI.git

2. Install dependencies:

pip install -r requirements.txt

3. Run the application:

streamlit run app.py

## How It Works

1. Upload one or more resumes.
2. Enter a job description.
3. The system extracts skills and relevant information.
4. Similarity scores are calculated.
5. Candidates are ranked based on relevance.
6. Results are displayed in ranked order.

## Sample Output

* Candidate Name
* Extracted Skills
* Match Score
* Ranking Position

## Future Improvements

* NLP-based skill extraction
* Advanced resume parsing
* Multiple job description support
* AI-powered candidate recommendations

## Author

Ananya Chauhan
