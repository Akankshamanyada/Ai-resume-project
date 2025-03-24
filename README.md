## AI Resume Screening & Candidate Ranking System  

This project is an AI-powered resume screening and ranking system that helps recruiters compare resumes against a job description. It uses **TF-IDF and cosine similarity** to score resumes based on relevance and provides improvement suggestions for candidates.

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
   ```

2. Install dependencies:
   ```bash
   your-repo install -r requirements.txt
   ```

4. Run the application:  
   ```bash
   streamlit run app.py
   ```

## How It Works  
1. Enter the **job description** in the text box.  
2. Upload **multiple resumes** in PDF format.  
3. Click the **"Rank Resumes"** button.  
4. View **match scores** and **improvement suggestions**.  
