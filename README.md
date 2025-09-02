# Telegram AI Agent using N8N
An AI-powered Telegram assistant built with n8n, integrating OpenAI, SerpAPI, Google Calendar, and Google Tasks. It enables natural language chat, task management, event scheduling, and web search all from Telegram AI Agent chat. The modular workflow is easy to customize and extend.

![Workflow](n8n_telegram_ai_agent_workflow.jpg)

## Features
- **Telegram Integration** – Talk to your AI agent through Telegram  
- **OpenAI Chat Model with Memory** – Context-aware, natural conversations  
- **SerpAPI Search** – Get real-time web search results  
- **Google Calendar** – Create and fetch events with natural language  
- **Google Tasks** – Manage and list tasks directly via chat

## Demo
<img src="https://github.com/user-attachments/assets/8800b8f5-7720-4339-9fe2-a56f2d056825" alt="Demo1" width="300"/>

- Used OpenAI and SerpAPI to fetch and deliver real-time weather updates for New York.

<img src="https://github.com/user-attachments/assets/c3bb3c36-73a4-4162-86d6-46be2fb49a72" alt="Demo2" width="300"/>

- Used Open AI and Simple Memory to access previous chat and then update on places to visit.

<img src="https://github.com/user-attachments/assets/73932af5-6e0c-4dbc-aa92-3cef049808ca" alt="Demo2" width="300"/>

- Used Google Calendar and Google Tasks API to book a spot on calendar and update tasks as per user queries.

![ss4](https://github.com/user-attachments/assets/2881f5ad-3ed3-45fe-b5f0-73f0283b6791)


## Tech Stack
- [n8n](https://n8n.io) – Automation & workflow engine  
- [Telegram Bot API](https://core.telegram.org/bots/api) – Chat interface  
- [OpenAI](https://platform.openai.com/) – AI-powered conversation  
- [SerpAPI](https://serpapi.com/) – Web search integration  
- [Google Calendar API](https://developers.google.com/calendar) – Event management  

## Notes

- The exported workflow does not contain your API keys or secrets
- Replace any personal emails or identifiers before publishing
- Use this as a template and customize it as needed

## License
MIT License
