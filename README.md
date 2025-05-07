# 🧠 Resume Analyzer

An **AI-powered resume analysis tool** that provides detailed insights into skills, experience, education, and ATS (Applicant Tracking System) compatibility.

---

## 🚀 Features

- 🔍 Skills Analysis  
- 🧑‍💼 Experience Evaluation  
- 🎓 Education Assessment  
- 🛠️ Improvement Suggestions  
- ✅ ATS Compatibility Check  
- ⏱️ Response Time Tracking  
- 📄 Downloadable Reports  

---

## 📋 Prerequisites

### 1. Install [Ollama](https://ollama.ai)

#### For Mac/Linux:
- Download and install from [https://ollama.ai](https://ollama.ai)
- Ensure Ollama is **running in the background** (icon visible in menu bar/system tray)

### 2. Install Required Model

# Pull the Deepseek Coder model (recommended - lightweight and fast)
ollama pull deepseek-coder

# OR pull the Deepseek R1 1.5B model (more comprehensive but larger)
ollama pull deepseek-r1:1.5b
🛠️ Installation

# Clone the repository
git clone https://github.com/yourusername/resume-analyzer.git
cd resume-analyzer

# Install Python dependencies
pip install -r requirements.txt
💻 Usage

# Make sure Ollama is running

# Start the Streamlit app
streamlit run resume_analyzer.py
Then:

Upload a PDF resume

Choose the analysis options

Get detailed feedback and ATS compatibility score

Download the final report if needed

⚙️ Supported Models
Model Name	Description
deepseek-coder	✅ Recommended, fast & lightweight
deepseek-r1:1.5b	🔍 Slower but more comprehensive

📝 Notes
Resumes must be in PDF format

Analysis time depends on the model and resume length

Keep Ollama running during usage

Resume Analyzer
An AI-powered resume analysis tool that provides detailed insights about skills, experience, education, and ATS compatibility.

🚀 Features
Skills Analysis
Experience Evaluation
Education Assessment
Improvement Suggestions
ATS Compatibility Check
Response Time Tracking
Downloadable Reports
📋 Prerequisites
Install Ollama

For Mac/Linux: Download from Ollama.ai
After installation, ensure Ollama is running (check for the icon in menu bar)
Install Required Model

# Pull the Deepseek Coder model (recommended)
ollama pull deepseek-coder

# OR pull the Deepseek R1 1.5B model (larger but more comprehensive)
ollama pull deepseek-r1:1.5b
🛠️ Installation
Clone the repository:

git clone https://github.com/yourusername/resume-analyzer.git
cd resume-analyzer
Install required Python packages:

pip install -r requirements.txt
Run the application:

streamlit run resume_analyzer.py
💻 Usage
Ensure Ollama is running
Start the Streamlit app
Upload a PDF resume
Select desired analysis aspects
Get detailed analysis with response times
Download complete report if needed
⚙️ Models
Deepseek Coder: Faster, lighter model (recommended)
Deepseek R1 1.5B: More comprehensive but slower
📝 Note
Ensure your resume is in PDF format
Analysis time may vary based on the model selected and resume length
Keep Ollama running while using the application
