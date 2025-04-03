# resume_shortlisting_bert
# AI-Powered Resume Shortlisting Using NLP & BERT

## Overview
This project automates the resume shortlisting process using NLP techniques and BERT embeddings. By extracting keywords from job descriptions and matching them with candidate resumes, the system ranks the top 5 most relevant resumes. This significantly reduces manual effort in hiring processes.

## Features
- **Automated Resume Processing**: Extracts and preprocesses resumes from PDF format.
- **Keyword Extraction**: Uses NLP techniques (spaCy) to extract relevant keywords from job descriptions.
- **BERT Embeddings**: Computes similarity between job descriptions and resumes using contextual embeddings.
- **Ranking System**: Scores resumes and identifies the top 5 most relevant candidates.
- **Visualization**: Displays similarity scores using various plots to highlight top resumes.

## Technologies Used
- **Python**
- **Natural Language Processing (NLP)**
- **spaCy**
- **BERT Embeddings**
- **Regex for text parsing**
- **PyPDF2 for PDF handling**
- **Matplotlib & Seaborn for visualization**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/resume-shortlisting.git
   cd resume-shortlisting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download necessary NLP models:
   ```bash
   python -m spacy download en_core_web_sm
   ```

## Usage
1. **Prepare your dataset**:
   - Place resumes in the `dataset/testResumes` folder (PDF format).
   - Place the job description PDF in the same directory.
2. **Run the script**:
   ```bash
   python shortlist_resumes.py
   ```
3. **View Results**:
   - The script will output the top 5 resumes based on similarity scores.


## Future Enhancements
- Integration with ATS (Applicant Tracking Systems)
- Support for DOCX format
- Improved ranking with additional ML techniques

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss the proposed changes.


