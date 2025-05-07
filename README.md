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
