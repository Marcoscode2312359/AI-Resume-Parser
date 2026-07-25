# AI Resume Parser

This project is a Python-based Resume Parser that compares a candidate's resume with a given Job Description and generates an ATS compatibility score.

The idea behind this project is to automate the initial resume screening process by extracting important information from resumes and checking how well they match the required job skills.

## Features

- Parse resumes in PDF and DOCX format
- Read and analyze Job Description
- Extract candidate information
- Compare resume with Job Description
- Generate ATS Match Score
- Highlight matching and missing skills
- Process multiple resumes

## Technologies Used

- Python
- Groq LLM
- Pydantic
- PyPDF
- python-docx
- dotenv

## Project Structure

```
AI-Resume-Parser
│
├── resumes/
├── main.py
├── resume_parser.py
├── pyproject.toml
├── README.md
├── .gitignore
└── .env (Not uploaded)
```

## How to Run

### Clone the repository

```bash
git clone https://github.com/Marcoscode2312359/AI-Resume-Parser.git
```

### Go to project folder

```bash
cd AI-Resume-Parser
```

### Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
uv sync
```

### Create a .env file

```
GROQ_API_KEY=YOUR_API_KEY
```

### Add resumes

Place your resumes inside the `resumes` folder.

### Run the project

```bash
python main.py
```

## Output

The application analyzes each resume and provides:

- Candidate Name
- Skills
- Education
- Experience
- ATS Score
- Missing Skills
- Final Recommendation

## Why I Built This Project

I built this project to learn how Large Language Models can be used in recruitment and resume screening. Instead of relying only on keyword matching, this project uses AI to understand resume content and compare it with the job description.

It also helped me improve my knowledge of Python, prompt engineering, JSON parsing with Pydantic, and working with APIs.

## Future Improvements

- Web interface using Streamlit
- Drag and Drop resume upload
- Export results to Excel
- Dashboard for recruiters
- Support for multiple job descriptions
- Resume ranking based on ATS score

## Note

This repository does not include API keys or any sensitive information. The `.env` file is ignored using `.gitignore`.

Sample resumes can be added to the `resumes` folder for testing.

## Author

**Aman Mishra**

Associate Data Scientist

LinkedIn:  
https://www.linkedin.com/in/aman-mishra-03b266290

GitHub:  
https://github.com/Marcoscode2312359