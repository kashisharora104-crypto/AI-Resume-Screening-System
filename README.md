# AI Resume Screening System

## Overview
Recruiters often have to go through multiple resumes manually, which is time-consuming and inconsistent. To address this, I built a simple AI-inspired resume screening system that evaluates candidates against a given job description and ranks them accordingly.

The goal of this project was not just to generate outputs, but to design a practical system that mimics how a recruiter thinks while shortlisting candidates.

---

## How It Works
The system takes:
- A job description
- Multiple candidate resumes

It then evaluates each candidate based on:
- Key technical skills (Python, SQL, Excel, Data Visualization)
- Relevant experience (internships/projects)
- Educational background

Each resume is processed using a rule-based scoring logic, and the system generates:
- A match score (0–100)
- Key strengths
- Key gaps
- A recommendation (Strong Fit / Moderate Fit / Not Fit)

Finally, candidates are ranked and a decision (Shortlist/Reject) is assigned along with a brief reason.

---

## Output
The final output is a structured table that helps quickly compare candidates and identify the best fits for the role.

---

## Tech Stack
- Python
- Pandas
- Google Colab

---

## Why This Approach
Instead of overcomplicating the solution, I focused on building something that is:
- Simple and practical
- Easy to understand and extend
- Close to real-world hiring workflows

The system can be easily extended in the future by integrating LLM APIs for automated evaluation or by adding resume parsing from PDFs.

---

## Future Improvements
- Integrate LLMs (like GPT) for more contextual evaluation  
- Add support for PDF resume parsing  
- Build a simple UI/dashboard for recruiters  

---
## Suggested Improvements to Hiring Process

- Automating initial resume screening can significantly reduce recruiter workload
- Standardized scoring ensures fair and consistent evaluation
- Ranking candidates helps prioritize interviews efficiently
- Integrating this system with ATS tools can streamline hiring workflows

  ---
## Note
This project focuses on system design and logical evaluation rather than model training, aligning with real-world AI-assisted workflows.
