# ChatFlaskOR

A simple Flask-based web chat application that connects to AI models through OpenRouter API.

## Features

- 🤖 Chat with DeepSeek R1 (free model) via OpenRouter
- 💬 Clean, modern chat interface
- 🎨 Beautiful gradient UI design
- ⚡ Fast and lightweight

## Prerequisites

- Python 3.7+
- OpenRouter API key ([Get one here](https://openrouter.ai/))

## Installation

1. Clone the repository:
```bash
git clone https://github.com/eniompw/ChatFlaskOR.git
cd ChatFlaskOR
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root:
```bash
OPENROUTER_API_KEY=your_api_key_here
```

## Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

3. Start chatting with the AI!

## Project Structure

```
ChatFlaskOR/
├── app.py              # Flask application and API routes
├── templates/
│   └── index.html      # Chat interface
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (not tracked)
└── README.md          # This file
```

## Technologies Used

- **Flask** - Web framework
- **OpenAI Python SDK** - API client
- **OpenRouter** - AI model gateway (free models available)
- **python-dotenv** - Environment variable management

## Model

This application uses the free `tngtech/deepseek-r1t2-chimera` model via OpenRouter. 

- **Model Details**: [DeepSeek R1 T2 Chimera](https://openrouter.ai/tngtech/deepseek-r1t2-chimera:free)
- **OpenRouter Quickstart**: [Integration Guide](https://openrouter.ai/docs/quickstart)
- **All Models**: [Browse available models](https://openrouter.ai/)

## License

See LICENSE file for details.