Resume Builder Assistant (AI Powered)

An intelligent AI-powered Resume Builder built with Streamlit and Groq LLM (Llama 3.3 70B).
This app helps users create professional, structured resumes through natural conversation.

🚀 Features
🤖 AI-powered resume generation using Groq API
💬 Conversational interface (chat-based resume building)
🧠 Context-aware memory during session
📑 Automatic resume structuring:
Personal Information
Summary
Education
Skills
Experience
Projects
Certifications
Achievements
✍️ Smart follow-up questions for missing details
🎯 Role-based resume tailoring (e.g., AI Engineer, Data Scientist)
🧹 Clear chat & reset functionality
🎨 Modern dark-themed UI with custom styling
🛠️ Tech Stack
Python 3.10+
Streamlit
Groq API (LLaMA 3.3 70B)
python-dotenv
📦 Installation
1. Clone the repository
git clone https://github.com/your-username/resume-builder-assistant.git
cd resume-builder-assistant
2. Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install -r requirements.txt
🔑 Environment Variables

Create a .env file in the root directory:

GROQ_API_KEY=your_groq_api_key_here

👉 Get your API key from: https://console.groq.com/keys

▶️ Run the App
streamlit run app.py

Then open:

http://localhost:8501
💡 How It Works
User chats with the assistant
AI collects resume details step by step:
Name
Education
Skills
Experience
Projects
System stores conversation context
When user types "Generate my resume"
→ AI compiles a structured, professional resume
Output is formatted in clean sections
🧠 System Prompt Design

The assistant is guided by a structured system prompt that ensures:

Proper resume formatting
Missing information detection
Professional language generation
Role-specific customization
📁 Project Structure
resume-builder-assistant/
│── app.py
│── .env
│── requirements.txt
│── README.md
📌 Example Usage
User: My name is Hamza and I am a Python developer  
AI: Great! What is your education background?

User: I studied Computer Science at XYZ University  
AI: What skills would you like to include?

User: Generate my resume
AI: (returns formatted professional resume)
⚡ Future Improvements
📄 Export resume as PDF
💾 Save user profiles
🎨 Multiple resume templates
🌐 Deploy on Streamlit Cloud / Vercel
🧑‍💼 Job-specific resume scoring system

  
🧑‍💻 Author
Hamza Raza
Python & AI Developer
Building intelligent tools one project at a time.

📜 License

This project is open-source and available under the MIT License
