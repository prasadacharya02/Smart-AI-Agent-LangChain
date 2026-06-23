# 🤖 AI Chat Agent with LangChain, Chainlit & MCP

An intelligent AI assistant built using LangChain, Chainlit and GitHub Models. The application supports conversational AI, tool calling, streaming responses and Model Context Protocol (MCP) integrations.

## 🚀 Features

* 💬 Interactive chat interface using Chainlit
* 🧠 LLM integration with GitHub Models
* ⚡ Real-time streaming responses
* 🔧 Tool calling with Weather API
* 🌐 MCP (Model Context Protocol) integration
* 📚 Conversation memory and context management
* 🎯 Agent-based architecture using LangChain

## 🛠️ Technology Stack

* Python
* LangChain
* Chainlit
* GitHub Models
* WeatherAPI
* MCP (Model Context Protocol)

## 📂 Project Structure

```text
solutions/
├── phase-02/  # GitHub Models setup
├── phase-03/  # Chainlit chat interface
├── phase-04/  # LangChain agent
├── phase-05/  # Tool calling (Weather API)
└── phase-06/  # MCP integration

requirements.txt
README.md
.env.example
```

## 🎯 Key Capabilities

### AI Chat Interface

Provides a responsive conversational interface with support for multi-turn interactions.

### Tool Calling

Uses LangChain tools to fetch real-time weather information through WeatherAPI.

### MCP Integration

Connects external MCP-compatible services to extend the agent's capabilities.

### Streaming Responses

Generates responses token-by-token for a smoother user experience.

## ⚙️ Installation

```bash
git clone <repository-url>
cd <repository-name>

python -m venv .venv
source .venv/bin/activate
# Windows:
# .venv\Scripts\activate

pip install -r requirements.txt
```

Create a `.env` file:

```env
GITHUB_TOKEN=your_github_token
WEATHER_API_KEY=your_weather_api_key
```

Run the application:

```bash
python -m chainlit run solutions/phase-06/app.py
```
