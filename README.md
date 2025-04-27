# YouTube Bot - AI-Powered Content Assistant

A powerful AI-driven YouTube content assistant that leverages multiple language models and AI services to help with content creation, analysis, and management.

## Features

- Integration with multiple AI services:
  - OpenAI
  - Anthropic
  - Google Gemini (PaLM)
  - Hugging Face models
- Content analysis and generation
- Environment variable management
- Streamlit-based web interface

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ytbot.git
cd ytbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your environment variables:
Create a `.env` file in the root directory with your API keys:
```
OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key
GOOGLE_API_KEY=your_google_key
HUGGINGFACE_API_KEY=your_huggingface_key
```

## Usage

1. Start the Streamlit application:
```bash
streamlit run ytbot.py
```

2. Access the web interface through your browser (typically at http://localhost:8501)

## Dependencies

- langchain
- langchain-core
- langchain-openai
- langchain-anthropic
- langchain-google-genai
- langchain-huggingface
- python-dotenv
- streamlit
- numpy
- scikit-learn

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
