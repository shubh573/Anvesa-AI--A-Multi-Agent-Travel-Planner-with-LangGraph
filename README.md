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


Tech Stack
Python 3.10+
FastAPI
Jinja2 + HTML/CSS/JavaScript frontend
LangGraph
LangChain
Groq LLMs
PostgreSQL
Tavily API
AviationStack API


Environment Variables
Create a .env file in the project root with the following variables:

DATABASE_URL=postgresql://user:password@localhost:5432/travel_db
GROQ_API_KEY=your_groq_api_key
AVIATIONSTACK_API_KEY=your_aviationstack_api_key
TAVILY_API_KEY=your_tavily_api_key
DEFAULT_ORIGIN_IATA=MUM


How to run Sage
1. Clone the repository:
    ```bash
    git clone https://github.com/shubh573/Sage.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Sage
    ```

3. Create a virtual environment (optional)
    ```bash
    conda create -n Sage python=3.11 -y
    ```

4. Activate the virtual environment:
    ```bash
    conda activate Sage
    ```

5 Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

6. Run the application:
    ```bash
    python app.py
