# Digital Twin

## 🧠 Overview
A conversational AI-powered **Digital Twin** that represents your professional identity — acting as your virtual elevator pitch, available 24/7. It answers questions about your background, experience, skills, projects, and contact information on your behalf.

## 🏗️ Tech Stack

| Component | Technology |
|-----------|------------|
| **LLM** | [Ollama](https://ollama.com/) (Local LLM inference) |
| **Tool Calling** | Function-based tool calls for dynamic responses (e.g., email lookup, contact info) |
| **Framework** | Python |
| **Package Manager** | [uv](https://github.com/astral-sh/uv) |

## ⚙️ How It Works

1. **Knowledge Base** — The twin is grounded with a structured profile containing career history, skills, education, and contact details.
2. **Ollama LLM** — Runs locally to generate natural language responses based on the knowledge base.
3. **Tool Functions** — Custom functions are registered as tools that the LLM can invoke:
   - `record_user_details(email, name, notes)` — Records a user's contact info (email, name, notes) for follow-up
   - `record_unknown_question(question)` — Logs any question the twin couldn't answer for later review
4. **Guardrails** — Out-of-scope questions (e.g., weather) are gracefully handled, redirecting the user back to career-related topics.

## 🚀 Getting Started

```bash
# Install Ollama
brew install ollama

# Pull a model
ollama pull llama3

# Install dependencies
uv sync

# Run the Digital Twin
uv run app.py
```

## 💬 Demo

## Elevator Pitch

### 🏠 Home
![Digital Twin - Elevator Pitch Home](./test_results/home.png)

### 👤 Background and Experience
![Digital Twin - Elevator Pitch Background and Experience](./test_results/background_experience.png)

user: Tell me about your background and experience.

assistant: ## Background
I am a digital twin representing SriRamaChandra Macharayya Gangumalla, an Indian software engineer with extensive experience in the field of software development.

## Background Experience
Here's a concise overview of my professional experience:

* **Senior Software Engineer at Evernorth Health Services**: Developed and implemented AI-powered auditing platform, leading DevOps setup, CI/CD pipeline configuration.
* **Software Engineering Advisor at CoreTechnology**: Designed and developed audit companion for internal processing across Cigna & EverNorth, responsible for leading devops setup, code reviews.
* **Senior Software Engineer at BridgeThings IoT Pvt Ltd**: Led team, designed APIs for streamlining internal audit processes, contributing to innovative solutions.

## Education
* **Bachelor of Technology (B.Tech.)**, Computer Science Engineering from Jawaharlal Nehru Technological University (2005-2009)

## Skills
* Java
* Neo4j
* Javascript
* NodeRED
* NodeJS

## Additional Notes
SriRamaChandra is a lifelong learner with significant experience in software engineering.

### 🚀 Projects
![Digital Twin - Elevator Pitch Background and Experience](./test_results/projects1.png)

I'm currently working on developing an AI-powered auditing platform for Evernorth Health Services. As a software engineering advisor, I'm designing and implementing backend RESTful APIs to support audit workflow management, findings tracking, and remediation recommendations.

The project is being led by CoreTechnology – Audit Companion, where I'm also working as an engineer, in addition to my role as a Senior Software Engineer there. We're creating an AI-powered platform that will streamline and automate internal audits across Cigna & EverNorth.

In fact, I recently conducted some code reviews with our junior engineers to enforce coding standards, improve code quality, and ensure best practices across the team!

### 🛠️ Skills
![Digital Twin - Elevator Pitch Projects](./test_results/skills.png)

My strongest technical skills are:

* Java
* Neo4j
* Javascript
* NodeRED
* NodeJS
* ReactJS
* Python
* AWS
* Apache Storm
* InfluxDB
* PostGIS

I have experience with developing audit companion, leading DevOps setup and CI/CD pipeline configuration, mentoring junior and mid-level engineers on architecture patterns, coding standards, and technical problem-solving.

Please let me know if you have any specific questions or topics you'd like to discuss regarding my skills. 

By the way, I'm SriRamaChandra Macharayya Gangumalla, a life-long learner software engineer from India, with experience in working on various projects, including developing an AI-powered auditing platform designed to streamline and automate internal audit processes across companies like Cigna & EverNorth.

I'd love to chat more about my skills or explore how I can help you with your career goals.

### 📬 Get In Touch
![Digital Twin - Elevator Pitch Projects](./test_results/get_in_touch.png)

I'm SriRamaChandra Macharayya Gangumalla, the digital twin of our esteemed individual. I'd love to hear from you! What's on your mind? How can I assist you regarding your career paths or technical requirements?

Feel free to reach out to me via email at sriramaramachandra@gmail.co. My tool will record your message and send it to my virtual inbox for follow-up.

Looking forward to connecting with you!

**Profile Update:**

As a digital twin, I'll keep track of our conversation history. If you'd like to modify or update your profile, please feel free to do so:

* Your current name is SriRamaChandra Macharayya Gangumalla.
* You're an experienced Senior Software Advisor with expertise in various technologies.
* I'm the digital twin representing SriRamaChandra's career and background.

Let me know if you'd like to change anything, and I'll help!

As SriRamaChandra Macharayya Gangumalla, my contact information is:

Email: sriramaramachandra@gmail.co
Tool call: I don't know, but you can try sending me an email on sriramaramachandra@machiaryya.net.

If you'd like to learn more about me or would like to confirm your LinkedIn profile's accuracy, feel free to ask!

### ❓ Out-of-Scope Questions
![Digital Twin - Elevator Pitch Projects](./test_results/unknown_question.png)

The current weather is not available in this conversation. If you're looking for real-time weather updates, I recommend checking a reliable source such as AccuWeather or the National Weather Service.

As your digital twin SriRamaChandra Macharayya Gangumalla, I can provide information on my personal background and experiences. Would you like to know more about your career goals or the skills I possess?