# 🎓 EdTech Multi-Agent AI Tutor

## 📌 Problem Statement
Online students often struggle with time management, lack of personalized learning, difficulty in solving doubts, and maintaining study consistency.  
Traditional online platforms don’t offer continuous guidance or adaptive support, leading to reduced productivity and poor outcomes.  

This project introduces a multi-agent AI tutor system that collaborates like a virtual teaching assistant team to make online learning more effective and engaging.

## 🤖 Project Description
We designed a system of AI agents that work together to support students throughout their learning journey:

- 🗓️ Study Planner Agent → Manages study hours, schedules, and deadlines.  
- ❓ Doubt Solver Agent → Provides explanations and solutions to questions.  
- 📖 Concept Simplifier Agent → Breaks down complex concepts into simple terms.  
- 💡 Motivator Agent → Sends reminders, encouragement, and productivity nudges.  
- 📚 Resource Curator Agent → Suggests videos, articles, and coding exercises.  

These agents can act independently but also collaborate. For example, the Doubt Solver may call the Simplifier Agent if a student struggles to understand the first explanation.

## 🛠️ Tech Stack
- LangChain – Agent orchestration and chaining  
- AutoGen – Multi-agent communication and collaboration  
- Streamlit / Gradio – Interactive demo interface  
- OpenAI GPT-3.5 / GPT-4 – Reasoning and natural language responses  

## 🚀 Setup Instructions
```bash
# Clone the repository
git clone <your-repo-link>
cd <repo-folder>

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run the demo app
streamlit run app.py
