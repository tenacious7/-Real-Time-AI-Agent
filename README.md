# 🤖 Real-Time AI Agent

<div align="center">

![AI Agent](https://img.shields.io/badge/AI-Agent-blue?style=for-the-badge)
![Real Time](https://img.shields.io/badge/Real--Time-Data-green?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open--Source-❤️-red?style=for-the-badge)

*Your personal AI assistant that knows what's happening RIGHT NOW*

[Demo](#demo) • [Features](#features) • [Installation](#installation) • [Usage](#usage)

</div>

## 🚀 What This Does

Tired of AI assistants giving you outdated information? This AI agent scrapes real-time web data to give you current, accurate answers to any question.

**Think Perplexity AI, but built by you, for you.**

## ✨ Features

- 🌐 **Real-time web scraping** - Gets fresh data every time
- 🧠 **Google Gemini integration** - Powered by advanced AI
- 🔍 **SerpAPI search** - Access to live search results  
- 💭 **Memory buffer** - Remembers conversation context
- 🧮 **Built-in calculator** - Handles math and calculations
- 💬 **Chat interface** - Natural conversation flow

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Workflow Engine | n8n |
| AI Model | Google Gemini |
| Search API | SerpAPI |
| Memory | Buffer Window |
| Interface | Chat Trigger |

## 📋 Prerequisites

Before you start, make sure you have:

- n8n installed ([Installation Guide](https://docs.n8n.io/getting-started/installation/))
- Google Gemini API key
- SerpAPI key

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/realtime-ai-agent
cd realtime-ai-agent
```

### 2. Set up n8n
```bash
# Install n8n globally
npm install n8n -g

# Or use Docker
docker run -it --rm --name n8n -p 5678:5678 n8nio/n8n
```

### 3. Get Your API Keys

#### Google Gemini API
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy and save it securely

#### SerpAPI Key  
1. Sign up at [SerpAPI](https://serpapi.com/)
2. Get your API key from dashboard
3. Copy and save it securely

### 4. Import the Workflow
1. Open n8n (usually at `http://localhost:5678`)
2. Click "Import workflow"
3. Upload the `workflow.json` file
4. Configure your API credentials in the respective nodes

## 🎯 Usage

### Basic Chat
1. Start the workflow in n8n
2. Open the chat interface
3. Ask any question - the agent will search for real-time data and respond

### Example Conversations
```
You: "What's the current price of Bitcoin?"
Agent: *searches web* "As of today, Bitcoin is trading at $43,250..."

You: "Calculate 15% of 2,500"  
Agent: *uses calculator* "15% of 2,500 is 375"

You: "What's happening with Tesla stock?"
Agent: *searches latest news* "Tesla stock is currently..."
```

## 📁 Project Structure

```
realtime-ai-agent/
├── workflow.json          # n8n workflow configuration
├── README.md             # You're reading this!
├── docs/                 # Additional documentation
└── examples/             # Example use cases
```

## 🔧 Configuration

### Setting up API Credentials in n8n

1. **Google Gemini**: 
   - Node: "Google Gemini Chat Model"
   - Add your API key in credentials

2. **SerpAPI**:
   - Node: "SerpAPI" 
   - Add your API key in credentials

## 🎨 Customization

Want to extend this? Here are some ideas:

- Add more tools (weather, news, stock APIs)
- Integrate with Discord/Slack
- Add voice input/output
- Create a web interface
- Add specific domain knowledge

## 🤝 Contributing

Found a bug? Have a cool feature idea? 

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- n8n for the amazing workflow automation platform
- Google for Gemini AI
- SerpAPI for real-time search capabilities

## 🔗 Connect With Me

- LinkedIn: www.linkedin.com/in/brijesh-kumar-ghadei
---

<div align="center">

**If this helped you, give it a ⭐ and share it with fellow developers!**

Made with ❤️ by Brijesh

</div>
