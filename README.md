## AI Resume Screening & Candidate Ranking System  

This project is an AI-powered resume screening and ranking system that helps recruiters compare resumes against a job description. It uses **TF-IDF and cosine similarity** to score resumes based on relevance and provides improvement suggestions for candidates.

## Features  
âœ… Upload multiple resumes (PDF format)  
âœ… Extract text from resumes using **PyPDF2**  
âœ… Rank resumes based on job description similarity (TF-IDF + Cosine Similarity)  
âœ… Provide improvement suggestions for candidates  
âœ… Interactive Streamlit interface for easy use  

## Technologies Used  
- **Python**  
- **Streamlit** (for the web interface)  
- **PyPDF2** (to extract text from PDFs)  
- **Scikit-Learn** (TF-IDF and cosine similarity)  
- **Pandas** (for data handling)  
- **NumPy** (for data manipulation)  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Akankshamanyada/Ai-resume-project
   cd your-repo-name
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:  
   ```bash
   streamlit run app.py
   ```

## How It Works  
1. Enter the **job description** in the text box.  
2. Upload **multiple resumes** in PDF format.  
3. Click the **"Rank Resumes"** button.  
4. View **match scores** and **improvement suggestions**.  
