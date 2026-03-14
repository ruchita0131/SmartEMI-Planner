# SmartEMI Planner

An agentic AI system for personal loan optimization. Users enter their income, 
expenses, and loans — a 5-agent LangGraph pipeline analyzes their financial 
situation and generates personalized debt repayment advice powered by Google Gemini.
## Repositories
- Backend: https://github.com/ruchita0131/smartemi
- Frontend: https://github.com/ruchita0131/smartemi-frontend
## Live Application

| | Link |
|--|------|
| Frontend | https://smartemi-frontend.vercel.app |
| Backend API | https://smartemi-api.onrender.com |
| API Documentation | https://smartemi-api.onrender.com/docs |

## Demo Account

| Field    | Value            |
|----------|------------------|
| Email    | demo@smartemi.in |
| Password | demo1234         |

## Repositories

| Repository | Description |
|------------|-------------|
| [smartemi](https://github.com/ruchita0131/smartemi) | FastAPI backend, LangGraph agents, Gemini AI |
| [smartemi-frontend](https://github.com/ruchita0131/smartemi-frontend) | React frontend, Tailwind CSS, Vercel deployment |

## Agent Pipeline

The core of this project is a LangGraph StateGraph with 5 specialized agents:

| Agent | Responsibility |
|-------|---------------|
| Data Agent | Validates and structures financial input |
| Analysis Agent | Calculates DTI ratio and health score (0-100) |
| Optimizer Agent | Simulates Avalanche vs Snowball repayment strategies |
| Forecast Agent | Projects loan closure dates via amortization |
| Advisor Agent | Calls Gemini AI with full financial context |

## Tech Stack

| Layer | Technology |
|-------|------------|
| Agent Pipeline | LangGraph StateGraph |
| Backend | FastAPI, SQLAlchemy, SQLite |
| AI | Google Gemini (gemini-2.5-flash) |
| Frontend | React 19, Vite, Tailwind CSS v4 |
| Deployment | Render (backend), Vercel (frontend) |

## Features

- Financial dashboard with DTI health indicator
- Animated LangGraph pipeline visualization
- Avalanche vs Snowball strategy comparison
- Loan scenario simulator with interactive slider
- AI chat with full financial context awareness
- Dark and light mode with persistent preference
- Profile dropdown with user details
```


