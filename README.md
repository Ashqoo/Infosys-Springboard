
#  AI Agent to Test Commands (Flask + LangGraph)

This project is a simple AI Agent-based web application built using **Flask** and **LangGraph**.  
It provides a clean web interface where users can enter testing instructions, which are then processed by a baseline AI agent and returned as structured JSON output.

This repository represents the **initial milestone** of the project, focusing on environment setup, project structure, and frontend–backend integration.


## Project Structure

ai-agent-test/
│
├── app.py
├── requirements.txt
├── README.md
│
├── agent/
│   ├── __init__.py
│   └── langgraph_agent.py
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css


## Technologies Used

- Python 3
- Flask
- LangGraph
- Playwright (for future automation)
- HTML, CSS, JavaScript
- JSON

---

## Installation & Setup

## Clone the Repository

```bash
git clone https://github.com/your-username/ai-agent-test.git
cd ai-agent-test

## Create Virtual Environment
python -m venv venv
venv\Scripts\activate

##Run the Application
python app.py


## Open in Browser
http://127.0.0.1:5000/
