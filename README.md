# Anvesa-AI--A-Multi-Agent-Travel-Planner-with-LangGraph-

An open-source AI travel planner that turns a natural-language trip request into a practical travel plan with flight suggestions, hotel ideas, and a day-by-day itinerary. The project uses a multi-agent workflow built with LangGraph, LangChain, and FastAPI.

Features

✈️ Flight research using AviationStack

🏨 Hotel suggestions using Tavily search

🧠 Multi-agent orchestration with LangGraph

📝 Structured travel itinerary generation

🌐 FastAPI backend with a simple web interface

💾 Conversation state persistence using PostgreSQL

⚡ LLM-powered responses with Groq



## Tech Stack
Python 3.10+

FastAPI

Jinja2 + HTML/CSS/JavaScript frontend

LangGraph

LangChain

Groq LLMs

PostgreSQL

Tavily API

AviationStack API


## Environment Variables

Create a .env file in the project root with the following variables:

DATABASE_URL=postgresql://user:password@localhost:5432/travel_db

GROQ_API_KEY=your_groq_api_key

AVIATIONSTACK_API_KEY=your_aviationstack_api_key

TAVILY_API_KEY=your_tavily_api_key

DEFAULT_ORIGIN_IATA=MUM


## Run Locally

Start the FastAPI app:

```bash
python app.py
```

The app will be available at:

```text
http://127.0.0.1:8080
```


Run the API server

python -m uvicorn app:app --reload
