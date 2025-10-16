# ai-resume-screener
AI-powered resume parser that automatically extracts skills, matches candidates with jobs, and provides intelligent compatibility scores.

## 🚀 Features
- **PDF Resume Parsing** - Extract text, skills, experience, and education from resumes
- **AI-Powered Matching** - Intelligent candidate-job compatibility scoring (1-10)
- **Web Dashboard** - User-friendly interface for uploads and results
- **Detailed Analytics** - Strengths, weaknesses, and match justifications

## 🛠️ Installation(VSCODE)
(bash)
cd ai-resume-screener
pip install -r requirements.txt
python app.py

📁 Project Structure
text
ai-resume-screener/
├── app.py              # Flask backend
├── resume_parser.py    # PDF parsing & data extraction
├── matcher.py         # AI matching algorithms
├── templates/
│   └── index.html     # Web dashboard
└── requirements.txt   # Dependencies
🔧 API Endpoints
POST /upload-resume - Upload and parse resume

POST /add-job - Add job description

POST /match-candidates - Get compatibility scores

GET /jobs - List all jobs

🤖 AI Matching Prompts
python
"Compare resume skills {skills} with job requirements {job_desc}. 
Provide score (1-10) with justification, strengths, and weaknesses."

🎥 Demo
https://drive.google.com/file/d/1EMjLNNwJurTdGpe5-IesACnM5A04WyFY/view?usp=sharing


👨‍💻 Developer
Riya Raulgaonkar - 22BAI10057

