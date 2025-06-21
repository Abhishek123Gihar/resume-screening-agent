# Autonomous Resume Screening Agent

This project uses LangChain, FAISS, and OpenAI to build an autonomous agent that scans resumes
and matches them to a given job description.

## Features
- Parses PDF/TXT resumes
- Embeds content and searches via vector similarity
- Outputs top 3 matching resumes with reasoning

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Set your OpenAI API key: `export OPENAI_API_KEY=your_key`
3. Run: `python main.py`

## Output
Top-ranked resumes will be saved in `output/top_resumes.txt`