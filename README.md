# FUTURE_ML_03
# Resume / Candidate Screening System (Task 3)

## Overview
This project builds a machine learning–based resume screening system
that compares candidate resumes with a given job description and ranks
candidates based on relevance.

Such systems are commonly used by companies to reduce recruiter workload
and shortlist candidates efficiently.

## Dataset
Resume Dataset (Kaggle)  
The dataset contains resume text data across multiple job categories.

## Job Description
A sample Machine Learning Engineer job description was used to evaluate
resume relevance and skill matching.

## Approach
1. Loaded and explored resume text data
2. Cleaned and preprocessed resume content
3. Converted text into numerical features using TF-IDF
4. Compared resumes with the job description using cosine similarity
5. Ranked candidates based on relevance score
6. Identified role fit and potential skill gaps

## Results
- Resumes are ranked by similarity score against the job description
- Higher scores indicate better alignment with required skills
- The system helps prioritize candidates for recruiter review

## Business Use Case
This system can help HR teams:
- Automatically shortlist candidates
- Reduce manual resume screening effort
- Identify suitable candidates faster
- Improve hiring efficiency

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorization
- Jupyter Notebook
