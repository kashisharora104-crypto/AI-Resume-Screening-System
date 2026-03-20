# AI Resume Screening System

## Overview
This project is an AI-based resume screening system designed to help recruiters efficiently evaluate candidates against a job description.

## Features
- Evaluates multiple resumes against a job description
- Generates a match score (0–100)
- Identifies key strengths and gaps
- Provides recommendation (Strong Fit / Moderate Fit / Not Fit)
- Ranks candidates automatically
- Includes shortlist/reject decision with reasoning

## Approach
The system uses a rule-based evaluation logic that analyzes:
- Technical skills (Python, SQL, Excel, Data Visualization)
- Experience and project exposure
- Educational background relevance

The results are structured and ranked using Python (Pandas).

## Tech Stack
- Python
- Pandas
- Google Colab

## Output
The system generates a ranked table of candidates with:
- Score
- Strengths
- Gaps
- Recommendation
- Decision
- Reason

## Future Improvements
- Integration with LLM APIs for automated evaluation
- Resume parsing from PDF
- Web-based interface
