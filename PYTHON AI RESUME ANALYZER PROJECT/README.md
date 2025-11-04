# 🧠 AI Resume Analyzer

## Overview  
A smart, user-friendly desktop application that analyzes resumes to determine how well they match specific job roles such as **Data Scientist**, **Software Engineer**, **Data Analyst**, and **Product Manager**.  
It evaluates skills, experience, and generates beautiful visual reports to help users improve their resumes.

---

## Algorithm Used  
**Keyword-based Greedy Scoring Algorithm**

- Each job role has a set of weighted keywords (skills & experience terms).  
- The app scans your resume and assigns scores based on keyword matches.  
- Final scores are shown for each role with percentage-based match results and visual graphs.

---

## Steps  
1. Upload or paste your resume (`.pdf`, `.docx`, or `.txt`).  
2. Choose **Analyze Resume** to generate results.  
3. View:
   - Skill Match %
   - Experience Match %
   - Overall Role Fit %
4. Explore interactive visualizations:
   - Match Comparison Chart  
   - Skill Frequency Treemap  
   - Radar Chart  
5. Manage job roles easily from the **⚙ Manage Roles** tab (edit, add, delete roles).  

---

## How to Run  
1. Unzip the folder.  
2. Make sure you have Python 3 installed.  
3. Install dependencies:  
   ```bash
   pip install ttkbootstrap pandas numpy matplotlib seaborn PyMuPDF python-docx pillow squarify
