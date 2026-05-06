# AI Personal Assistant with n8n Automation

An AI-powered personal productivity assistant built using Streamlit and n8n workflow automation.

The assistant processes user requests through an AI agent connected with Groq and Gemini fallback models, enabling task automation across productivity tools and services.

---

## Features

- Web Search using SerpAPI
- Google Calendar Management
- Gmail Automation
- Task Management
- Expense Tracking with Google Sheets
- Notes Creation with Google Docs

---

## Tech Stack

### Frontend
- Streamlit
- Python

### Automation & AI
- n8n
- Groq API
- Gemini API

### Integrations
- Gmail API
- Google Calendar API
- Google Sheets API
- Google Docs API
- SerpAPI

---

## Workflow Architecture

1. User sends message through Streamlit chat interface
2. Request is sent to n8n Webhook
3. AI Agent processes the request
4. Appropriate tools/APIs are triggered
5. Response is returned to the frontend

---

## Project Screenshots

### Chat Interface

![Chat UI](screenshots/chat-ui.png)

### n8n Workflow

![Workflow](screenshots/workflow.png)

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ai-personal-assistant-n8n.git
