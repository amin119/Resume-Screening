# Resume Category Classification System

A machine learning application that automatically categorizes resumes into job categories using NLP and SVM classification.

## Features
- Supports PDF, DOCX, and TXT file formats
- Text extraction and cleaning pipeline
- Pre-trained classification model (SVM)
- Simple Streamlit web interface

## Setup

1. **Download model files** and place in project root:
   - clf.pkl (Classifier)
   - tfidf.pkl (Vectorizer) 
   - encoder.pkl (Label Encoder)

 [This is the link to the 3 pkl files] https://drive.google.com/drive/folders/1_PB8KafR72P7d6x6_t2XcA31r2S9oX57?usp=sharing 

2. **Install requirements**:
   ```bash
   pip install streamlit python-docx PyPDF2 scikit-learn pandas nltk
